# IMS System (Inventory Management System) 🔒📦 | Documentation Only (No Source Code)

This is an **internal IMS system developed for my company** to manage and track inventory operations efficiently.  
Due to **company policy / NDA**, the **live link and source code cannot be shared publicly**.  
✅ **Demo / detailed walkthrough can be provided on request.**

---

## 📌 Project Overview
The IMS System streamlines day-to-day inventory operations by managing **current stock**, monitoring **stock movement (IN/OUT)**, generating reports, and enabling fast purchase planning using **automatic stock-based indicators**.

---

## ✨ Key Features
- **Item Master Management**
  - Add / Update / Delete inventory items
  - Maintain item details such as category, unit, and stock thresholds

- **Stock Tracking (IN / OUT)**
  - Manage stock inward (Stock IN) entries
  - Manage stock outward (Stock OUT) entries
  - Automatically updates available stock after each transaction

- **Real-Time Stock Availability**
  - Displays current stock instantly for each material
  - Helps teams track inventory without manual calculations

- **Smart Stock Status Highlighting (Color Indicators)**
  - **Magenta:** More than **100** quantity available *(high stock)*
  - **Green:** More than **60** and less than **100** *(good stock)*
  - **Yellow:** Less than **60** and greater than **30** *(warning level)*
  - **Red:** Less than **30** *(critical stock — immediate action required)*

- **Automatic Purchase Planning**
  - Automatically identifies **which materials need to be purchased**
  - Critical/low-stock materials are highlighted automatically (Red Alert)
  - Auto-updates required materials directly in the **Purchase Sheet**
  - ✅ **No manual effort needed** for updating purchase requirements

- **Dashboard & Reporting**
  - Stock summary dashboard for quick visibility
  - Inventory movement reports (IN/OUT history)
  - Supports operational decision-making

- **Role-Based Access Control (RBAC)**
  - Admin / Manager / User level access
  - Permission-based controls for secure operations

- **Data Accuracy & Audit Tracking**
  - Maintains logs for inventory updates
  - Ensures traceability of stock changes and user actions

---

## 📈 Business Impact
- ✅ Reduced manual inventory tracking effort
- ✅ Faster purchase planning and procurement workflow
- ✅ Fewer stock-out issues due to real-time visibility and alerts

---

## 🧑‍💻 My Responsibilities
- Requirement gathering and understanding internal business flow
- Designed inventory database structure and transaction logic
- Developed complete IMS workflow (UI + Backend integration)
- Implemented stock indicators & automated purchase-sheet updates
- Testing, bug fixing, and deployment support for internal usage

---

## 🛠️ Tech Stack
- **Frontend:** HTML, CSS
- **Backend:** Python (Flask)
- **Database:** MySQL
- **Tools:** Git, Postman, Excel Reporting, Google Sheets
- **Deployment:** Internal Company Network / Internal Server

## 📂 Repository Structure

ims-system-documentation/
│
├── README.md
├── docs/
│   ├── architecture-diagram.png
│   ├── screenshots/
│   │   ├── dashboard.png
│   │   ├── inventory-list.png
│   │   ├── stock-in.png
│   │   ├── stock-out.png
│   │   ├── reports.png
│   └── project-summary.pdf (optional)
│
└── LICENSE

## 🧱 System Architecture (High Level)
```txt
User → Frontend UI → Backend API / Business Logic → Database → Reports & Dashboard




