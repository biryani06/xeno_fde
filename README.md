# Xeno FDE Internship – Shopify Data Ingestion & Insights Service

This project implements a **multi-tenant Shopify Data Ingestion & Insights Service**, as required for the Xeno Forward Deployed Engineer Internship Assignment 2025.

It simulates how Xeno helps enterprise retailers onboard, integrate, and analyze their customer data.

---

## 🚀 Features
- **Multi-Tenancy**: Each Shopify store (tenant) has isolated data via `tenantId`.
- **Shopify Data Ingestion**: 
  - Customers, Orders, Products (via Shopify REST API).
  - Real-time updates via Shopify **Webhooks**.
  - Scheduled background sync via **cron job**.
- **Database**: PostgreSQL with **Prisma ORM** for clean schema handling.
- **Authentication**: Email + Password with JWT.
- **Insights Dashboard (Next.js)**:
  - Total customers, orders, and revenue.
  - Orders by date (line chart with filtering).
  - Top 5 customers by spend.
- **Deployment Ready**: Backend (Render/Railway/Heroku), Frontend (Vercel), Database (Supabase/Postgres).

---

## 🛠️ Tech Stack
- **Backend**: Node.js (Express.js) + Prisma
- **Frontend**: Next.js (React)
- **Database**: PostgreSQL
- **Auth**: JWT
- **Charts**: Chart.js (react-chartjs-2)
- **Scheduler**: node-cron

---

## 📦 Project Structure
