# Personal-Expense-Tracker
Console-based Python expense tracker with category-wise analysis, search, and persistent CSV storage.

A console-based Python application to record, track, and analyze daily personal 
expenses, with persistent storage using CSV files.

## Overview

This project is a menu-driven expense tracker that lets users log expenses by 
category, view spending summaries, search past records, and save/load data 
between sessions — built using core Python concepts without external libraries.

## Features

- **Add Expense** — record date, category, description, and amount
- **View Expenses** — display all logged expenses in a readable format
- **Calculate Total** — sum total spending across all entries
- **Category-wise Breakdown** — view spending grouped by category
- **Search by Category** — filter and display expenses for a specific category
- **Save to CSV** — persist expense records to `expenses.csv`
- **Load from CSV** — restore previously saved expenses on startup
- **Interactive Menu** — simple numbered menu for navigating all features

## Concepts Used

- Variables, Lists, Dictionaries
- Loops and Conditional Statements
- Functions
- File Handling (CSV read/write)
- Exception Handling (invalid input, missing files)

## Tech Stack

- Python 3
- Built-in `csv` and `datetime` modules (no external dependencies)

## How to Run

```bash
python expense_tracker.py
```

Follow the on-screen menu to add, view, search, save, or load expenses.

## Files

| File | Description |
|---|---|
| `Expense_Tracker_Project.ipynb` | Jupyter notebook with full source code and explanations |
| `expenses.csv` | Generated file storing saved expense records |

## Future Scope

- Budget limits with alerts when a category exceeds a set threshold
- Monthly/date-range filtering
- Data visualization (spending trends via Matplotlib)
- Migrate from console app to a simple GUI or web interface

## Author

Tanuja Mane
[LinkedIn](#) · [GitHub](#)
