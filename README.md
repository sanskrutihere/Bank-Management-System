# Bank Account Management System

This project is a **Banking Management System** built using **Object-Oriented Programming (OOP) principles in C++**. It demonstrates the functionality of an internet banking system, allowing users to perform essential banking operations such as account creation, deposits, withdrawals, balance inquiry, and loan approval.

---

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Classes](#classes)
- [Contribution](#contribution)
---

## Introduction
The **Bank Account Management System** is a C++ project that simulates a basic online banking environment. The system allows users to create accounts, make deposits, withdraw funds, check account balances, and calculate interest on their accounts. The system also includes a loan approval system based on the user's credit score and the requested loan amount.

This project is ideal for beginners learning object-oriented programming in C++ as it covers many essential OOP concepts like **classes**, **constructors**, **destructors**, **encapsulation**, and **modularity**.

---

## Features
- **Account Creation**: Create a bank account with a set balance and interest rate.
- **Deposits**: Add funds to your bank account.
- **Withdrawals**: Withdraw money from your bank account, ensuring a minimum balance is maintained.
- **Interest Calculation**: Calculate interest on the account balance for a given time.
- **Loan Approval System**: Check loan eligibility based on credit score and requested loan amount.
- **Interactive Interface**: Simple CLI-based interaction that prompts users to input data for transactions.

---

## Installation
To run this project locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/bank-management-system.git
    ```
2. **Navigate to the project directory**:
    ```bash
    cd bank-management-system
    ```
3. **Compile the C++ program**:
    ```bash
    g++ -o bank_management_system main.cpp
    ```
4. **Run the program**:
    ```bash
    ./bank_management_system
    ```

---

## Usage

### Main Menu
When you run the project, you'll have the option to:
- Open a new account.
- Deposit money.
- Withdraw money.
- Check balance.
- Calculate interest.
- Apply for a loan.

### Example
```bash
Successfully opened your new account!
Enter the amount you want to deposit in your account: 1000
Successfully deposited the amount mentioned!
Enter the amount you want to withdraw from your account: 500
Successfully withdrawn the amount mentioned!
```
## Classes

### Bank Class
- **balance**: Stores the current account balance.
- **rate**: Stores the interest rate for the account.

**Methods**:
- `deposit()`: Deposits a specified amount into the account.
- `withdraw()`: Withdraws a specified amount, ensuring the minimum balance is maintained.
- `calcinterest(time)`: Calculates interest based on the time period provided.
- `getbalance()`: Returns the current account balance.

### Loan Class
- `approval()`: Determines loan approval based on the credit score and the requested loan amount.

## Contributors
- <a href="https://github.com/sanskrutihere/">Sanskruti B.</a>
- <a href="">Avantika M.</a>
