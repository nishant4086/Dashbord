# Syncfusion Admin Dashboard

A comprehensive React-based admin dashboard application built with Syncfusion components. This dashboard provides a modern, feature-rich interface with theming, advanced data visualization, scheduling, and more.

**Built by:** Nishant

## 🚀 Features

- **Responsive Design** - Mobile-friendly and responsive layout
- **Dark/Light Theme** - Dynamic theme switching capability
- **Interactive Charts** - Multiple chart types (Line, Bar, Pie, Area, Stacked, Financial, etc.)
- **Data Tables & Grids** - Advanced data grid with filtering and sorting
- **Calendar & Scheduling** - Integrated calendar and event scheduling
- **Kanban Board** - Task management with drag-and-drop functionality
- **Rich Text Editor** - WYSIWYG editor for content creation
- **Color Picker** - Built-in color selection tool
- **Customer & Order Management** - Pre-built pages for managing customers and orders
- **Employee Management** - Employee data management interface
- **Notifications & Chat** - Real-time notification system and chat interface

## 📚 Tech Stack

### Frontend Framework
- **React** (v17.0.2) - UI library
- **React Router DOM** (v6.2.1) - Client-side routing

### UI Components & Visualization
- **Syncfusion EJ2 Suite** (v19.4.x):
  - React Charts - Advanced data visualization
  - React Grids - Data tables and grids
  - React Calendar - Date selection
  - React Scheduler - Event scheduling
  - React Kanban - Task board
  - React Input Components - Form inputs
  - React Rich Text Editor - Content editor
  - React Dropdowns & Popups - UI components

### Styling & Utilities
- **Tailwind CSS** (v3.0.19) - Utility-first CSS framework
- **React Icons** (v4.3.1) - Icon library
- **PostCSS** (v8.4.6) - CSS processing

### Development Tools
- **React Scripts** (v5.0.0) - Create React App build scripts
- **ESLint** (v8.9.0) - Code quality and linting
- **Autoprefixer** (v10.4.2) - CSS vendor prefixing

## 🛠️ Installation

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Setup

1. Clone the repository:
```bash
git clone https://github.com/nishant4086/Dashbord.git
cd Dashbord
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

The application will open at `http://localhost:3000`

## 📦 Available Scripts

### `npm start`
Runs the app in development mode. Opens [http://localhost:3000](http://localhost:3000) to view it in your browser.

### `npm build`
Builds the app for production to the `build` folder.

### `npm test`
Launches the test runner in interactive watch mode.

### `npm eject`
Ejects from Create React App configuration (one-way operation).

## 📂 Project Structure

```
src/
├── components/          # Reusable React components
│   ├── Charts/         # Chart components
│   ├── Navbar.jsx      # Navigation bar
│   ├── Sidebar.jsx     # Side navigation
│   ├── ThemeSettings.jsx# Theme configuration
│   └── ...             # Other UI components
├── pages/              # Page components
│   ├── Charts/         # Chart pages
│   ├── Ecommerce.jsx   # Dashboard home
│   ├── Orders.jsx      # Orders page
│   ├── Employees.jsx   # Employees page
│   └── ...             # Other pages
├── contexts/           # React Context for state management
├── data/               # Mock data and utilities
├── App.js              # Main app component
└── index.js            # App entry point
```

## 🎨 Key Pages

- **Dashboard** - Overview and statistics
- **Orders** - Order management interface
- **Employees** - Employee database
- **Customers** - Customer management
- **Calendar** - Event scheduling
- **Kanban** - Task board
- **Editor** - Rich text editor
- **Charts** - Data visualization dashboard
- **Color Picker** - Color selection tool

## 🔧 Configuration

- **Tailwind CSS** - Configured in `tailwind.config.js`
- **Craco Config** - Build customization in `craco.config.js`
- **ESLint Rules** - Code quality settings in `.eslintrc.js`

## 📄 License

Check the `license.txt` file for licensing details.

## 👨‍💻 Developer

**Nishant** - Full-stack developer

For questions or support, please refer to the project documentation or contact the developer.

---

**Repository:** [GitHub - Dashbord](https://github.com/nishant4086/Dashbord)
