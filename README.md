# Roomify Infrastructure

This repository contains the infrastructure configuration and environment setup for the Roomify system.

It manages how the frontend, backend, and database are configured and deployed.

---

## 📦 Infrastructure Components

- ASP.NET Core Backend
- PostgreSQL Database
- React Frontend
- Environment configuration
- JWT Secret management

---

## 🗄 Database Setup

Database: PostgreSQL

Create database:

roomify_db

Connection format:

Host=localhost;Port=5432;Database=roomify_db;Username=postgres;Password=your_password

---

## 🔐 Environment Variables

Backend (appsettings.Development.json):

- ConnectionStrings
- Jwt:Key
- Jwt:Issuer
- Jwt:Audience

Frontend (.env):

VITE_API_URL=https://localhost:7252/api

---

## 🚀 Running Locally

1. Start PostgreSQL
2. Run Backend:
   dotnet run
3. Run Frontend:
   npm run dev

---

## 🧱 Deployment Strategy (Current)

Local development environment:

- Backend runs on HTTPS port 7252
- Frontend runs on port 5173
- Database runs on port 5432

---

## Author

Zahrin Savana Khadijah  
Infrastructure Configuration – Roomify Project
