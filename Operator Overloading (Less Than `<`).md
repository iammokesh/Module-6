# 🐍 Python OOP: Operator Overloading (Less Than `<`)

## 🎯 AIM

To write a Python program that demonstrates **operator overloading** by overloading the **less than (`<`)** operator using a custom class.

---

## 🧠 ALGORITHM

1. **Create Class `A`**:
   - Define the `__init__()` method to initialize the object with a value `a`.

2. **Overload the `<` Operator**:
   - Define the `__lt__()` method with logic:
     - If `self.a < o.a`, return `"ob1 is less than ob2"`
     - Else, return `"ob2 is less than ob1"`

3. **Create Objects**:
   - Instantiate two objects `ob1` and `ob2` with values.

4. **Use `<` Operator**:
   - Use `print(ob1 < ob2)` to trigger the overloaded behavior.

---

## 💻 Program
```python
class A:
    def __init__(self, a):
        self.a = a

    # Overloading the < operator
    def __lt__(self, o):
        if self.a < o.a:
            return "ob1 is less than ob2"
        else:
            return "ob2 is less than ob1"

# Create objects
ob1 = A(10)
ob2 = A(20)

# Use overloaded < operator
print(ob1 < ob2)
```

## Output

<img width="364" height="29" alt="Screenshot 2026-05-31 184714" src="https://github.com/user-attachments/assets/8a1ac6ad-6e89-4ff2-b500-a875bb5f5a49" />


## Result
By using python the code was executed successfully.
