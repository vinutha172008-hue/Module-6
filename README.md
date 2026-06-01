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

# 3. Method Overriding-Fish and Shark Class Inheritance in Python

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
<img width="370" height="335" alt="Screenshot 2026-06-01 143203" src="https://github.com/user-attachments/assets/9c16f231-5758-4a4e-b2e4-1243fe0683a0" />

## OUTPUT
<img width="444" height="193" alt="Screenshot 2026-06-01 143210" src="https://github.com/user-attachments/assets/44632706-7256-4e5f-ab3d-785310623058" />


## RESULT
The execution of the program was successfully done.

# 4. Python OOP: Operator Overloading (Less Than `<`)

## 🎯 AIM

To write a Python program that demonstrates **operator overloading** by overloading the **less than (`<`)** operator using a custom class.

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


## 💻 Program
<img width="503" height="364" alt="Screenshot 2026-06-01 143417" src="https://github.com/user-attachments/assets/b388b942-af3d-41cf-8617-b259eedf48f1" />

## Output
<img width="610" height="187" alt="Screenshot 2026-06-01 143423" src="https://github.com/user-attachments/assets/446d7010-06fe-4634-ac90-29d890c33971" />

## Result
The execution of the program was successfully done.

# 5. Python OOP: Polymorphism with Classes

## 🎯 AIM

To create two specific classes — `Beans` and `Mango`. Then, create a **generic function** that can accept any object and determine its **type** (Fruit or Vegetable) and **color**, using polymorphism.


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

## 💻 Program
<img width="354" height="490" alt="Screenshot 2026-06-01 143647" src="https://github.com/user-attachments/assets/410560be-acca-4b0f-8f67-1979993d74f3" />

## Output
<img width="371" height="204" alt="Screenshot 2026-06-01 143653" src="https://github.com/user-attachments/assets/da37e153-7b1e-4c19-9c72-381ae2e3278f" />

## Result
The execution of the program was successfully done.
