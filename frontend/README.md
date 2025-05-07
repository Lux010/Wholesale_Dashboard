# Wholesale Dashboard

A modern microservice application using React for the frontend and Node.js (Express) for the backend. Containerized using Docker and ready for CI/CD integration.

## 📁 Project Structure

src/
├── components/
│ ├── layout/
│ │ ├── Sidebar.jsx
│ │ ├── Header.jsx
│ │ ├── Layout.jsx
│ │ └── NavItem.jsx
│ ├── dashboard/
│ │ ├── StatCard.jsx
│ │ ├── ActivityItem.jsx
│ │ ├── InventoryOverview.jsx
│ │ └── TopSellingProducts.jsx
│ ├── inventory/
│ │ ├── InventoryTable.jsx
│ │ ├── InventoryFilters.jsx
│ │ └── Pagination.jsx
│ ├── database/
│ │ ├── DatabaseCard.jsx
│ │ ├── DatabaseUpdates.jsx
│ │ ├── DatabaseHealth.jsx
│ │ └── QuickActions.jsx
│ └── ui/
│ ├── Button.jsx
│ ├── Badge.jsx
│ └── ProgressBar.jsx
├── pages/
│ ├── Dashboard.jsx
│ ├── Inventory.jsx
│ ├── Database.jsx
│ ├── Reports.jsx
│ ├── Suppliers.jsx
│ └── Settings.jsx
├── data/
│ ├── mockInventory.js
│ └── mockDashboard.js
├── hooks/
│ └── useSidebar.js
├── contexts/
│ └── SidebarContext.jsx
├── utils/
│ └── formatters.js
├── App.jsx
└── index.js

## 🛠 Tech Stack

- React 18
- Node.js (Express)
- Docker & Docker Compose
- GitHub Actions (CI/CD-ready)

## 🧪 Getting Started (Dev)

```bash
# Build and run both services
docker-compose up --build
```
