# 🚗 Car Rental System – Java OOP Console Project

This is a Java-based console application that demonstrates the core principles of **Object-Oriented Programming (OOP)** through a simple and practical **Car Rental System**. It simulates how a real-world rental service manages customers, car inventory, and rental transactions — all from a command-line interface.

---

## 📌 Features

- 🔁 **Rent a Car** – Users can browse available cars and rent one.
- 🔄 **Return a Car** – Users can return cars, and the system updates availability.
- 👤 **Customer Management** – Add and track customer profiles.
- 🚗 **Car Inventory Management** – Manage car brands, models, and pricing.
- 📊 **Rental History Tracking** – Maintains records of who rented what and for how long.
- 🧑‍💼 **Admin Mode (Concept)** – Can be expanded to include separate admin functions like managing cars, reviewing rentals, and analytics.

---

## 🧱 Tech Stack

- **Language**: Java  
- **IDE**: IntelliJ IDEA / Eclipse / VS Code  
- **Concepts Used**:
  - Classes & Objects
  - Encapsulation
  - Inheritance
  - Polymorphism
  - Modular Code Organization
  - Control Flow, Arrays, and Collections

---

## 📂 Project Structure

| File Name                    | Purpose                                         |
|-----------------------------|-------------------------------------------------|
| `Car.java`                  | Car object with brand, model, price, availability status |
| `Customer.java`             | Customer data class                            |
| `Rental.java`               | Rental logic for assigning and returning cars  |
| `CarRentalSystemTesting.java` | Main class (Console Menu and System Logic)  |

---

## 🛠️ How to Run

```bash
# Compile all Java files
javac *.java

# Run the main class
java CarRentalSystemTesting
