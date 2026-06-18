# 🌿Craine Sanctuary - Admin Dashboard & Payroll System

Welcome to the development workspace for *The Wellhall Resort & Spa* Administrative Portal. This system integrates essential HR management tools, attendance tracking, and dynamic payroll calculations into a cohesive, luxury-inspired user interface.

---

### 🎨 Design & Aesthetic System
- *Theme:* Luxury Wellness / Organic Minimalist.
- *Palette:* Sage/moss greens, soft cream backgrounds, crisp white data cards, and deep forest-green typography.
- *UX Layout:* A persistent, monochromatic green-and-white left sidebar navigation block coupled with a highly organized, rounded-corner dashboard view.

---

### 🛠️ Core Features & System Architecture

#### 1. Operations Dashboard
- Real-time counters for tracking *Total Employees*, *Active Employees*, *Employees on Leave*, and *Total Monthly Payroll*.

#### 2. Administrative Security
- Secure login portal utilizing standard test credentials (admin@test.com / admin123) mapping directly to the Users database table.

#### 3. Employee & Compensation Records (CRUD)
- Complete directory management tracking Employee IDs, contact details, hiring dates, and dynamic employment statuses.
- Automated salary adjustment calculation module processing:
  $$\text{Net Salary} = \text{Basic Salary} + \text{Allowance} - \text{Deductions}$$

#### 4. Attendance & Payroll Ledger
- Centralized daily log interface tracking check-in times (Time In / Time Out) and daily attendance state records.
- Comprehensive payroll processing ledger featuring a dedicated, clean print-view optimization script.

---

### ⚙️ Technical Stack & Data Models

- *Frontend:* React, Tailwind CSS (or Custom CSS)
- *Backend:* Node.js + Express API
- *Database:* SQLite / MySQL / PostgreSQL

#### Relational Database Architecture:
- Users — Administrative credentials and access tokens.
- Employees — Core personal profiles and structural assignment data.
- Salaries — Fixed and variable compensation itemizations.
- Attendance — Clock-in timestamps and daily structural validations.
- Payroll — Compiled historical salary run summaries.
