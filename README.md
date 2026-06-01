# 1. Python OOP: Abstract Class & Method Example

## 🎯 AIM

To create an **abstract class** named `Shape` with an **abstract method** `calculate_area`, and implement this method in two subclasses: `Rectangle` and `Circle`.


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


## 💻 Program
<img width="582" height="509" alt="Screenshot 2026-06-01 142000" src="https://github.com/user-attachments/assets/c51cdba3-1021-4fe4-a75c-07e15cf9fe1d" />


## Output
<img width="360" height="174" alt="Screenshot 2026-06-01 142014" src="https://github.com/user-attachments/assets/118d7d14-592d-4ed1-9b0a-a436316893d2" />


## Result
The execution of the program was successfully done.


# 2. Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.


## 🧠 ALGORITHM

1. **Define the Class**:
   - Create a class `Rectangle` with two private attributes: `__length` and `__breadth`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__length` and `__breadth`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `Rectangle` class to trigger the constructor.

## 💻 Program
<img width="526" height="268" alt="Screenshot 2026-06-01 142856" src="https://github.com/user-attachments/assets/510e97e0-a41b-40c3-8c62-d5ec1f55417c" />

## Output
<img width="349" height="177" alt="Screenshot 2026-06-01 142901" src="https://github.com/user-attachments/assets/be3b690d-cf86-448f-a28d-d657ef9df963" />


## Result
The execution of the program was successfully done.
