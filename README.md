# 💾 Banking Operations Analysis

<p align="center">
  <img width="600" alt="Banking Operations Analysis" src="https://github.com/user-attachments/assets/aed7a8be-95c0-4185-9293-d723cbe23461" />
</p>

**SQL | Snowflake | Data Analysis**

---

## 📌 Project Overview

This project demonstrates my SQL skills through practical banking-related scenarios involving lending, credit utilization, interest calculations, and transaction analysis.

Using SQL in Snowflake, I developed queries to retrieve, filter, sort, and calculate data based on specific business requirements.

The queries highlights my progression from foundational SQL concepts to intermediate techniques.

*These analyses are based on simulated business requests designed to demonstrate practical SQL and data analysis skills.*

---

## 🛠️ Tools Used

- **SQL** — Querying and analyzing data
- **Snowflake** — Database platform
- **GitHub** — Organizing and showcasing SQL queries

---
<!-- THIS IS A COMMENT: List the skills demonstrated in the repository. That way, hiring managers can click the SQL files and verify them. -->

## 📈 SQL Skills Progression

### 🟢 Beginner SQL — Building the Foundation

**Skills Demonstrated:**
- SELECT and FROM
- WHERE and comparison operators
- AND, OR, IN, and NOT IN
- BETWEEN
- ORDER BY
- LIMIT

### 🔵 Intermediate SQL — Expanding Analytical Skills

**Skills Demonstrated:**
- Calculated fields and arithmetic operators
- Column aliases using AS
- Filtering with multiple conditions
- Applying calculations to financial data
- Combining SQL techniques to address business requests

---

## 💻 SQL Query Examples

The following SQL queries demonstrate my progression from foundational querying techniques to intermediate calculations and data analysis.

---

### 1. Approved Loan Portfolio Review

**Skill Level:** Beginner SQL

**Business Request**

The AVP of Lending wants to review the ten highest-value approved Mortgage and Auto loans exceeding $20,000. The report should include the loan ID, amount, type, and approval status.

**SQL Concepts Demonstrated**
- SELECT and FROM
- WHERE and comparison operators
- AND / OR
- ORDER BY DESC
- LIMIT

**What the Query Does**

Retrieves approved Mortgage and Auto loans exceeding $20,000 and displays the ten highest loan amounts.

**SQL Query**

[View Completed SQL Query](Beginner_SQL/01_approved_loan_portfolio.sql)

---

### 2. Personal Loan Amount Review

**Skill Level:** Beginner SQL

**Business Request**

The AVP of Lending wants to review the ten highest-value approved Personal Loans between $10,000 and $20,000. The report should include the loan ID, amount, type, and approval status.

**SQL Concepts Demonstrated**
- SELECT and FROM
- WHERE
- BETWEEN
- AND
- ORDER BY DESC
- LIMIT

**What the Query Does**

Filters approved Personal Loans within the specified amount range and displays the ten highest loan amounts.

**SQL Query**

[View Completed SQL Query](Beginner_SQL/02_personal_loan_review.sql)

---

### 3. Credit Utilization & Available Credit

**Skill Level:** Intermediate SQL

**Business Request**

The Finance department is preparing for an upcoming stress test and wants to review customers' available credit and credit card utilization rates. Only accounts with utilization rates of 35% or less should be included.

**SQL Concepts Demonstrated**
- Calculated fields
- Arithmetic operators
- Column aliases using AS
- WHERE conditions

**What the Query Does**

Calculates available credit and credit utilization rates, then filters accounts based on the specified utilization threshold.

**SQL Query**

[View Completed SQL Query](Intermediate_SQL/03_credit_utilization.sql)

---

### 4. Mortgage Interest Cost Analysis

**Skill Level:** Intermediate SQL

**Business Request**

A regional branch manager wants to evaluate the estimated monthly interest cost for Mortgage loans with terms exceeding 36 months and moderate interest rates.

**SQL Concepts Demonstrated**
- Arithmetic calculations
- Calculated fields
- Column aliases using AS
- Multiple WHERE conditions
- ORDER BY

**What the Query Does**

Calculates an estimated monthly interest amount using the exercise's specified formula and organizes the results for review.

**SQL Query**

[View Completed SQL Query](Intermediate_SQL/04_mortgage_interest.sql)

---

### 5. Withdrawal & Account Deficit Analysis

**Skill Level:** Intermediate SQL

**Business Request**

The Customer Success department wants to examine withdrawal transactions associated with negative account balances and identify transactions meeting specified deficit conditions.

**SQL Concepts Demonstrated**
- Calculated fields
- Arithmetic operators
- Multiple WHERE conditions
- Filtering transaction records
- ORDER BY

**What the Query Does**

Retrieves qualifying withdrawal transactions, applies the specified calculations and conditions, and organizes the results for review.

**SQL Query**

[View Completed SQL Query](Intermediate_SQL/05_withdrawal_deficit.sql)

---

## 🎯 Technical Skills Demonstrated

Through these SQL analyses, I demonstrated the ability to:

- Retrieve, filter, and organize data using SQL.
- Apply multiple conditions to identify specific records.
- Sort and limit query results.
- Perform calculations and create meaningful column aliases.
- Translate simulated banking business requests into SQL querie.

---

## 📂 Project Structure

    Banking-Operations-Analysis/
    |
    |-- README.md
    |
    |-- Beginner_SQL/
    |   |-- 01_approved_loan_portfolio.sql
    |   |-- 02_personal_loan_review.sql
    |
    |-- Intermediate_SQL/
        |-- 03_credit_utilization.sql
        |-- 04_mortgage_interest.sql
        |-- 05_withdrawal_deficit.sql

<!-- THIS IS A COMMENT: Make sure the actual repository folders and SQL filenames match the links in the README. -->
