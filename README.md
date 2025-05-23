# 🏦 Bank Management System in C++

A simple console-based Bank Management System built in C++ using Object-Oriented Programming principles like **encapsulation** and **modular file structure**. It supports account creation, deletion, modification, and basic transactions.

---

## 📁 Project Structure

BankSystem/
├── Account.h # Account class declaration
├── Account.cpp # Account class definition
├── BankOperations.h # Banking operations declarations
├── BankOperations.cpp # Banking operations definitions
├── main.cpp # Main interface logic
└── .vscode/
├── tasks.json # Build task for VS Code


---

## ✅ Features

- Create new accounts
- Display account details
- Deposit and withdraw funds
- Modify account details
- Delete accounts
- View all existing accounts

---

## 🧠 Concepts Used

- Encapsulation (private members with public methods)
- File handling with `fstream` in binary mode
- Separation of interface (`.h`) and implementation (`.cpp`)
- Menu-driven terminal interface
- Persistent data storage via `accounts.dat`

---

## 🛠 How to Run

### 🔸 Requirements

- C++ Compiler (e.g., MinGW or g++)
- [Visual Studio Code](https://code.visualstudio.com/)
- C++ Extension: `ms-vscode.cpptools`

### 🔸 Build & Run in VS Code

1. Open project folder in VS Code.
2. Press `Ctrl + Shift + B` to build (via `.vscode/tasks.json`)
3. Press `F5` to run/debug (via `.vscode/launch.json`)

### 🔸 Build from Terminal (Manual)

```bash
g++ main.cpp Account.cpp BankOperations.cpp -o BankApp
./BankApp         # On Linux/Mac
BankApp.exe       # On Windows

#FEAUTURE
1. Create Account
2. Deposit Money
3. Withdraw Money
4. Check Balance
5. Display All Accounts
6. Close Account
7. Modify Account
8. Exit
