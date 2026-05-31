# 🐟 Method Overriding-Fish and Shark Class Inheritance in Python

## 🧠 AIM:
To write a Python program that demonstrates class inheritance by creating a parent class `Fish` with a method `type`, and a child class `Shark` that overrides the `type` method.

## 📋 ALGORITHM:

1. Define the `Fish` class with a method named `type()` that prints `"fish"`.
2. Define the `Shark` class as a subclass of `Fish`, and override the `type()` method to print `"shark"`.
3. Create an instance of the `Fish` class named `obj_goldfish`.
4. Create an instance of the `Shark` class named `obj_hammerhead`.
5. Use a `for` loop to iterate over both objects.
6. Within the loop, call the `type()` method using the loop variable.
7. Output will demonstrate method overriding: printing `"fish"` and `"shark"` accordingly.

## 💻 PROGRAM:
```python
# Parent class
class Fish:
    def type(self):
        print("fish")

# Child class
class Shark(Fish):
    def type(self):
        print("shark")

# Create objects
obj_goldfish = Fish()
obj_hammerhead = Shark()

# Iterate through objects and call type()
for animal in (obj_goldfish, obj_hammerhead):
    animal.type()
```


## OUTPUT

<img width="472" height="64" alt="Screenshot 2026-05-31 184516" src="https://github.com/user-attachments/assets/1b863cf0-c1df-4e88-bae3-77330480f539" />


## RESULT
By using python the code was executed successfully.
