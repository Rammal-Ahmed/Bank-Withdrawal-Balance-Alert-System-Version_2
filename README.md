# BANK WITHDRAWAL & BALANCE ALERT SYSTEM

**Version 2 | Python Console Application**

A beginner-friendly Python project that simulates a basic bank withdrawal process. It checks withdrawal requests, calculates the remaining account balance, and displays alerts when the balance reaches zero or falls below a predefined limit.

---

## Project Overview

The Bank Withdrawal & Balance Alert System is a simple console-based application designed to demonstrate basic banking transaction logic using Python.

The program accepts the user's current account balance and requested withdrawal amount. It then checks whether the withdrawal is valid, verifies sufficient funds, calculates the remaining balance, and displays an appropriate transaction message or balance warning.

## Key Features

- **User Input:** Accepts account balance and withdrawal amount.
- **Invalid Amount Validation:** Rejects withdrawal amounts equal to or below zero.
- **Insufficient Balance Check:** Prevents withdrawals that exceed the available balance.
- **Balance Calculation:** Calculates and displays the remaining balance.
- **Zero Balance Alert:** Displays a warning when the account balance becomes zero.
- **Low Balance Alert:** Notifies the user when the remaining balance reaches the predefined limit.
- **Formatted Output:** Displays transaction messages and amounts in a clean console layout.

## Transaction Rules

| Condition | System Response |
|---|---|
| Withdrawal amount ≤ 0 | Invalid amount message |
| Withdrawal amount > Account balance | Insufficient balance message |
| Remaining balance = 0 | Zero balance warning |
| Remaining balance ≤ Rs. 1,358 | Low balance warning |
| Remaining balance > Rs. 1,358 | Transaction successful |

## Technologies Used

- Python 3
- Conditional Statements (`if`, `elif`, `else`)
- User Input (`input()`)
- Variables and Constants
- Arithmetic Operators
- String Formatting (`format()`)
- Output Formatting (`center()`)

## How to Run

1. Install Python 3 on your computer.
2. Download or clone this repository.
3. Open the project folder in Visual Studio Code.
4. Open the terminal.
5. Run the following command:

```bash
python main.py
```

6. Enter your account balance and withdrawal amount when prompted.

## Sample Output

```text
Enter your account balance (Rs.): 5000
Enter the amount to withdraw (Rs.): 4000

You have withdrawn Rs. 4000.0
Remaining Balance: Rs. 1000.00

Transaction Successful. Thank you!
Warning: Low Balance.

========================================
     SEE YOU IN THE NEXT REPOSITORIES..!
========================================
```

## Learning Objectives

This project demonstrates how to:

- Take numerical input from users.
- Apply conditional logic to validate transactions.
- Perform basic arithmetic calculations.
- Compare values using relational operators.
- Use constants to maintain fixed business rules.
- Display formatted financial information.
- Build a simple real-world-inspired Python application.

## Project Purpose

This project was developed as part of Python programming practice to strengthen fundamental programming concepts through a practical banking scenario.

**Note:** This is an educational console application. It does not connect to real bank accounts or process actual financial transactions.

---

## Author

**Rammal Ahmed**

AI & Data Science Enthusiast | Microsoft Dynamics 365 CRM Developer | Power Platform | UI/UX Designer | Graphic Designer & Illustrator

[LinkedIn] www.linkedin.com/in/rammal-ahmed-58184b325 · [GitHub] https://github.com/Rammal-Ahmed

---

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

**Project Status:** Completed

**Developed as part of Python Programming Practice.**
