# TaskManagementApp_Oritso# Task Management Application

## Overview
This is a Task Management application built using:
- Angular 16 (Frontend)
- .NET 7 Web API (Backend)
- SQL Server (SSMS) (Database)

The application demonstrates CRUD operations using MVC principles.

---

## Project Structure

TaskManagement_Assignment/
│
├── backend/        (.NET 7 Web API)
├── frontend/       (Angular 16 UI)
├── database/       (SQL scripts & ER diagram)
└── README.md

---

## Prerequisites

- Node.js v18+
- Angular CLI v16
- .NET SDK 7.0
- SQL Server + SSMS
- VS Code / Visual Studio

---

## Database Setup

1. Open SQL Server Management Studio
2. Run the script:
   database/TaskManagement.sql
3. Database Name: TaskManagementDB

---

## Backend Setup (.NET API)

1. Open backend project in Visual Studio
2. Update connection string in `appsettings.json`
3. Run the project
4. Swagger URL:
   https://localhost:5001/swagger

---

## Frontend Setup (Angular)

1. Open VS Code
2. Navigate to:
   frontend/task-management-ui
3. Install dependencies:
   npm install
4. Start application:
   ng serve
5. Open browser:
   http://localhost:4200

---

## Features Implemented

- Create Task
- View Tasks
- Update Task
- Delete Task
- Search Tasks
- MVC Pattern
- REST APIs
- Lazy Loading (Angular)

---

## Technologies Used

- Angular 16
- .NET Core 7
- SQL Server
- TypeScript
- Reactive Forms

---

## Author

Name: <Your Name>
