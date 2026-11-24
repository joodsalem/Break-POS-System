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

<img width="960" height="540" alt="جديد" src="https://github.com/user-attachments/assets/44bae93a-b44d-413c-a6f0-a870f794f355" />


<img width="237" height="404" alt="4" src="https://github.com/user-attachments/assets/cef29bbe-0a2a-4d8d-954a-5d78067114f9" />

<img width="960" height="438" alt="11" src="https://github.com/user-attachments/assets/cb8d1ad2-6148-4d4c-a510-40ebddae64de" />
<img width="960" height="423" alt="22" src="https://github.com/user-attachments/assets/44bdbb92-d6ee-497d-b917-e355eb1b4893" />

<img width="960" height="437" alt="33" src="https://github.com/user-attachments/assets/a1cdcf7c-1dba-4da4-83a3-76c83448e496" />

<img width="960" height="433" alt="77" src="https://github.com/user-attachments/assets/760cf28f-d089-4cf1-a4be-2b3a41a38f45" />

<img width="960" height="540" alt="فواتير" src="https://github.com/user-attachments/assets/d8b1973d-627c-455f-9496-8f0cbf016fc9" />




