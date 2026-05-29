# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.

---

## 🧠 ALGORITHM

1. **Define the Class**:
   - Create a class `Rectangle` with two private attributes: `__length` and `__breadth`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__length` and `__breadth`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `Rectangle` class to trigger the constructor.

---

## 💻 Program
Class with encapsulation
class Rectangle:

def __init__(self, length, breadth):
    # Private members
    self.__length = length
    self.__breadth = breadth

def display(self):
    # Accessing private members inside the class
    print("Length:", self.__length)
    print("Breadth:", self.__breadth)
Create object
obj = Rectangle(10, 5)

Call method
obj.display()
## Output
<img width="551" height="279" alt="image" src="https://github.com/user-attachments/assets/0923afd0-0423-4720-81ef-62a0ec68349b" />

## Result
Thus, the Python program successfully demonstrates encapsulation by using private member variables __length and __breadth, which are accessed only within the class.
