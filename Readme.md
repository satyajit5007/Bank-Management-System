# 🏦 Bank Management System in C++

## 📌 Overview
This **Bank Management System** is a simple console-based C++ project that allows users to create, modify, and manage bank accounts.  
The program stores account information in a binary file (`account.dat`) for persistent storage.

## ✨ Features
- Create a new bank account
- Deposit money
- Withdraw money
- Check account balance
- View list of all account holders
- Modify account details
- Delete an account
- Data is stored persistently in a binary file

## 🛠️ Technologies Used
- **C++** (Object-Oriented Programming)
- **File Handling** (Binary mode)
- **Standard Template Library (STL)**
- **Console-based UI**

## 📂 File Structure
```

📁 BankManagementSystem
├── main.cpp          # Main source code
├── account.dat       # Binary data file (created at runtime)
├── README.md         # Project documentation

````

## 🚀 How to Run
### 1️⃣ Clone the repository
```bash
git clone https://github.com/satyajit5007/bank-management-system.git
cd bank-management-system
````

### 2️⃣ Compile the program

```bash
g++ main.cpp -o bank
```

### 3️⃣ Run the program

```bash
./bank
```

## 📋 Menu Options

| Option | Description             |
| ------ | ----------------------- |
| 1      | Create New Account      |
| 2      | Deposit Amount          |
| 3      | Withdraw Amount         |
| 4      | Balance Enquiry         |
| 5      | All Account Holder List |
| 6      | Close an Account        |
| 7      | Modify an Account       |
| 8      | Exit                    |

## 💾 Data Storage

* Accounts are stored in `account.dat` in binary format.
* When an account is created, modified, or deleted, the changes are reflected in this file.

## 📷 Example Screenshot

```
======================
BANK MANAGEMENT SYSTEM
======================
    ::MAIN MENU::

1. NEW ACCOUNT
2. DEPOSIT AMOUNT
3. WITHDRAW AMOUNT
4. BALANCE ENQUIRY
5. ALL ACCOUNT HOLDER LIST
6. CLOSE AN ACCOUNT
7. MODIFY AN ACCOUNT
8. EXIT
```