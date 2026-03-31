# oss-audit-24BCE10956

---

# 🧾 Open Source Audit — MySQL & Linux Shell Scripts

## 📌 Overview

This repository contains a **capstone project for the Open Source Software course**, focusing on a detailed audit of **MySQL** as an open-source system along with practical **Linux shell scripting implementations**.

The project explores:

* Open-source philosophy & licensing (GPL v2)
* MySQL architecture and ecosystem
* Linux system integration
* Real-world shell scripting tasks

---

## 🎯 Objectives

* Analyze MySQL as an open-source software
* Understand **GPL v2 licensing and dual licensing model**
* Explore MySQL’s role in the **LAMP stack**
* Perform system-level tasks using **Bash scripting**
* Demonstrate practical Linux + MySQL interaction

---

## 🛠️ Technologies Used

* **MySQL**
* **Linux (Ubuntu/Debian)**
* **Bash Shell Scripting**
* **GNU Tools (awk, grep, sed, etc.)**

---

## 📂 Project Structure

```
├── script1_system_identity.sh
├── script2_package_inspector.sh
├── script3_disk_auditor.sh
├── script4_log_analyzer.sh
├── script5_manifesto_generator.sh
└── README.md
```

---

## 📜 Shell Scripts Description

### 1️⃣ System Identity Report

Displays system information including:

* Kernel & OS details
* Logged-in user
* Uptime & date/time
* MySQL version (if installed)

👉 Concepts used:

* Variables
* Command substitution
* Conditional statements

---

### 2️⃣ FOSS Package Inspector

Checks whether **MySQL server** is installed and displays:

* Version info
* Maintainer details
* Open-source philosophy note

👉 Concepts used:

* `if-else`
* `case` statement
* `dpkg`, `grep`, `awk`

---

### 3️⃣ Disk & Permission Auditor

Audits important system directories:

* Disk usage
* Permissions
* Ownership

Also checks:

* MySQL data directory (`/var/lib/mysql`)

👉 Concepts used:

* Arrays
* Loops
* `du`, `ls`, `awk`

---

### 4️⃣ Log File Analyzer

Analyzes log files for a keyword (default: `error`):

* Counts occurrences
* Displays last 5 matching lines

👉 Usage:

```bash
./log_analyzer.sh /var/log/mysql/error.log error
```

👉 Concepts used:

* While loop
* File handling
* Command-line arguments

---

### 5️⃣ Open Source Manifesto Generator

Interactive script that:

* Takes user input
* Generates a personalized open-source manifesto
* Saves output to a `.txt` file

👉 Concepts used:

* `read`
* File handling (`>`, `>>`)
* String formatting

---

## ⚙️ Installation & Setup

### Install MySQL (Ubuntu/Debian)

```bash
sudo apt update
sudo apt install mysql-server -y
```

### Run Scripts

```bash
chmod +x script_name.sh
./script_name.sh
```

---

## 🔍 Key Learnings

* Importance of **open-source licensing (GPL v2)**
* MySQL’s impact on modern web infrastructure
* Practical exposure to **Linux system administration**
* Writing efficient and modular **Bash scripts**

---

## ⚖️ Open Source Philosophy

This project highlights how MySQL:

* Started as a free alternative to expensive databases
* Became the backbone of the web (LAMP stack)
* Demonstrates the power of **community-driven development**
* Shows the balance between **open-source and commercial models**

---

## 👨‍💻 Author

**Krish Raj Singh**
Registration No: 24BCE10956

---

## 📚 References

* MySQL Official Documentation
* GNU GPL v2 License
* MariaDB Foundation
* Open Source Initiative

---

## ⭐ Final Note

This project demonstrates that **open source is not just code — it's a philosophy, ecosystem, and foundation of modern computing.**

---


