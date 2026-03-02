# 📉 Personal Expense Tracker (Terminal-Based)

A robust Python application designed to automate personal finance tracking through **Object-Oriented Programming (OOP)** and **Data Persistence**.

---

## 🚀 Overview
This project solves the problem of manual budget tracking by providing a streamlined terminal interface. It calculates remaining daily allowances based on the current month's calendar, ensuring users stay within their financial goals.

## 🛠️ Technical Features
* **Modular Architecture:** Utilized a dedicated `Expense` class to manage data attributes (Name, Category, Amount).
* **Smart Budgeting Logic:** Integrated the `calendar` and `datetime` libraries to dynamically calculate "Remaining Days" in a month for accurate daily budget forecasting.
* **Data Persistence:** Implemented CSV File I/O to ensure user data is stored locally and persists across multiple sessions.
* **User Experience (UX):** Built-in input validation loops to categorize expenses (Food, Home, Work, Fun, Misc) and prevent data entry errors.

## 🧰 Tech Stack
* **Language:** Python 3.10+
* **Key Modules:** `csv`, `datetime`, `calendar`, `typing`

## 📊 Project Structure

```text
.
├── main.py             # Entry point of the application
├── expense.py          # Expense class definition
├── expenses.csv        # Persistent data storage
└── README.md           # Project documentation
