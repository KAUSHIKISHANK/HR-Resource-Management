# HR Resource Management System 🏢

A modern HR Dashboard built with React, Vite, and Recharts for managing employee data, leave requests, and performance tracking.

## 🎯 Features

- **Dashboard** - Overview of total employees, active employees, departments, and pending leaves with department-wise bar chart
- **Employees** - View all employees with search and filter functionality
- **Leave Requests** - Track employee leave statuses
- **Performance** - Visualize employee performance ratings with line charts
- **Responsive Design** - Clean and modern UI with Tailwind CSS

## 🛠️ Tech Stack

- **Frontend**: React 19.2.5
- **Build Tool**: Vite 8.0.10
- **Routing**: React Router DOM v7
- **Charts**: Recharts 3.8.1
- **Styling**: Tailwind CSS 4.2.4

## 📦 Installation

```bash
npm install
```

## 🚀 Running the Project

```bash
npm run dev
```

The app will be available at `http://localhost:5174/`

## 📁 Project Structure

```
src/
├── components/
│   ├── Navbar.jsx
│   └── Sidebar.jsx
├── page/
│   ├── Dashboard.jsx
│   ├── Employees.jsx
│   ├── Leave.jsx
│   └── Performance.jsx
├── data/
│   └── Employees.js
├── App.jsx
├── App.css
├── main.jsx
└── index.css
```

## 📊 Dashboard Pages

1. **Dashboard** - KPI cards and department analytics
2. **Employees** - Employee list with search/filter
3. **Leave Requests** - Leave status tracking
4. **Performance** - Employee performance graph

## 🎨 Styling

Custom CSS with responsive design for all screen sizes.

## 📝 License

MIT
