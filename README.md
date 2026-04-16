# HealthShield — Secure Healthcare Portal

**HH8 Major Project** | Cybersecurity + Healthcare Management System

---

## 🛡️ Overview

HealthShield is a full-stack (single-file) secure healthcare portal with:
- **User Interface** — Patient records, billing, pharmacy, appointments, and profile
- **Admin Interface** — Security Operations Center (SOC) with live threat monitoring

---

## 🚀 Getting Started

Just open `index.html` in any modern browser. No server setup required.

### Login Credentials

| Role  | Username | Password  |
|-------|----------|-----------|
| User  | `user`   | `user123` |
| Admin | `admin`  | `admin123`|

**PDF Download PIN:** `1234`

---

## 🔐 Security Features

### 1. User Login — Wrong Password → Live Admin Alert
If a user enters an incorrect password on the User Login page:
- A **live red popup alert** appears on the Admin side immediately
- The event is logged in the **AI Log terminal** as `CRITICAL [AUTH_FAILURE]`
- The **Failed Logins counter** on the Admin Live Alerts page increments

### 2. PDF Download — Wrong PIN → Live Admin Alert
If the user enters an incorrect PIN in the download modal:
- A **live red popup alert** fires on the Admin side instantly
- Logged as `CRITICAL [PIN_FAILURE]` in the AI terminal
- Marked as a **suspicious activity** event

### 3. Excess Download Detection
Downloading the same document more than 2 times triggers a **Critical alert** to Admin.

---

## 👤 User Profile

The **My Profile** section displays only the authenticated user's personal details:

| Field   | Value                   |
|---------|-------------------------|
| Name    | Majumder Royal          |
| Mobile  | +91 93650 83378         |
| Email   | majumderroyal@gmail.com |
| Address | Bangalore               |

Other sections (Patient Details, Treatment, Lab, Billing, Pharmacy) retain demo data.

---

## 📁 Project Structure

```
hh8-major-project/
├── index.html       ← Main application (all-in-one)
├── README.md        ← This file
├── CHANGELOG.md     ← Version history
├── .gitignore
├── assets/
│   ├── css/         ← (styles embedded in index.html)
│   ├── js/          ← (scripts embedded in index.html)
│   └── images/
├── pages/           ← Reserved for future expansion
└── docs/
    └── security-flow.md
```

---

## 📝 Developer

**Majumder Royal** | HH8 Major Project
