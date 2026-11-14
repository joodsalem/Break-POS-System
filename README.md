# ☕ Break POS – Cafeteria Point of Sale & Management System


**Break POS** is a live, Arabic-first (RTL) web-based Point of Sale (POS) and management system engineered for real-world cafeteria operations. Designed and developed end-to-end as a solo project, the system delivers seamless performance across cashier tablets and owner mobile/desktop devices.

> **Note:** This repository serves as a project showcase and architectural overview. The source code is kept private as the system is actively deployed in a live commercial environment.

---

## Key Features

### Cashier Interface (Tablet-Optimized)
* **Fast Checkout:** Category-based product filtering, instant search, and dynamic cart management.
* **Cash Handling:** Automated change calculation for cash payments.
* **Thermal Printing:** Direct 80mm receipt printing via Bluetooth (Mopria integration).

### Owner Dashboard (Mobile & Desktop)
* **Real-Time Analytics:** Daily and monthly revenue tracking, peak-hour insights, and top/least-selling product reports.
* **Inventory & Catalog Management:** Add, edit, categorize, or temporarily hide menu items.

### Security & Architecture
* **Role-Based Access Control (RBAC):** Strict separation between Cashier and Owner permissions.
* **Database Security:** Powered by **Supabase Row-Level Security (RLS)** and server-side PostgreSQL functions for atomic invoice creation and daily sequential numbering.
* **Cashier PIN Protection:** Quick PIN login with brute-force attempt limits.

---

## Tech Stack

* **Frontend:** React, TypeScript, Vite, React Router
* **Styling:** Custom CSS with full RTL support and responsive layouts
* **Backend & Database:** Supabase (PostgreSQL, Auth, RPC Functions, RLS)
* **Testing:** Vitest
* **Deployment:** Vercel

---

## Project Role

* **Solo Full-Stack Developer & UI/UX Designer:** Independently architected the database schema, implemented security policies, designed the RTL user interfaces, integrated thermal printing, and deployed the live production build.

---

## Screenshots

<p align="center">
  <img width="960" alt="Cashier POS View" src="https://github.com/user-attachments/assets/81bc3280-1b66-4aef-97e1-5bff68eed566" />
</p>

<p align="center">
  <img width="960" alt="Owner Dashboard Analytics" src="https://github.com/user-attachments/assets/1d6b876c-c54b-4de9-88de-0b90b4bfff37" />
</p>

<p align="center">
  <img width="960" alt="Menu and Inventory Management" src="https://github.com/user-attachments/assets/991ea692-1b66-4de9-88de-0b90b4bfff37" />
</p>

<p align="center">
  <img width="960" alt="System Settings and Reports" src="https://github.com/user-attachments/assets/d341c31c-e0ef-4e2f-88de-0b90b4bfff37" />
</p>

<p align="center">
  <img width="280" alt="Mobile & Receipt View" src="https://github.com/user-attachments/assets/55187977-d20e-4181-9b36-b410a7c25523" />
</p>
