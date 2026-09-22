<div align="center">

# ⚡ Electricity Billing System

### A Full-Featured Automation Platform for Electricity Bill Management & Payment

[![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](https://www.java.com/)
[![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)](https://www.php.net/)
[![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com/)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen?style=for-the-badge)](CONTRIBUTING.md)

**A comprehensive electricity billing solution** that automates meter reading, tariff calculation, bill generation, payment tracking, and consumer management — built for utility providers and their customers.

[📥 Download](#-getting-started) · [🐛 Report Bug](https://github.com/SIRATHNAYAKA/Electricity-Billing-System/issues) · [✨ Request Feature](https://github.com/SIRATHNAYAKA/Electricity-Billing-System/issues)

</div>

---

## 📑 Table of Contents

<details open>
<summary>Click to expand / collapse</summary>

- [📌 Overview](#-overview)
- [🎯 Key Highlights](#-key-highlights)
- [✨ Features](#-features)
- [🛠 Tech Stack](#-tech-stack)
- [🏗 Architecture](#-architecture)
- [📂 Project Structure](#-project-structure)
- [🗄 Database Schema](#-database-schema)
- [🚀 Getting Started](#-getting-started)
- [🎮 Usage](#-usage)
- [🖼 Screenshots](#-screenshots)
- [🔐 Security Notes](#-security-notes)
- [🔮 Roadmap](#-roadmap)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [📬 Contact](#-contact)

</details>

---

## 📌 Overview

**Electricity Billing System** is a complete software solution designed to automate the traditionally manual, error-prone process of electricity billing. It replaces paper-based workflows with a digital system that handles **meter reading management**, **tariff-based bill calculation**, **automated bill generation**, **payment tracking**, and **consumer self-service** — all in one platform.

The system serves two primary user groups:

- **Consumers** — Register, view bills, check usage history, and make payments
- **Administrators / Utility Providers** — Manage customers, record meter readings, generate bills, and monitor revenue

Built with a focus on **accuracy**, **transparency**, and **efficiency**, this system eliminates billing disputes, reduces processing time, and provides real-time visibility into electricity consumption and revenue.

> 💡 **Why this project?** Unlike basic CRUD billing apps, this system includes **tiered tariff calculation**, **automated bill numbering**, **payment status tracking**, **usage history analytics**, and **role-based dashboards** — making it a practical, production-grade utility management solution.

---

## 🎯 Key Highlights

| 🏆 | Highlight |
| :-: | :--- |
| 🔐 | **Role-based access** — Separate dashboards for consumers, operators, and admins |
| 📊 | **Automated tariff calculation** — Slab-based billing with configurable rates |
| 🧾 | **One-click bill generation** — Auto-numbered invoices with tax breakdown |
| 📈 | **Usage history & analytics** — Monthly consumption trends per consumer |
| 💳 | **Payment tracking** — Record payments, view unpaid bills, generate receipts |
| 🔔 | **Bill alerts** — Notifications for due dates and payment confirmations |
| 🛡️ | **Secure authentication** — Hashed passwords and session management |
| 📱 | **Responsive interface** — Works on desktop, tablet, and mobile |

---

## ✨ Features

### 👤 Consumer Portal

| Feature | Description |
| :--- | :--- |
| 🆕 **Registration** | Create an account with name, address, phone, and meter number |
| 🔑 **Secure Login** | Email/consumer-ID-based authentication with password hashing |
| 📊 **Dashboard** | View current bill, due date, and outstanding balance at a glance |
| 🧾 **Bill View** | Detailed bill breakdown: units consumed, tariff slabs, taxes, total |
| 📜 **Bill History** | Complete archive of past bills with download/print option |
| 📈 **Usage History** | Graphical representation of monthly electricity consumption |
| 💳 **Online Payment** | Pay bills via integrated payment gateway (optional module) |
| 🔔 **Notifications** | Email/SMS alerts for new bills, due dates, and payment confirmation |
| 👤 **Profile Management** | Update contact details and change password |
| 📞 **Complaint / Support** | Raise billing disputes or service requests |

### 🛡️ Admin / Operator Console

| Feature | Description |
| :--- | :--- |
| 📊 **Admin Dashboard** | Overview of total consumers, bills generated, revenue, and pending dues |
| 👥 **Customer Management** | Add, edit, search, and deactivate consumer accounts |
| 📟 **Meter Management** | Assign meters to consumers, record installation dates |
| 📝 **Meter Reading Entry** | Record periodic readings with automatic unit consumption calculation |
| 🧾 **Bill Generation** | Auto-generate bills based on readings and configured tariff slabs |
| 💰 **Tariff Management** | Configure slab rates, fixed charges, taxes, and surcharges |
| 💳 **Payment Recording** | Log offline payments (cash/cheque) and reconcile online payments |
| 📑 **Reports** | Daily/monthly revenue reports, unpaid bill reports, consumer summaries |
| 🔍 **Audit Trail** | Track all billing and payment actions with timestamps |
| ⚙️ **System Settings** | Configure billing cycle, due date rules, and notification templates |

### ⚙️ Technical Features

- **Prepared Statements** — Protection against SQL injection in all queries
- **Password Hashing** — Bcrypt / SHA-256 for secure credential storage
- **Session Management** — Secure sessions with timeout and regeneration
- **Input Validation** — Server-side validation for all form inputs
- **Pagination** — Efficient handling of large consumer and bill datasets
- **Modular Architecture** — Separate layers for UI, business logic, and data access
- **Configurable Tariffs** — Slab rates stored in database, not hardcoded
- **Bill Number Auto-Generation** — Unique, sequential bill identifiers

---

## 🛠 Tech Stack

<div align="center">

| Category | Technology |
| :--- | :--- |
| **Language (Desktop)** | Java SE 8+ |
| **Language (Web)** | PHP 7.x / 8.x |
| **GUI (Desktop)** | Java Swing / JavaFX |
| **Front-end (Web)** | HTML5, CSS3, JavaScript, Bootstrap |
| **Database** | MySQL 5.7+ / 8.0 |
| **DB Connectivity** | JDBC (Java) / PDO (PHP) |
| **Server** | Apache (XAMPP / WAMP / LAMP) |
| **Build Tool** | Maven / Gradle *(optional)* |
| **IDE** | IntelliJ IDEA · Eclipse · NetBeans · VS Code |
| **Version Control** | Git + GitHub |

</div>

> **Note:** This system supports both **desktop (Java Swing)** and **web (PHP)** implementations. Choose the stack that matches your deployment scenario.

---

## 🏗 Architecture

The system follows a **layered architecture** with clear separation of concerns:
