# Supermarket Management System

## Overview

The Supermarket Management System is a console-based application developed using Java. It is designed to manage basic supermarket operations such as staff management, inventory management, and stock handling.

The project was developed using Object-Oriented Programming (OOP) concepts to organize different operations into separate classes.

## Features

### Staff Management
- Add new staff members
- View staff details
- Remove existing staff members
- Verify staff IDs before accessing staff management

### Inventory Management
- Add new products to the inventory
- View available products and their details
- Store product IDs, names, quantities, and prices

### Stock Management
- Add stock to existing products
- Remove stock from inventory
- Check stock availability before removing items

## Technologies Used

- Java
- Object-Oriented Programming (OOP)
- Arrays
- Scanner Class
- Command-Line Interface (CLI)

## How to Run

1. Install the Java Development Kit (JDK).
2. Download the project files.
3. Open the project folder using a terminal.
4. Compile the Java file:

```bash
javac SupermarketManagementSystem.java
```

5. Run the program:

```bash
java SupermarketManagementSystem
```

## Main Menu

The system provides the following options:

```text
--- Supermarket Management System ---
1. Staff Management
2. Inventory Management
3. Stock In/Out Management
4. Exit
```

## Project Structure

The application consists of the following classes:

- **Staff** – Stores staff information.
- **StaffManager** – Handles staff-related operations.
- **InventoryItem** – Stores product information.
- **InventoryManager** – Manages inventory items.
- **StockManager** – Handles stock additions and removals.
- **SupermarketManagementSystem** – Contains the main method and menu navigation.

## Future Improvements

- Database integration
- Graphical user interface
- Billing system
- Sales reports
- Improved user authentication

## Conclusion

This project demonstrates the practical use of Java and Object-Oriented Programming concepts in developing a basic supermarket management application. It provides a simple way to manage staff, inventory, and stock through a console-based interface.
