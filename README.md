# HalleyX Workflow Engine - Challenge I

**Developed by:** Arun Kumar S (3rd Year CSD Student)

## 📋 Project Overview
This is a high-performance **Full-Stack Workflow Automation System** built for the HalleyX Challenge. The engine allows users to define custom business workflows, set logical conditions using the MVEL expression engine, and execute them with a real-time terminal log viewer.



## ✨ Key Features
- **Dynamic Workflow Builder:** Create multiple workflows like Leave Approval, Expense Approval, and Employee Onboarding.
- **Step & Rule Designer:** A sidebar-based UI to add sequential steps and define complex logic rules.
- **MVEL Rule Engine:** Uses MVFLEX Expression Language for advanced condition evaluation (e.g., `amount > 500`).
- **Professional Execution Terminal:** A custom-built pop-up terminal that displays syntax-highlighted execution logs.
- **Responsive UI:** Dark-themed, modern dashboard built with React and Tailwind CSS.

## 🛠️ Tech Stack
- **Frontend:** React.js, Tailwind CSS, Lucide-React (Icons)
- **Backend:** Spring Boot (Java), JPA/Hibernate
- **Database:** MySQL
- **Logic Engine:** MVEL 2.0

## 🚦 Sample Workflows Configured
1. **Expense Approval:** Logic: `amount > 500` → Routes to CEO Approval.
2. **Leave Approval:** Logic: `days > 3` → Routes to Manager Review.
3. **Employee Onboarding:** Linear sequence (IT Setup -> Security -> HR Orientation).



## ⚙️ Setup & Installation
### Backend:
1. Import the `backend` folder into IntelliJ IDEA.
2. Update `src/main/resources/application.properties` with your MySQL credentials.
3. Run `WorkflowEngineApplication.java`.

### Frontend:
1. Open the `frontend` folder in VS Code.
2. Run `npm install` to install dependencies.
3. Run `npm run dev` to start the dashboard at `http://localhost:5173`.

### Database:
1. Import the SQL script from the `/database` folder into MySQL Workbench to set up tables.

---
© 2026 Arun Kumar S - HalleyX Full Stack Developer Challenge.
