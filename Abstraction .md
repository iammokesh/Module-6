# 🐍 Python OOP: Abstract Class & Method Example

## 🎯 AIM

To create an **abstract class** named `Shape` with an **abstract method** `calculate_area`, and implement this method in two subclasses: `Rectangle` and `Circle`.

---

## 🧠 ALGORITHM

1. **Import ABC module**:
   - Use `from abc import ABC, abstractmethod` to define abstract classes and methods.

2. **Create Abstract Class `Shape`**:
   - Define an abstract method `calculate_area()` with `@abstractmethod`.

3. **Create Subclass `Rectangle`**:
   - Set default values for `length` and `breadth`.
   - Override `calculate_area()` to compute the rectangle area.

4. **Create Subclass `Circle`**:
   - Set default value for `radius`.
   - Override `calculate_area()` to compute the circle area.

5. **Create Objects & Call Methods**:
   - Instantiate `Rectangle` and `Circle`.
   - Call their `calculate_area()` methods.

---

## 💻 Program
```python
from abc import ABC, abstractmethod

# Abstract class
class Shape(ABC):

    @abstractmethod
    def calculate_area(self):
        pass

# Rectangle class
class Rectangle(Shape):
    def __init__(self, length=10, breadth=5):
        self.length = length
        self.breadth = breadth

    def calculate_area(self):
        return self.length * self.breadth

# Circle class
class Circle(Shape):
    def __init__(self, radius=7):
        self.radius = radius

    def calculate_area(self):
        return 3.14 * self.radius * self.radius

# Create objects
rectangle = Rectangle()
circle = Circle()

# Display areas
print("Area of Rectangle:", rectangle.calculate_area())
print("Area of Circle:", circle.calculate_area())
```


## Output
<img width="574" height="54" alt="Screenshot 2026-05-31 184112" src="https://github.com/user-attachments/assets/0330e9ef-aa74-48af-8f8f-e544d7461e95" />

## Result
By using python the code was executed successfully.
