# Banking Management System

A beginner-friendly Banking Management System built using Python and Pandas.

The project simulates basic banking operations such as account creation, deposits, withdrawals, fund transfers, customer services, and loan application and eligibility checking.

## Features

* Create and manage customer accounts
* Account validation and minimum balance constraint
* Deposit and withdrawal operations
* Net banking and fund transfer
* Transaction history
* Customer service for updating phone and email
* Multiple loan types:

  * Home Loan
  * Car Loan
  * Education Loan
  * Personal Loan
* Loan eligibility and approval/rejection based on defined project rules
* Customer and transaction data stored using CSV files

## Tech Stack

* **Language:** Python
* **Library:** Pandas
* **Data Storage:** CSV
* **IDE:** PyCharm

## Project Structure

```text
Banking-Management-System/
│
├── Banking_project.py
├── customers.csv
├── transactions.csv
├── loans.csv
└── README.md
```

## How to Run

1. Clone the repository.
2. Install Pandas:

```bash
pip install pandas
```

3. Run the Python file:

```bash
python Banking_project.py
```

The required CSV files are created automatically when the program runs.

## Note

The loan approval conditions used in this project are simplified rules created for educational purposes and do not represent actual bank lending policies.
