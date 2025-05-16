# Restaurant Management System

A comprehensive Java-based restaurant management system developed by Phạm Lê Ngọc Sơn.

## Project Overview

This Restaurant Management System provides a complete solution for managing restaurant operations including order processing, menu management, employee management, and sales reporting. The system features both a command-line interface (CLI) and a graphical user interface (GUI) for flexibility in different environments.

## Project Structure

### Core Java Files:
- **RMS.java** - Main entry point for command-line interface
- **RMS_GUI.java** - Main entry point for graphical user interface
- **Controller.java** - Core business logic for CLI version
- **Controller_GUI.java** - Core business logic for GUI version
- **UserInterface.java** - Command-line interface implementation
- **UserInterface_GUI.java** - Graphical user interface implementation
- **Database.java** - Data handling and persistence

### Data Models:
- **Staff.java** - Base employee data model
- **Employee.java** - Regular employee implementation
- **Manager.java** - Manager with extended permissions
- **MenuItem.java** - Restaurant menu item representation
- **Order.java** - Customer order information
- **OrderDetail.java** - Detailed order item information

### Data Storage:
- **dataFiles/** - Directory containing all persistent data
  - Text files for staff, menu items, and reports
  - Reports are generated in this directory

### Image Resources:
- **images/** - Contains images used in the GUI
- **demo_images/** - Screenshots and demonstration images

## Features

### User Authentication
- Separate login for employees and managers
- Password protection
- Clock-in and clock-out functionality

### Menu Management
- Add, edit, and delete menu items
- Categorize items (Main, Drink, Alcohol, Dessert)
- Set prices and item details

### Order Processing
- Create and manage customer orders
- Add and remove items from orders
- Process payments
- Cancel or close orders

### Employee Management
- Add, edit, and delete staff records
- Track working hours
- Manage staff permissions

### Reporting
- Generate sales reports
- Payment and wage calculation
- Daily financial summaries

## How to Use

### Starting the Application
- **Command Line Interface**: Run `java RMS`
- **Graphical Interface**: Run `java RMS_GUI` or execute the JAR file `RMS_GUI.jar`

### Login
1. Launch the application
2. Enter your staff ID and password
3. Select whether you're a manager (if applicable)
4. Click Login

### Menu Management (Managers Only)
1. Click "Manage menu items"
2. Add new items with the "Add" button
3. Edit existing items with the "Edit" button
4. Remove items with the "Delete" button

### Order Management
1. Click "Order management"
2. Create a new order with the "New Order" button
3. Add items by selecting from the menu and entering quantity
4. Remove items using the "Delete Item" button
5. Close the order when complete
6. Cancel the order if needed

### Employee Management (Managers Only)
1. Click "Manage employees"
2. Add new staff with the "Add Staff" button
3. Edit staff information with the "Edit Staff" button
4. Remove staff with the "Delete Staff" button

### Viewing Reports
1. Click "Show total sales" for sales reports
2. Click "Show payments" for payment information

### Clocking Out
1. Click the "Clock Out" button in the information panel
2. Managers can clock out all staff at the end of the day

## System Requirements
- Java Runtime Environment (JRE) 8 or higher
- Minimum screen resolution: 800x600
- Operating Systems: Windows, macOS, Linux

## Credits
Developed by Phạm Lê Ngọc Sơn