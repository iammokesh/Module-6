<img width="606" height="86" alt="image" src="https://github.com/user-attachments/assets/02899891-c983-4373-9442-995b2e38a01c" /># # 🐍 Python OOP: Polymorphism with Classes

## 🎯 AIM

To create two specific classes — `Beans` and `Mango`. Then, create a **generic function** that can accept any object and determine its **type** (Fruit or Vegetable) and **color**, using polymorphism.

---

## 🧠 ALGORITHM

1. **Create Class `Beans`**:
   - Define `type()` method that prints `"Vegetable"`.
   - Define `color()` method that prints `"Green"`.

2. **Create Class `Mango`**:
   - Define `type()` method that prints `"Fruit"`.
   - Define `color()` method that prints `"Yellow"`.

3. **Define Generic Function `func(obj)`**:
   - Call `obj.type()` and `obj.color()` — this works with both `Beans` and `Mango` objects, showcasing **polymorphism**.

4. **Create Objects**:
   - Instantiate `Beans` and `Mango`.
   - Pass them to `func()` and execute the program.

---

## 💻 Program
```python
# Class Beans
class Beans:
    def type(self):
        print("Vegetable")

    def color(self):
        print("Green")

# Class Mango
class Mango:
    def type(self):
        print("Fruit")

    def color(self):
        print("Yellow")

# Generic function
def func(obj):
    obj.type()
    obj.color()

# Create objects
b = Beans()
m = Mango()

# Call function with different objects
func(b)
func(m)
```


## Output

<img width="606" height="86" alt="Screenshot 2026-05-31 184912" src="https://github.com/user-attachments/assets/21bc1771-d962-4dae-a924-71039aa67691" />


## Result
By using python the code was executed successfully.
