# 🧠 Hands-on Lab: Sub-queries and Nested SELECTs

## ⏱ Estimated time needed: **20 minutes**

Welcome to this lab, where you’ll get **hands-on experience** with nested SQL `SELECT` statements—also known as **Sub-queries**. These exercises will help you understand how sub-queries work and when to use them.

---

## 🔍 What is a Nested SELECT?

A typical Nested `SELECT` (Sub-query) looks like this:

```sql
SELECT column_name [, column_name ]
FROM table1 [, table2 ]
WHERE column_name OPERATOR
  (SELECT column_name [, column_name ]
   FROM table1 [, table2 ]
   WHERE condition);
## 🎯 **Objectives**

After completing this lab, you will be able to:

- **Write SQL queries** that demonstrate the necessity of using sub-queries  
- **Compose sub-queries** in the `WHERE` clause  
- **Build Column Expressions** (sub-query in place of a column)  
- **Write Table Expressions** (sub-query in place of a table)

📁 **Note:** Ensure that you are using the CSV file and datasets provided in the instruction file.
 

## 🧭 **Instructions**

To run the SQL queries in this lab on Db2:

1. Go to the **Resource List** on
