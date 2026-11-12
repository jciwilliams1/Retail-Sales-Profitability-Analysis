
# 💾 SQL Skills Portfolio: Beginner to Intermediate

**SQL | Snowflake | Data Analysis**

---

## 📌 Project Overview

This portfolio showcases my progression in SQL, from beginner concepts to intermediate techniques, through hands-on exercises completed during SQL training.

Using banking-related datasets, I applied SQL to retrieve, filter, sort, and calculate data while addressing practical business requests.

The exercises demonstrate how my SQL skills developed as I worked with increasingly complex queries.

---

## 🛠️ Tools Used

- **SQL** — Querying and analyzing data
- **Snowflake** — Database platform
- **GitHub** — Organizing and showcasing completed SQL exercises

---

## 📈 SQL Skills Progression

### 🟢 Beginner SQL — Building the Foundation

**Skills Demonstrated:**
- SELECT and FROM
- WHERE and comparison operators
- AND, OR, IN, and NOT IN
- BETWEEN
- ORDER BY
- LIMIT

### 🔵 Intermediate SQL — Expanding My Skills

**Skills Demonstrated:**
- Calculated fields
- Arithmetic operators
- Column aliases using AS
- Filtering with multiple conditions
- Applying calculations to business data

*The SQL techniques listed above reflect the exercises included in this portfolio.*

---

## 💻 SQL Exercises & Examples

The following exercises demonstrate SQL concepts learned during training, progressing from foundational queries to more complex calculations and filtering.

---

### Exercise 1: Approved Loan Portfolio Review

**Skill Level:** Beginner SQL

**Business Request / Exercise:**

The lending department wants to identify the ten highest-value approved loans exceeding $20,000, excluding Mortgage and Auto loans.

**SQL Concepts Demonstrated:**
- SELECT and FROM
- WHERE with multiple conditions
- NOT IN
- ORDER BY DESC
- LIMIT

**What the Query Does:**

Retrieves loan information, applies the requested conditions, and displays the ten highest loan amounts.

**SQL Query:**

[View Completed SQL Query](Beginner_SQL/01_approved_loan_portfolio.sql)

---

### Exercise 2: Loan Amount Range Analysis

**Skill Level:** Beginner SQL

**Business Request / Exercise:**

The lending department wants to review the ten highest-value approved loans between $10,000 and $20,000, excluding Mortgage and Auto loans.

**SQL Concepts Demonstrated:**
- SELECT and FROM
- BETWEEN
- NOT IN
- AND
- ORDER BY DESC
- LIMIT

**What the Query Does:**

Filters approved loans within a specified amount range and sorts the results from highest to lowest.

**SQL Query:**

[View Completed SQL Query](Beginner_SQL/02_loan_amount_range.sql)

---

### Exercise 3: Credit Utilization Analysis

**Skill Level:** Intermediate SQL

**Business Request / Exercise:**

The credit department wants to identify credit card accounts with utilization rates of 35% or less and calculate the available credit for each account.

**SQL Concepts Demonstrated:**
- Calculated fields
- Arithmetic operators
- Column aliases using AS
- WHERE conditions

**What the Query Does:**

Calculates available credit and credit utilization, then filters accounts based on the specified utilization threshold.

**SQL Query:**

[View Completed SQL Query](Intermediate_SQL/03_credit_utilization.sql)

---

### Exercise 4: Mortgage Interest Cost Analysis

**Skill Level:** Intermediate SQL

**Business Request / Exercise:**

The lending department wants to estimate monthly interest costs for Mortgage loans with terms greater than 36 months and interest rates below 5%.

**SQL Concepts Demonstrated:**
- Arithmetic calculations
- Calculated fields
- Column aliases using AS
- Multiple WHERE conditions
- ORDER BY ASC

**What the Query Does:**

Calculates an estimated monthly interest cost using the provided formula and sorts the results from lowest to highest.

**SQL Query:**

[View Completed SQL Query](Intermediate_SQL/04_mortgage_interest.sql)

---

### Exercise 5: Withdrawal & Account Deficit Analysis

**Skill Level:** Intermediate SQL

**Business Request / Exercise:**

The operations department wants to review withdrawal transactions associated with negative account balances during 2023 and identify records meeting the specified deficit conditions.

**SQL Concepts Demonstrated:**
- Calculated fields
- Arithmetic operators
- Multiple WHERE conditions
- BETWEEN for date filtering
- ORDER BY ASC

**What the Query Does:**

Retrieves qualifying withdrawal transactions, calculates the specified deficit value, and sorts the results.

**SQL Query:**

[View Completed SQL Query](Intermediate_SQL/05_withdrawal_deficit.sql)

---

## 🎯 Skills Developed

Through these exercises, I demonstrated the ability to:

- Write SQL queries to retrieve information from database tables.
- Apply filters and conditions to identify specific records.
- Sort and limit query results.
- Create calculated fields using arithmetic operators.
- Apply SQL techniques to banking-related business requests.
- Organize and document completed SQL exercises using GitHub.

---

## 📂 Project Structure

```text
SQL-Skills-Portfolio/
│
├── README.md
│
├── Beginner_SQL/
│   ├── 01_approved_loan_portfolio.sql
│   └── 02_loan_amount_range.sql
│
└── Intermediate_SQL/
    ├── 03_credit_utilization.sql
    ├── 04_mortgage_interest.sql
    └── 05_withdrawal_deficit.sql
```

---

## 📚 Continuing My SQL Development

This portfolio represents my progression through Beginner and Intermediate SQL training.

As I continue developing my analytical skills, I plan to expand this portfolio with additional SQL exercises and techniques.

