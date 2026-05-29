# # 🐍 Python OOP: Polymorphism with Classes

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
Class Beans
class Beans: def type(self): print("Vegetable")

def color(self):
    print("Green")
Class Mango
class Mango: def type(self): print("Fruit")

def color(self):
    print("Yellow")
Generic function
def func(obj): obj.type() obj.color()

Create objects
b = Beans() m = Mango()

Call function with different objects
func(b) func(m)
## Output
<img width="563" height="376" alt="image" src="https://github.com/user-attachments/assets/bd16ddd1-3001-45c1-a631-d47e860a3e03" />

## Result
Thus, the Python program successfully demonstrates polymorphism, where a single function func() works with different object types (Beans and Mango) to produce appropriate outputs.
