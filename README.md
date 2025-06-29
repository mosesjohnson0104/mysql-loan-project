# 💳 MySQL Loan Management Project

A complete SQL-based mini-project to manage loan applications, approvals, payments, and sales tracking — built using MySQL. Ideal for beginners to practice relational schema design, data querying, and conditional logic in SQL.

---

## 🧾 Project Features

- Customers and loan application tracking
- Approval logic based on income criteria
- Payments recording and overdue detection
- Sales team performance reporting
- Queries using JOINs, CASE, DATEDIFF, and aggregate functions

---

## 🗃️ Database Schema

- `Customers` – Customer details and income info
- `Loan_Applications` – Applied loans with status
- `Loan_Approvals` – Final approved amount and interest rate
- `Payments` – Loan repayments
- `Loan_Sales_Team` – Sales reps handling applications

---

## ⚙️ Functional Highlights

- Approve loans only if requested amount ≤ 80% of income
- Track applications without payments after approval
- Report days since application
- View sales rep-wise loan closures

---

## 📁 Files

| File Name       | Description                                      |
|----------------|--------------------------------------------------|
| `schema.sql`    | All table creation statements                   |
| `insert_data.sql` | Sample data for customers, loans, and sales     |
| `queries.sql`   | All queries (update, view, reports)              |

---

## 🚀 How to Use

1. Import the scripts into MySQL Workbench or any SQL client.
2. Run `schema.sql` to create the structure.
3. Run `insert_data.sql` to populate the tables.
4. Run `queries.sql` to test approval logic, overdue payments, etc.

---

## 🔗 Author

**Moses Johnson**  
📫 [Gmail](mailto:mosesjohnson.nixon@gmail.com) • [LinkedIn](https://www.linkedin.com/in/moses-johnson/) • [GitHub](https://github.com/mosesjohnson0104)

---

## 📌 Tags

`MySQL` • `SQL Practice` • `Loan Approval` • `Relational Schema` • `Data Reporting` • `Beginner Friendly`
