# 🛣️ Sri Lanka Highway Management System

A Java desktop application for managing Sri Lanka highway toll operations. Built with NetBeans and SQL Server.

## Tech Stack
- Java (NetBeans)
- SQL Server
- SQL Server Management Studio (SSMS)

## User Roles

| Role | Responsibilities |
|---|---|
| **Admin** | Manage users, manage vehicles, manage tolls, view accident reports, view other reports |
| **Cashier** | Record vehicle entrances and exits, calculate costs, collect payments, generate reports |

## Default Login Credentials

| Username | Password |
|---|---|
| admin | 1234 |
| cashier | 1234 |

## Project Structure
```
src/
 └── highway/
      ├── classes/   → All logic and model classes (OOP)
      └── app/       → All JFrame UI screens
Database/            → SQL database file
Resources/           → Project resources
SRS Document/        → System requirements document
dist/                → Runnable JAR file
```

## OOP Concepts
The system is built using Object Oriented Programming principles with a clear separation between logic classes and UI screens.

## Requirements
- Java JRE 8 or higher
- SQL Server Express
- SQL Server Management Studio (SSMS)

## Setup
1. Install Java JRE from https://www.java.com
2. Install SQL Server Express and SSMS
3. Open SSMS and connect to your local server
4. Click New Query
5. Go to File → Open → File
6. Select the .sql file from the Database folder
7. Press F5 to execute — database will be created automatically
8. Make sure SQL Server is running
9. Go to the dist folder
10. Double click Highway_Management_System.jar
11. App will launch! ✅

## Note
Make sure SQL Server service is running before launching the application. You can check this in Windows Services or SQL Server Configuration Manager.
