# Rental System App

This is a simple command-line Car Rental System built in Java using object-oriented programming.

## Project Structure

```
Rental System App/
+-- .gitignore
+-- LICENSE
+-- README.md
+-- RentalSystemApp.java
```

## Description

The application allows users to rent and return cars using an in-memory data model. It uses basic Java classes and collections to track available vehicles, customers, and rental records.

## Features

- Display available cars
- Rent a car for a specified number of days
- Return a rented car
- View rental summary for the current transaction

## File Details

- `RentalSystemApp.java` � contains all classes and application logic in a single Java source file.

## How to Run

1. Open a terminal and navigate to the project folder:

   ```bash
   cd "c:\Users\Aditya\OneDrive\Desktop\Rewntal Car System"
   ```

2. Compile the Java source file:

   ```bash
   javac RentalSystemApp.java
   ```

3. Run the application:

   ```bash
   java RentalSystemApp
   ```

## Terminal Example

Example session when renting and returning a car:

```
+--------------------------------------+
|          Car Rental System          |
+--------------------------------------+
| 1. Rent a Car                       |
| 2. Return a Car                     |
| 3. Exit                             |
+--------------------------------------+
Enter your choice: 1

== Rent a Car ==

Enter your name: aditya

Available Cars:
C001 - Toyota Camry
C002 - Honda Accord
C003 - Mahindra Thar

Enter the car ID you want to rent: C002
Enter the number of days for rental: 2

Confirm rental (Y/N): Y

+--------------------------------------+
|          Rental Summary             |
+--------------------------------------+
| Customer ID: CUS1                   |
| Customer Name: aditya               |
| Car: Honda Accord                   |
| Rental Days: 2                      |
| Total Price: $140.00                |
+--------------------------------------+
Car rented successfully.

+--------------------------------------+
|          Car Rental System          |
+--------------------------------------+
| 1. Rent a Car                       |
| 2. Return a Car                     |
| 3. Exit                             |
+--------------------------------------+
Enter your choice: 2

== Return a Car ==

Enter the car ID you want to return: C002
Car returned successfully by aditya

+--------------------------------------+
|          Car Rental System          |
+--------------------------------------+
| 1. Rent a Car                       |
| 2. Return a Car                     |
| 3. Exit                             |
+--------------------------------------+
Enter your choice: 3

Thank you for using the Car Rental System!
```

## Requirements

- Java JDK 8 or higher

## Possible Improvements

- Persist rental data to a file or database
- Add customer lookup by ID or name
- Add pricing rules and discounts
- Build a graphical user interface (GUI)
