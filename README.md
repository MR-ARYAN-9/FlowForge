# FlowForge-Unified Project & Financial Workflow Platform

Video link Demo -> https://drive.google.com/file/d/1RdwZopqAYFvZXHeUBH6FPrNBu3QM7ghb/view?usp=sharing


A comprehensive project and task management platform with integrated financial tracking, timesheet management, and team collaboration features.

## 📋 Overview

FlowForge is a full-stack web application designed to streamline project management workflows. It provides teams with powerful tools to manage projects, track tasks, monitor time, handle approvals, and manage financial aspects including expenses, invoices, and purchase orders.

## ✨ Features

### Core Functionality
- **Project Management**: Create, organize, and track multiple projects
- **Task Management**: Assign tasks, set priorities, track progress, and manage dependencies
- **Team Collaboration**: Add team members, assign roles, and manage permissions
- **Timesheet Tracking**: Log work hours and track time spent on tasks and projects
- **Dashboard & Reports**: View quick stats, project insights, and generate reports

### Authentication & Security
- User registration and login with secure authentication
- Admin dashboard for user management
- Role-based access control
- Pending user approval system

### Financial Management
- **Expenses**: Track and manage project expenses
- **Invoices**: Create and manage invoices
- **Sales Orders**: Handle sales order processing
- **Purchase Orders**: Manage procurement and purchase orders
- **Production Tracking**: Monitor production-related financials

## 🛠️ Technology Stack

### Frontend
- **React** with TypeScript
- **Tailwind CSS** for styling
- Modern component-based architecture
- Responsive design

### Backend
- **Node.js** with Express
- RESTful API architecture
- MySQL database
- JWT-based authentication

## 📁 Project Structure

```
OneFlow/
├── src/                    # Frontend React application
│   ├── components/        # React components
│   ├── services/          # API services
│   ├── styles/           # CSS stylesheets
│   └── types/            # TypeScript type definitions
├── server/                # Backend Node.js application
│   └── src/
│       ├── controllers/  # API controllers
│       ├── routes/       # API routes
│       ├── middleware/   # Express middleware
│       ├── db/          # Database scripts
│       └── config/      # Configuration files
└── public/               # Static files
```

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- MySQL database
- npm or yarn package manager

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/oneflow.git
cd oneflow
```

2. Install frontend dependencies:
```bash
npm install
```

3. Install backend dependencies:
```bash
cd server
npm install
cd ..
```

4. Configure the database:
   - Create a MySQL database
   - Update database configuration in `server/src/config/db.js`
   - Run database migrations: `node server/src/db/init.js`

5. Start the backend server:
```bash
# Windows PowerShell
./start-backend.ps1

# Windows Command Prompt
start-backend.bat
```

6. Start the frontend development server:
```bash
npm start
```

7. Open your browser and navigate to `http://localhost:3000`

## 📝 Usage

1. **Registration**: Create a new account (requires admin approval)
2. **Login**: Access the platform with your credentials
3. **Projects**: Create and manage projects from the Projects page
4. **Tasks**: Add tasks to projects, assign team members, set deadlines
5. **Timesheets**: Log hours worked on tasks and projects
6. **Financial**: Manage expenses, invoices, and orders from the Financial menu
7. **Reports**: Generate insights and reports from the Reports section

## 🔒 Admin Features

Administrators have additional capabilities:
- Approve or reject pending user registrations
- Manage user roles and permissions
- Access admin dashboard for system overview
- Manage team members across all projects

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License.

## 📧 Contact

For questions or support, please open an issue on GitHub.

---

Built with ❤️ for better project management



