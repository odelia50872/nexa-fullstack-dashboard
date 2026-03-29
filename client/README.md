# Nexa – Full-Stack User Platform Simulator

Nexa is a production-deployed full-stack web application that simulates a modern user data platform.  
It allows authenticated users to manage personal content across multiple domains including **Todos, Posts, Comments, Albums and Photos**.

The system demonstrates scalable frontend architecture, reusable logic patterns, relational data navigation and real cloud deployment practices.

---

## 🌐 Live Application
* **Frontend (Vercel):** [https://nexa-fullstack-dashboard.vercel.app/](https://nexa-fullstack-dashboard.vercel.app/)
* **Backend API (Render):** [https://nexa-fullstack-dashboard.onrender.com](https://nexa-fullstack-dashboard.onrender.com)

---

## 🔑 Demo Credentials
You can explore the system using an existing user from the API.

**Example:**
* **Username:** `Bret`
* **Password:** (use the value from the user’s `website` field)

---

## 📸 Screenshots
*(To display images, upload your screenshots to the repository and link them here)*

### Authentication
![Login Screen](link-to-your-image-here)

### Dashboard
![Home Screen](link-to-your-image-here)

### Todos Management
![Todos Screen](link-to-your-image-here)

### Posts & Comments
![Posts Screen](link-to-your-image-here)

### Albums & Photos
![Albums Screen](link-to-your-image-here)

---

## 🚀 Project Overview
Nexa simulates a real data-driven platform where users can:
* Manage personal tasks (**Todos**)
* Create and edit **posts**
* Add and manage **comments**
* Navigate relational entities
* Create **albums** and load photos incrementally
* Maintain persistent authenticated sessions

The project focuses on **clean architecture**, modularity, and real frontend engineering workflows.

---

## 🏗️ Production Architecture
`User Browser` ➔ `React Client (Vercel)` ➔ `HTTPS REST Requests` ➔ `Mock API Server (Render)` ➔ `Local JSON Database (db.json)`

---

## ✨ Engineering Highlights
- **Protected routing** and authentication persistence.
- **Context-based** global state management.
- **Reusable generic CRUD hooks**.
- **Nested routing** for relational data structures.
- **Incremental loading strategy** for performance.
- Centralized **API abstraction layer**.
- Notification feedback system.
- Modular scalable folder organization.

---

## 📂 Repository Structure
```text
project/
├── client/  # React frontend
└── server/  # Mock REST API
