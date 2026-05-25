# SQL Practice Questions — Sakila Database

A set of 15 SQL practice questions with answers based on the **Sakila** sample database.

---

## Database Setup

```bash
# Download Sakila from MySQL official site
# https://dev.mysql.com/doc/sakila/en/

mysql -u root -p < sakila-schema.sql
mysql -u root -p < sakila-data.sql
```

---

## Files

```
sql-practice/
├── README.md               ← You are here
└── queries/
    ├── 01_basic_filters.sql
    ├── 02_aggregation.sql
    ├── 03_joins_subqueries.sql
    └── answers_all.sql     ← All 15 answers in one file
```

---

## Topics Covered

| # | Topic |
|---|---|
| 1–4 | WHERE, LIKE, AND, IS NOT NULL |
| 5–8 | GROUP BY, HAVING, COUNT, SUM |
| 9–11 | IS NULL, IN, ORDER BY, LIMIT |
| 12–13 | JOIN, HAVING with aggregates |
| 14–15 | LEFT JOIN, Subqueries |

---

## How to Run

Open `answers_all.sql` in **MySQL Workbench**, **DBeaver**, or **VS Code with SQLTools extension** and run each query.
