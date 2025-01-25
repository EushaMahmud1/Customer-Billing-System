# Customer Billing System

This project is a simple **Customer Billing System** developed in C. It provides a way to manage customer accounts, including adding, searching, displaying, and deleting records. The system uses file handling to store customer data persistently, making it accessible across multiple sessions.

## Features

- **Add Customer Accounts**: Input customer details and save them to a file.
- **Search Accounts**: Find customer accounts by name or customer number.
- **Display All Accounts**: View the details of all customer records.
- **Delete All Accounts**: Clear all customer data from the system.
- **Persistent Storage**: Customer records are stored in a file for future reference.

## How It Works

1. **Add Accounts**: Enter customer details like name, mobile number, account type, and payment history.
2. **Search**: Search for a customer using either the account number or name.
3. **Display All**: List all customer records along with account details and payment status.
4. **Delete**: Clear all records from the file.

## Technologies Used

- **Programming Language**: C
- **File Handling**: For storing customer data (`file.txt`).
- **CLI Interface**: Command-line interface for interacting with the system.

## How to Compile and Run

1. Open a terminal or command prompt.
2. Navigate to the project directory.
3. Compile the program using a C compiler (e.g., GCC):
   ```bash
   gcc -o CustomerBillingSystem CustomerBillingSystem.c
