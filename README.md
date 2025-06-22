# Vehicle-Management-using-Inheritance-and-Polymorphism
To demonstrate object-oriented programming concepts like inheritance, method overriding, and encapsulation. Resulted in a functional Java-based program for simulating behavior of different vehicle types.
## 📌 Project Overview
This project is a simple Java-based vehicle management system that demonstrates core Object-Oriented Programming (OOP) concepts such as **inheritance**, **method overriding**, and **polymorphism**. It simulates different types of vehicles (Car and Truck) and their unique behaviors.

---

## 🔧 Technologies Used
- Java  
- Object-Oriented Programming (OOP)  
- Scanner class (for user input)

---

## 🎯 Objective
To create a basic console application where users can input details for different vehicle types, and observe how different classes behave using inheritance and polymorphism.

---

## 📂 Project Structure

---

## 🛠️ Features
- Accepts user input for vehicle details (brand, year, fuel type/load capacity).
- Demonstrates:
  - **Inheritance** between `Vehicle`, `Car`, and `Truck`.
  - **Polymorphism** via method overriding of `startEngine()` in both `Car` and `Truck`.
  - **Encapsulation** of vehicle data.
- Outputs custom behavior based on object type.

---

## 📌 Classes Description

### 1. `vehicle` (Parent Class)
- Attributes: `brand`, `year`
- Method: `startEngine()`

### 2. `Car` (Child Class of `vehicle`)
- Additional Attribute: `fuelType`
- Overrides: `startEngine()`
- New Method: `drive()`

### 3. `truck` (Child Class of `vehicle`)
- Additional Attribute: `loadCapacity`
- Overrides: `startEngine()`
- New Method: `haul()`

---

## ▶️ How to Run
1. Make sure you have **Java installed**.
2. Open your terminal or IDE (like Eclipse or VS Code).
3. Compile the file:  
   `javac vehicles_mainclass.java`
4. Run the program:  
   `java vehicles_mainclass`
5. Follow the console prompts to enter vehicle details.

---

## 📖 Learning Outcome
- Reinforced understanding of Java classes and objects.
- Learned how to use inheritance and method overriding to build flexible, extensible code.
- Practiced reading user input and displaying outputs dynamically.

---

## 🙌 Acknowledgements
Project developed as part of academic self-learning to strengthen Java and OOP fundamentals.

---

## 📄 License
This project is open for learning and educational purposes.
