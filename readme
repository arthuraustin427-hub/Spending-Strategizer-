# Smart Spending Strategizer

A Python budget tracker that organizes your expenses by category
and prints a full spending summary with a health score and tips.

---

## Team

- Austin  — Class Definitions (Cell 2)
- Clancy  — File Reading & Parsing (Cell 3) and Display Functions (Cell 4)

---

## Requirements

- Python 3
- Jupyter Notebook

---

## Files

- spending_strategizer.ipynb — the main notebook with all the code
- expenses.txt               — your expense data file

---

## How to Set Up expenses.txt

Create a file called expenses.txt in the same folder as the notebook.
Each line should follow this format:

    category, description, amount

Example:

    rent, monthly rent, 1200
    food, groceries, 310
    transport, gas, 140
    utilities, electric and wifi, 120
    dining, restaurants, 200
    entertainment, streaming, 90
    shopping, clothes, 150
    savings, emergency fund, 400
    investment, 401k, 170

Rules:
- One expense per line
- Exactly 3 fields separated by commas
- Amount must be a number
- Lines that start with # are treated as comments and ignored
- Blank lines are ignored

---

## How to Run

1. Open spending_strategizer.ipynb in Jupyter Notebook
2. Run Cell 2 — loads the Expense and Budget classes
3. Run Cell 3 — loads the file reading and display functions
4. Run Cell 4 — loads the summary functions
5. Run Cell 5 — runs the program and prints the full output

Important: cells must be run in order every time you open the notebook.
You can do this quickly by clicking Run then Run All Cells.

---

## What the Output Shows

- Monthly income
- Total amount spent
- Amount remaining
- Spending breakdown by category with percentage and bar chart
- Budget health score from 0 to 100
- Tips based on your spending numbers

---

## Error Handling

The program handles the following automatically:

- File not found — prints a message instead of crashing
- Wrong number of fields on a line — skips the line and reports it
- Amount is not a number — skips the line and reports it
- Category name differences — rent, Rent, and RENT all count as the same

---

## Course Concepts Used

- File Reading    — open(), readlines(), try/except
- Classes         — Expense and Budget with methods
- Lists           — Budget.expenses stores all Expense objects
- Dictionaries    — by_category() groups totals by category name
- Functions       — display_summary(), calc_health_score(), display_tips()
