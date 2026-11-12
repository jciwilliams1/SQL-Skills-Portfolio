
# 💾 Banking Operations Analysis

<p align="center">
  <img width="600" alt="Banking Operations Analysis" src="https://github.com/user-attachments/assets/aed7a8be-95c0-4185-9293-d723cbe23461" />
</p>

**SQL | Snowflake | Data Analysis**

---

## 📌 Project Overview

This project demonstrates my SQL skills through practical banking-related scenarios involving lending, credit utilization, interest calculations, and transaction analysis.

Using SQL in Snowflake, I developed queries to retrieve, filter, sort, and calculate data based on specific business requirements.

The queries highlight my progression from foundational SQL concepts to intermediate techniques.

*These analyses are based on simulated business requests.*

---

## 🛠️ Tools Used

- **SQL** — Querying and analyzing data
- **Snowflake** — Database platform
- **GitHub** — Organizing and showcasing completed SQL queries

---

## 📈 SQL Skills & Techniques

### 🟢 Beginner SQL — Building the Foundation

**Skills Demonstrated:**
- SELECT and FROM
- WHERE and comparison operators
- AND, IN, and NOT IN
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

## 💻 Project Work & Examples

The following five SQL queries demonstrate my progression from foundational querying techniques to intermediate calculations and data analysis.

---

### 1. Approved Loan Portfolio Review

**Skill Level:** Beginner SQL

**Business Request**

The AVP of Lending wants to review the ten highest-value approved Mortgage and Auto loans exceeding $20,000. The report should include the loan ID, amount, type, and approval status.

**SQL Concepts Demonstrated**
- SELECT and FROM
- WHERE and comparison operators
- AND
- IN
- ORDER BY DESC
- LIMIT

**What the Query Does**

Retrieves approved Mortgage and Auto loans exceeding $20,000 and displays the ten highest loan amounts.

[View Completed SQL Query](Beginner_SQL/01_approved_loan_portfolio.sql)

---

### 2. Loan Amount Range Review

**Skill Level:** Beginner SQL

**Business Request**

The AVP of Lending wants to review the ten highest-value approved loans between $10,000 and $20,000, excluding Mortgage and Auto loans. The report should include the loan ID, amount, type, and approval status.

**SQL Concepts Demonstrated**
- SELECT and FROM
- WHERE
- BETWEEN
- NOT IN
- AND
- ORDER BY DESC
- LIMIT

**What the Query Does**

Filters approved loans within the specified amount range, excludes Mortgage and Auto loans, and displays the ten highest loan amounts.

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

[View Completed SQL Query](Intermediate_SQL/03_credit_utilization.sql)

---

### 4. Mortgage Interest Cost Analysis

**Skill Level:** Intermediate SQL

**Business Request**

A regional branch manager wants to estimate monthly interest costs for Mortgage loans with terms exceeding 36 months and interest rates below 5%.

**SQL Concepts Demonstrated**
- Arithmetic calculations
- Calculated fields
- Column aliases using AS
- Multiple WHERE conditions

**What the Query Does**

Calculates an estimated monthly interest cost using the exercise's specified formula for qualifying Mortgage loans.

[View Completed SQL Query](Intermediate_SQL/04_mortgage_interest.sql)

---

### 5. Withdrawal & Account Deficit Analysis

**Skill Level:** Intermediate SQL

**Business Request**

The Customer Success department wants to review withdrawal transactions during 2023 involving negative account balances and identify transactions meeting the specified deficit conditions.

**SQL Concepts Demonstrated**
- Calculated fields
- Arithmetic operators
- Multiple WHERE conditions
- BETWEEN for date filtering
- ORDER BY

**What the Query Does**

Retrieves qualifying withdrawal transactions, applies the specified deficit calculation and conditions, and organizes the results for review.

[View Completed SQL Query](Intermediate_SQL/05_withdrawal_deficit.sql)

---

## 🎯 Key Takeaways

This project demonstrates my ability to apply SQL techniques to practical banking-related scenarios, from retrieving and filtering data to performing calculations and analyzing financial information.

Through these queries, I strengthened my ability to interpret business requests, translate requirements into SQL, and organize results for analysis.
