# DVLD – Driving & Vehicle License Department Management System

A comprehensive **3-Tier desktop application** built with **C#**, **Windows Forms**, and **SQL Server**, designed to automate the full lifecycle of driving license issuance and management.

> **Note:** This project was developed as part of the **"Full Project in C#"** course by **Eng. Mohammed Abu-Hadhoud (Programming Advices)**. I built it independently following the instructor's solution to master 3-Tier architecture and real-world business logic.

---

## 📦 Project Scale

| Metric | Count |
|---|---|
| Projects (Layers) | 3 (UI, Business, DataAccess) |
| Business Classes | ~20 |
| Data Access Classes | ~18 |
| Windows Forms (Screens) | 30+ |
| Database Tables | 15+ |
| License Categories | 7 |
| Services Implemented | 7 |

---

## 🏗️ Architecture

```
DVLD (UI - Windows Forms)
    ↓
DVLD_Business (Business Logic Layer)
    ↓
DVLD_DataAccess (Data Access Layer - ADO.NET)
    ↓
SQL Server Database
```

---

## ⚙️ What the System Does

**Core Services:**
- First-time license issuance (3-stage testing: Vision → Written → Practical)
- License renewal, replacement (lost/damaged), and detention release
- International license issuance (Class 3 holders only)

**Business Rules:**
- Age validation per license class (18 / 21 years)
- Sequential test enforcement (cannot skip stages)
- Unique National ID enforcement
- Prevent duplicate license of same class

**Management Modules:**
- People & Users (with activation/permissions)
- Applications & Application Types
- Tests & Test Appointments
- License Classes & Detained Licenses

---

## 🛠️ Tech Stack

- **Language:** C#
- **UI:** Windows Forms
- **Database:** SQL Server (ADO.NET)
- **Architecture:** 3-Tier (Presentation, Business, Data Access)
- **Tools:** Visual Studio, SSMS, Git

---

## 📚 What I Learned

- Designing and implementing **3-Tier Architecture** from scratch
- Translating **complex business rules** into maintainable code
- Handling **relational data** with Many-to-Many and One-to-Many relationships
- Building **30+ interconnected screens** with consistent UX
- Managing a **large-scale codebase** (~60 classes)

---

## 🙏 Acknowledgments

Built under the mentorship of **Eng. Mohammed Abu-Hadhoud** as part of the **Programming Advices** diploma. Special thanks for the professional architectural guidance.

---
