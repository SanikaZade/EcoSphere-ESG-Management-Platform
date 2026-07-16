# 🌱 EcoSphere – ESG Management Platform

<p align="center">
  <img src="https://img.shields.io/badge/React-19-blue?logo=react">
  <img src="https://img.shields.io/badge/Vite-Latest-646CFF?logo=vite">
  <img src="https://img.shields.io/badge/Node.js-Express-green?logo=node.js">
  <img src="https://img.shields.io/badge/SQLite-Database-003B57?logo=sqlite">
  <img src="https://img.shields.io/badge/License-MIT-yellow">
</p>

---

# 📖 Overview

**EcoSphere** is a comprehensive ESG (Environmental, Social, and Governance) Management Platform designed to help organizations monitor, manage, and improve their sustainability initiatives through a centralized web application.

The platform enables organizations to track environmental metrics, manage CSR activities, monitor governance and compliance, engage employees through gamification, and generate insightful ESG reports—all within a single, user-friendly interface.

---

# ✨ Features

## 🌍 Environmental

* Carbon emission tracking
* Carbon transaction management
* Emission factor management
* Product profile management
* Sustainability goal tracking
* Environmental analytics

---

## 👥 Social

* Employee management
* CSR activity management
* ESG challenges
* Employee participation tracking
* Rewards & recognition
* Badge management
* XP & Points system

---

## 🏛 Governance

* Governance policy management
* Compliance issue tracking
* Governance monitoring
* Audit management
* Governance score dashboard

---

## 📊 Dashboard & Analytics

* ESG performance dashboard
* Carbon emission statistics
* Employee performance analytics
* CSR analytics
* Interactive charts
* KPI cards

---

## 📑 Reports

Generate and export reports including:

* ESG Reports
* Environmental Reports
* Social Reports
* Governance Reports

Supported export formats:

* PDF
* Excel

---

## 🔐 Authentication

* Secure Login
* JWT Authentication
* Password Hashing using bcryptjs
* Protected Routes
* Role-based Access Control

---

## 🔔 Notifications

* Activity notifications
* ESG updates
* System alerts

---

## ⚙ Master Data Management

Manage:

* Departments
* Categories
* Employees
* Product Profiles
* Emission Factors
* Goals
* Policies
* Rewards
* Badges

---

# 🏗 System Architecture

```text
                React + Vite Frontend
                         │
                         │ REST APIs
                         ▼
              Express.js Backend Server
                         │
                         ▼
                 SQLite Database
                         │
                         ▼
               ESG Analytics & Reports
```

---

# 🛠 Tech Stack

## Frontend

* React 19
* Vite
* JavaScript (ES6+)
* React Router DOM
* CSS3
* Recharts
* jsPDF
* SheetJS (XLSX)

### Backend

* Node.js
* Express.js
* JWT (jsonwebtoken)
* bcryptjs
* dotenv
* CORS

### Database

* SQLite
* sqlite
* sqlite3

### Development Tools

* Git
* GitHub
* Visual Studio Code
* Render
* Oxlint

---

# 📂 Project Structure

```text
EcoSphere_Project/
│
├── public/
│
├── src/
│   ├── api/
│   ├── assets/
│   ├── components/
│   ├── context/
│   ├── data/
│   ├── middleware/
│   ├── pages/
│   ├── routes/
│   ├── utils/
│   │
│   ├── App.jsx
│   ├── main.jsx
│   ├── index.js
│   ├── index.css
│   ├── db.js
│   ├── schema.sql
│   └── seed.sql
│
├── .env.example
├── .gitignore
├── database.sqlite
├── index.html
├── package.json
├── package-lock.json
├── render.yaml
└── README.md
```

---

# 🚀 Installation

## Clone the Repository

```bash
git clone https://github.com/SanikaZade/EcoSphere_Project.git
cd EcoSphere_Project
```

## Install Dependencies

```bash
npm install
```

## Configure Environment Variables

Create a `.env` file in the project root.

```env
JWT_SECRET=your_secret_key
PORT=4000
FRONTEND_URL=http://localhost:5173
```

## Run in Development Mode

```bash
npm run dev
```

## Run the Application

```bash
npm start
```

## Build the Project

```bash
npm run build
```

---

# 🗄 Database

EcoSphere uses **SQLite** as its local database.

When the application starts for the first time, it automatically:

* Creates the SQLite database
* Executes `schema.sql`
* Seeds initial sample data from `seed.sql`

No manual database configuration is required.

---

# 🔐 Default Login Credentials

### Administrator

```text
Email: admin@ecosphere.com
Password: admin123
```

### Employee

```text
Email: employee@ecosphere.com
Password: emp123
```

---

# 📡 API Overview

The backend exposes REST APIs for:

* Authentication
* Dashboard
* Employees
* Departments
* Categories
* Emission Factors
* Carbon Transactions
* Product Profiles
* ESG Goals
* Governance Policies
* Compliance Issues
* CSR Activities
* Rewards
* Badges
* Challenges
* Notifications
* Reports
* Settings

Health Check Endpoint:

```http
GET /api/health
```

---

# 📌 Application Modules

### Dashboard

Provides an overview of ESG metrics through interactive charts and summary cards.

### Environmental

Tracks carbon emissions, emission factors, sustainability goals, and product profiles.

### Social

Manages employees, CSR activities, ESG challenges, rewards, badges, and engagement.

### Governance

Handles governance policies, compliance issues, audits, and governance monitoring.

### Reports

Generates downloadable ESG reports in PDF and Excel formats.

### Master Data

Maintains reference data such as departments, categories, employees, emission factors, product profiles, goals, and policies.

### Settings

Allows administrators to configure system settings and manage platform preferences.

---

# 🚀 Future Enhancements

* AI-powered ESG insights
* Predictive sustainability analytics
* Carbon footprint forecasting
* Multi-organization support
* Cloud database integration
* Email notifications
* Enhanced mobile responsiveness
* Advanced role-based permissions

---

# 👩‍💻 Developer

**Sanika Zade**

Final Year B.Tech – Artificial Intelligence & Machine Learning

Faculty of Engineering & Technology

Datta Meghe Institute of Higher Education & Research (DMIHER), Wardha

GitHub: https://github.com/SanikaZade

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Push your branch.
5. Open a Pull Request.

---

# 📄 License

This project is developed for educational and learning purposes. You are welcome to use, modify, and enhance it with proper attribution.

