# Database Management System — SQL Lab

> A practical SQL and PL/SQL repository covering relational database operations, querying, joins, constraints, and procedural database programming.

<p align="center">
  <img src="https://skillicons.dev/icons?i=mysql" alt="SQL" />
</p>

---

## Database → Query → Logic

This repository contains **18 SQL practical files**, progressing from relational-table fundamentals to more advanced querying and PL/SQL programming.

```text
TABLES
  ↓
INSERT / UPDATE / DELETE
  ↓
CONDITIONS & AGGREGATION
  ↓
JOINS & RELATIONSHIPS
  ↓
SUBQUERIES / ADVANCED QUERIES
  ↓
PL/SQL
  ├── Procedures
  ├── Functions
  ├── Exceptions
  └── Transactions
```

---

## Practical index

| Range | Area | What it covers |
|---|---|---|
| `01–05` | SQL Foundations | tables, data manipulation, conditions, queries |
| `06–09` | Relational Queries | joins and multi-table operations |
| `10–12` | PL/SQL | procedural logic, functions, procedures, exceptions |
| `13–18` | Advanced SQL | extended query and database programming exercises |

The repository keeps the original practical filenames, including the different naming conventions used across the coursework.

---

## A closer look at the SQL

### Filtering & conditions

The student-table exercise demonstrates relational table creation followed by conditional queries using `AND`, `OR`, `NOT`, `BETWEEN`, and `LIKE`. citeturn226file0

```sql
SELECT * FROM STUDENT
WHERE course = 'CSE' AND marks > 80;
```

This is the foundation for moving from simply retrieving data to **retrieving specific data**.

---

### Joins & relationships

The repository also works with related entities such as **Departments, Employees, Projects, and Assignments**. The join practical demonstrates inner, natural, left, right, full outer, self, and cross joins. citeturn227file0

```text
Departments ──┐
              ├── Employees ── Assignments ── Projects
              │
              └── Manager ↔ Employee
```

This section is where individual tables start behaving like an actual relational system.

---

## PL/SQL: when SQL needs logic

The later practicals move beyond standalone queries into procedural database programming.

One of the larger exercises models **bank accounts and transactions**, including a `transfer_funds` procedure, balance checks, transaction logging, exception handling, rollback, and a balance function. citeturn228file0

```text
TRANSFER REQUEST
       │
       ▼
 same account? ── yes ──► error
       │ no
       ▼
 sufficient balance? ── no ──► error
       │ yes
       ▼
 debit sender
       │
       ▼
 credit receiver
       │
       ▼
 record transaction
       │
       ▼
     COMMIT
```

The same practical also explores transaction history and monthly transaction display using PL/SQL procedures and cursors. citeturn228file0

---

## Concepts covered

`DDL` · `DML` · `SELECT` · `WHERE` · `AND / OR / NOT` · `LIKE` · `BETWEEN` · `JOINS` · `GROUPING` · `RELATIONAL QUERIES` · `PL/SQL` · `PROCEDURES` · `FUNCTIONS` · `EXCEPTION HANDLING` · `TRANSACTIONS` · `COMMIT` · `ROLLBACK`

---

## Repository layout

```text
Database-Management-System_LAB/
│
├── practical 1.sql → practical 6.sql
├── Practical 7.sql → Practical 18.sql
└── practical 1.sql plus
```

The naming is intentionally preserved from the original lab work rather than normalised, so the files remain easy to match with the corresponding practical submissions.

---

## Tools

`SQL` · `PL/SQL` · `Relational Databases` · `Database Programming`

---

<p align="center">
  <sub>Database Management Systems Laboratory · SQL & PL/SQL</sub>
</p>
