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
<img width="1872" height="1170" alt="Login" src="https://github.com/user-attachments/assets/9a43c81a-e208-40ff-a13f-4c0a217a5915" />


### Dashboard
<img width="1893" height="905" alt="home" src="https://github.com/user-attachments/assets/fd80bf3d-1455-4f22-aaf8-7974998e36eb" />


### Todos Management
<img width="1430" height="810" alt="Todos" src="https://github.com/user-attachments/assets/ee65b07f-92ea-46d9-ab79-c1f8f1778d62" />

### Posts & Comments
<img width="1394" height="810" alt="Posts" src="https://github.com/user-attachments/assets/a5ac92c7-679e-4bba-9465-eed20d6f7295" />

### Albums & Photos
<img width="1872" height="894" alt="Albums" src="https://github.com/user-attachments/assets/b2964ef9-fd3a-4ce8-a57f-50ba52b39e0d" />

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
