# 📈 Stock Portfolio Tracker

A simple Stock Portfolio Tracker developed in **Python** as part of the **CodeAlpha Python Development Internship**.

The program allows users to enter stock names and quantities, calculates the total investment value using predefined stock prices, displays a portfolio summary, and optionally saves the results to a text file.

## 📌 Features

* 📊 Uses predefined stock prices
* 🔤 Allows users to enter stock names
* 🔢 Accepts the quantity of shares
* 💰 Calculates individual investment values
* 📈 Calculates the total portfolio investment
* ⚠️ Validates invalid stock names and quantities
* 💾 Optionally saves the portfolio summary to a `.txt` file
* 💻 Simple console-based interface

## 🛠️ Technologies Used

* **Python 3**
* Dictionaries
* Loops
* Conditional statements
* User input/output
* Basic arithmetic
* File handling
* Exception handling

## ▶️ How to Run

1. Make sure **Python 3** is installed.
2. Clone or download this repository.
3. Open the project folder in a terminal.
4. Run the program:

```bash
python stock_portfolio.py
```

5. Follow the instructions displayed in the console.

## 📊 Available Stocks

The program uses manually defined stock prices, for example:

```python
stock_prices = {
    "AAPL": 180,
    "TSLA": 250,
    "GOOGL": 175,
    "MSFT": 420,
    "AMZN": 190
}
```

These are **hardcoded example prices** and are not live market prices.

## 💰 How It Works

1. The program displays the available stocks and their predefined prices.
2. The user enters a stock symbol.
3. The user enters the quantity of shares.
4. The program calculates the investment value:

```text
Investment = Stock Price × Quantity
```

5. The program displays the complete portfolio summary.
6. The user can optionally save the result to `stock_portfolio.txt`.

## 📂 Project Structure

```text
Stock-Portfolio-Tracker/
│
├── stock_portfolio.py
├── stock_portfolio.txt
└── README.md
```

> `stock_portfolio.txt` is generated automatically when the user chooses to save the results.

## 🎯 Learning Objectives

This project demonstrates the practical use of **Python dictionaries, user input/output, loops, conditional statements, arithmetic operations, exception handling, and file handling**.

## 👨‍💻 Internship

**CodeAlpha – Python Development Internship**

**Task 2: Stock Portfolio Tracker**
