# Bank Account Management System

## Project Overview

The **Bank Account Management System** is a menu-driven Python application designed to perform basic banking operations. It allows users to create accounts, deposit money, withdraw money, check account balances, and view transaction histories.

The program uses JSON file handling to store account information persistently, so the data can be loaded again when the application is restarted.

## Features

* **Create Account:** Create a new account with an account number, account holder name, and initial deposit.
* **Deposit Money:** Add money to an existing account.
* **Withdraw Money:** Withdraw money if sufficient balance is available.
* **Check Balance:** View the account holder's name and current balance.
* **Transaction History:** View account-opening, deposit, and withdrawal records with timestamps.
* **Save Data:** Save account information to a JSON file.
* **Input Validation:** Handle invalid menu choices, invalid amounts, duplicate accounts, and insufficient balances.

## Technologies Used

* **Programming Language:** Python 3
* **Modules:** `json`, `os`, `datetime`
* **Data Storage:** JSON file

## Project Structure

```text
Bank-Account-Management-System/
│
├── bank_account_management.py
├── bank_data.json
└── README.md
```

**Note:** The `bank_data.json` file is created automatically when the program saves account information. It may not exist in the repository before the first run.

## Requirements

* Python 3 installed on your computer.
* A terminal or Python IDE, such as IDLE, VS Code, or PyCharm.

No external Python packages are required.


## Menu Options

```text
===== BANK ACCOUNT MANAGEMENT SYSTEM =====
1. Create Account
2. Deposit Money
3. Withdraw Money
4. Check Balance
5. Transaction History
6. Save Data
7. Exit
Enter your choice:
```

Enter the corresponding number to perform an operation.

## Sample Execution

```text
Enter your choice: 1
Enter account number: 101
Enter account holder name: sukanya
Enter initial deposit: 5000
Account created successfully!

Enter your choice: 2
Enter account number: 101
Enter deposit amount: 500
Money deposited successfully!

Enter your choice: 3
Enter account number: 101
Enter withdrawal amount: 1000
Withdrawal successful!

Enter your choice: 4
Enter account number: 101
Account Holder: sukanya
Current Balance: Rs. 4500.00
```

## Data Storage

Account details and transaction histories are stored in `bank_data.json` in JSON format. The application loads the saved information when it starts and updates the file after account creation, deposits, withdrawals, and explicit save or exit operations.

## Concepts Demonstrated

* Python functions
* Dictionaries and lists
* Conditional statements
* `while` loops
* Exception handling with `try` and `except`
* File handling
* JSON serialization and deserialization
* Date and time formatting

## Future Enhancements

* PIN-based authentication
* Account deletion
* Money transfers between accounts
* Interest calculation
* Monthly account statements
* Improved data validation and security

## Conclusion

This project demonstrates how Python can be used to develop a simple banking application with persistent data storage and transaction tracking. It is suitable for beginners learning Python programming and file handling.

---

**Author:** Your Name

**Language:** Python

**Project Type:** Console-Based Application
