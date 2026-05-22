# 🚗 Car Rental System

Explore the world of car rentals with the **Car Rental System**, a Java-based console application that combines learning and simulation. 🌟

---

## Features

* 🚀 Rent a Car: Experience the ease of renting cars through an interactive console.
* 🔁 Return a Car: Effortlessly return previously rented cars and update availability.
* 👥 Customer Management: Add new customers and maintain customer records.
* 🚗 Car Management: Manage cars, brands, models, and pricing details.
* 📝 Rental History: Keep track of rentals, customers, and rental durations.

---

## Project Structure

* **`Car.java`** - Manages car properties (ID, brand, model, base price per day) and handles availability states (`rent()` / `returnCar()`).
* **`Customer.java`** - Represents the client with a unique sequential ID and their name.
* **`Rental.java`** - Acts as an aggregation layer combining a specific `Car`, `Customer`, and the total rental duration.
* **`CarRentalSystem.java`** - Holds core business logic, arrays/lists of records, and manages the interactive CLI terminal menu.
* **`Main.java`** - The entry point of the application that instantiates the system, injects initial car data, and starts the interface.

---

## Technologies Used

* **Language:** Java (JDK 21 or higher recommended)
* **IDE:** Visual Studio Code (VS Code)
* **Concepts:** Encapsulation, Aggregation, List Collections (`ArrayList`), and Console I/O (`Scanner`).

---

## 🚀 How to Run the Application

### Prerequisites
Make sure you have the Java Development Kit (JDK) installed on your computer.

### Steps
1. Clone or download this repository to your local machine.
2. Open the project folder inside **Visual Studio Code**.
3. Navigate to the `Main.java` file.
4. Click the **Run (▶️)** button at the top-right corner of the editor.
5. Interact with the application using the numeric options in the integrated VS Code terminal!

---

## 📸 Sample Preview
```text
===== Car Rental System =====
1. Rent a Car
2. Return a Car
3. Exit
Enter your choice: 1

== Rent a Car ==
Enter your name: Dewthilini Wanniarachchi

Available Cars:
C001 - Toyota Camry
C002 - Honda Accord
C003 - Mahindra Thar

Enter the car ID you want to rent: C001
Enter the number of days for rental: 2

== Rental Information ==
Customer ID: CUS1
Customer Name: Dewthilini Wanniarachchi
Car: Toyota Camry
Rental Days: 2
Total Price: $120.00

Confirm rental (Y/N): Y

Car rented successfully.
===== Car Rental System =====
1. Rent a Car
2. Return a Car
3. Exit
Enter your choice: 2

== Return a Car ==

Enter the car ID you want to return: C001
Car returned successfully by Dewthilini Wanniarachchi
===== Car Rental System =====
1. Rent a Car
2. Return a Car
3. Exit
Enter your choice: 3

Thank you for using the Car Rental System!

Confirm rental (Y/N): Y
Car rented successfully.
