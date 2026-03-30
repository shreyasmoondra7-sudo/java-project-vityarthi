# 💰 Personal Finance Tracker

A lightweight, command-line Java application designed to help you track personal income and expenses efficiently. Built for simplicity and speed, this tool allows you to manage your finances directly from the terminal with persistent data storage.

![Java](https://img.shields.io/badge/Java-8%2B-orange.svg)
![License](https://img.shields.io/badge/License-MIT-blue.svg)
![Status](https://img.shields.io/badge/Status-Stable-green.svg)

---

## 📖 Table of Contents

- [Features](#-features)
- [Preview](#-preview)
- [Prerequisites](#-prerequisites)
- [Installation & Setup](#-installation--setup)
- [Usage Guide](#-usage-guide)
- [Data Storage](#-data-storage)
- [Project Structure](#-project-structure)
- [Contributing](#-contributing)
- [License](#-license)
- [Author](#-author)

---

## ✨ Features

- **💸 Transaction Management:** Easily add income or expense entries with descriptions.
- **📊 Real-time Balance:** Instantly calculate your current balance (Income - Expenses).
- **📜 History Log:** View a chronological list of all past transactions.
- **💾 Persistent Storage:** Data is saved automatically to a local text file; no database required.
- **✅ Input Validation:** Robust error handling prevents invalid numbers or empty entries.
- **⚡ Lightweight:** No external dependencies or heavy frameworks required.

---

## 🖥️ Preview

Here is what the application looks like in action:

```text
========================================
   Welcome to Personal Finance Tracker  
========================================
1. Add Transaction
2. View Balance
3. View History
4. Exit
----------------------------------------
Enter choice: 1

Enter type (income/expense): income
Enter amount: 5000
Enter description: Monthly Salary
Transaction added successfully!

----------------------------------------
Enter choice: 2
Current Balance: $5000.00
----------------------------------------
