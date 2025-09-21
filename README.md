# SQL-Injection-Attack

This repository provides a concise reference for **SQL Injection techniques**, **automation tools**, and **dictionary generation methods** commonly used in penetration testing and ethical hacking.

---

## 📌 Overview
SQL Injection (SQLi) is one of the most common web application vulnerabilities.  
It allows attackers to interfere with the queries that an application makes to its database, potentially exposing sensitive data.

This project highlights:
- ✅ Automated exploitation using **sqlmap**  
- ✅ Manual SQL injection queries  
- ✅ Wordlist generation with **Crunch**  
- ✅ Database exploitation using **jSQL Injection**  

---

## 🛠️ Tools & Techniques

### 1. **Sqlmap**
- Automates the process of detecting and exploiting SQL injection flaws.
- Extracts **databases, tables, columns, and data** with minimal effort.  

---

### 2. **Manual SQL Injection**
- Use crafted SQL queries directly in the URL to enumerate:  
  - Databases  
  - Tables  
  - Columns  
  - Sensitive data (usernames, passwords, etc.)  

---

### 3. **Crunch (Wordlist Generator)**
- Generate custom password dictionaries.
- Supports:
  - 🎯 Pattern-based wordlists  
  - 🔄 Start/End points  
  - 📂 File splitting by size/lines  
  - ⛔ Limiting duplicate characters  

---

### 4. **jSQL Injection**
- A lightweight GUI-based SQL injection tool.
- Features:  
  - Database scanning  
  - Table & column extraction  
  - Data dumping (export to CSV, TXT, SQL)  

---

## ⚠️ Disclaimer
This project is intended **strictly for educational and ethical purposes**.  
Do **NOT** use these techniques on systems without **explicit authorization**.  
Unauthorized testing may be **illegal** and punishable by law.

---

## ✨ Credits
- Tools: `sqlmap`, `Crunch`, `jSQL Injection`  
- Test Environment: [Vulnweb.com](http://testphp.vulnweb.com) (safe for practice)  

---
🔎 *Learn | Practice | Secure*
