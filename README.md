# Python Bank Account Management System  

## Objective  
The objective of this project is to develop a Bank Account Management System in Python that simulates essential banking operations. The system will allow users to create and manage accounts, perform financial transactions like deposits, withdrawals, and transfers, and retrieve account details. It will incorporate key Python concepts such as variables, data structures (lists, dictionaries), functions, file handling for saving and retrieving data, and modular code structure using functions. The program will simulate the core functionality of a banking system, ensuring users can interact with their accounts in a secure and organized way, while preserving data between sessions using file storage.

## Features  

### 1. Account Management  
- Create new bank accounts with the following attributes:  
  - Account holder's name  
  - Account number (Auto-Generated)  
  - Account type (e.g., savings or current)  
  - Initial balance  
- Retrieve account details, including:  
  - Account holder's name  
  - Account number  
  - Account type  
  - Current balance  

### 2. Transactions  
- **Deposit:** Add money to an account.  
- **Withdrawal:** Withdraw money, ensuring the withdrawal does not exceed the current balance.  
- **Transfer:** Transfer funds between two accounts with proper validation.  
- Transactions automatically update the account balances.  

### 3. File Handling  
- Persistent storage of account details and transaction history using the `pickle` library.  
- Load account data at program startup and save updates on termination.  
- Append new transactions to existing records without overwriting previous data.  

### 4. Reports  
- View transaction history for any account, displaying:  
  - Date & Time 
  - Type of transaction (deposit, withdrawal, transfer)  
  - Amount  
  - Target account (if applicable)  
- Generate summary statistics for each account, including:  
  - Total deposits  
  - Total withdrawals  
  - Average transaction amounts (using NumPy functions)  

### 5. User Interaction  
- An interactive menu for the following operations:  
  - Open a new account  
  - View account details  
  - Perform transactions (deposit, withdraw, transfer)  
  - View transaction history  
  - Exit the program  
- Smooth navigation using conditional statements and loops.  

### 6. Error Handling  
- Input validation to ensure:  
  - Positive amounts for deposits and withdrawals.  
  - Adequate balance before withdrawal or transfer.  
- Prevent invalid operations like transferring funds between non-existent accounts.  

### 7. Bonus Features (Optional)  
- Login functionality for multiple users with Account Number and Password.  
- Advanced Python features like lambda functions for quick calculations.

---

## Installation  

### Prerequisites  
- Python 3.8 or later  
- Required libraries:  
  - NumPy  
  - Pickle (built-in module)  

## Usage  

The program provides an interactive menu to perform the following operations:  
1. Open a new account  
2. View account details  
3. Perform transactions
   1. Withdraw 
   2. Deposit
   3. Transfer
4. View transaction history  
5. Exit 
