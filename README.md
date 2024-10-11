# Hostel Accommodation System

This is a C++ project that implements a **Hostel Accommodation Management System** using **Object-Oriented Programming (OOP)** principles and **MySQL** for database management. The system allows users to reserve hostel beds, keep track of available beds, and manage payments.

## Features

- **Hostel Management:**
  - Add a hostel with details like name, number of beds, and fees.
  - Reserve beds for students in the hostel.
  - Automatically update the number of available beds.
  
- **Database Integration:**
  - Stores hostel data (name, beds, fees) in a MySQL database.
  - Updates the bed count in real-time as students reserve them.

- **User Interface:**
  - Command-line interface for bed reservation.
  - Error handling for invalid inputs.

## Project Structure

- `Hostel.h`: Defines the `Hostel` class to handle hostel attributes and related functions.
- `main.cpp`: Implements the core functionality, including database interaction and user interaction.
- `Makefile`: Instructions to compile the program.

## Requirements

### Software

- **MySQL**: Install and set up MySQL server.
- **MySQL Connector for C++**: Required to connect and query the MySQL database from C++ code.
- **G++**: For compiling the C++ code.

### Libraries

- MySQL headers: Ensure you have `mysql.h` and `mysqld_error.h` available in your development environment.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/HVAIDH5/Hostel_accomodation.git

