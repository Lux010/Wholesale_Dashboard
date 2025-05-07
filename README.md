# Wholesale Dashboard

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
