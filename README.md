# 🐘 PL/SQL Playground  

![GitHub repo size](https://img.shields.io/github/repo-size/aansheeagrwal/PLSQL-Problems?color=blueviolet) ![GitHub contributors](https://img.shields.io/github/contributors/aansheeagrwal/PLSQL-Problems) ![GitHub last commit](https://img.shields.io/github/last-commit/aansheeagrwal/PLSQL-Problems?color=success) ![License](https://img.shields.io/badge/License-MIT-yellow.svg)

Welcome to my **PL/SQL Learning & Experiments Repository** 🎉  
This repo is my personal space to practice, explore, and share different **PL/SQL concepts** with simple, practical examples.  

Unlike typical repositories, this isn’t just code — it’s more like my **PL/SQL diary** 📓 where every script has a purpose, a story, and a learning behind it.  

---

## 📂 What’s Inside?  

- 🔹 **Basics** → Variables, Data Types, Conditional Statements  
- 🔹 **Cursors** → Explicit, Implicit, and Cursor FOR loops  
- 🔹 **Procedures & Functions** → Reusable PL/SQL blocks for tasks  
- 🔹 **Triggers** → Automating actions when data changes  
- 🔹 **Exception Handling** → Dealing with errors gracefully  
- 🔹 **Mini Projects** → Real-world inspired exercises  

---

## 🚀 Why this Repository is Unique?  

✔️ **Not just scripts** – each file has **comments & explanations** to help beginners.  
✔️ **Practical focus** – scripts are tested on real HR schemas (like `employees`, `departments`).  
✔️ **Progressive approach** – arranged in a learning flow, from beginner → advanced.  
✔️ **Creative touch** – every section feels like a step in a game 🎮 (Level 1: Basics, Level 2: Cursors, …).  

---

## 🛠 How to Use  

1. Clone the repo  
   ```bash
   git clone https://github.com/aansheeagrwal/PL-SQL.git
   ```
2. Open scripts in SQL Developer / SQL*Plus / VS Code
3. Run and experiment with modifications 🧪
   Example Snippet
   ``` SQL
   DECLARE
   v_salary employees.salary%TYPE;
   BEGIN
   SELECT salary INTO v_salary 
   FROM employees 
   WHERE employee_id = 100;

   DBMS_OUTPUT.PUT_LINE('Employee Salary: ' || v_salary);
   EXCEPTION
   WHEN NO_DATA_FOUND THEN
    DBMS_OUTPUT.PUT_LINE('No employee found!');
   WHEN TOO_MANY_ROWS THEN
    DBMS_OUTPUT.PUT_LINE('Query returned multiple rows!');
   END;

   ```
---  
## 🌱 Future Add-ons
- 🔹 PL/SQL Interview Questions
- 🔹 Advanced Performance Tuning Examples
- 🔹 Integration with Python/Flask APIs for hybrid projects

---
## 🤝 Contribution
This is my personal journey log, but if you’ve got an interesting PL/SQL puzzle, feel free to fork, play around, and submit a PR.

## 📌 Note
This repo is 100% original and handwritten.
No copy-paste from tutorials — only curated learning experiments ✨

## 👩‍💻 Author
📧 aansheeagrwal123@gmail.com
🌐 Exploring Databases | AI | Backend Systems
