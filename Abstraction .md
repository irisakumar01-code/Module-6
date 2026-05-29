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
from abc import ABC, abstractmethod import math

Abstract class
class Shape(ABC):

@abstractmethod
def calculate_area(self):
    pass
Subclass Rectangle
class Rectangle(Shape):

def __init__(self, length=5, breadth=3):
    self.length = length
    self.breadth = breadth

def calculate_area(self):
    area = self.length * self.breadth
    print("Area of Rectangle:", area)
Subclass Circle
class Circle(Shape):

def __init__(self, radius=4):
    self.radius = radius

def calculate_area(self):
    area = math.pi * self.radius * self.radius
    print("Area of Circle:", area)
Create objects
r = Rectangle() c = Circle()

Call methods
r.calculate_area() c.calculate_area()
## Output
<img width="737" height="261" alt="image" src="https://github.com/user-attachments/assets/89ad21d5-c207-4a4c-8e16-6a71efaa06b2" />

## Result
Thus, the Python program successfully demonstrates the use of an abstract class and abstract method, where subclasses Rectangle and Circle implement the calculate_area() method.
