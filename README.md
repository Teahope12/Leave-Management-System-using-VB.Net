# SML ELMS VB - Leave Management System

## Overview
SML ELMS VB is a Leave Management System designed to streamline and automate the process of managing employee leaves. This system helps organizations efficiently track, approve, and manage employee leave requests.

## Features
- Employee leave request management
- Leave approval workflow
- Leave balance tracking
- User authentication and authorization
- Database-driven architecture
- SQL-based data management

## Project Structure
```
SML ELMS VB/
├── alcala leave management/    # Main application directory
├── elms.sql                    # Database schema and queries
└── elms.txt                    # Project documentation
```

## Prerequisites
- Visual Basic (VB) development environment
- SQL Server or compatible database system
- Required VB dependencies and libraries

## Installation
1. Clone the repository:
   ```bash
   git clone [repository-url]
   ```
2. Set up the database:
   - Import the `elms.sql` file into your database system
   - Configure database connection settings

3. Open the project in your VB development environment
4. Build and run the application

## Usage
### Running the Project
1. **Database Setup**
   - Open SQL Server Management Studio
   - Create a new database named 'elms'
   - Open and execute the `elms.sql` script from the project root
   - Verify that all tables and stored procedures are created successfully

2. **Project Setup**
   - Open Visual Studio
   - Open the solution file `alcala leave management.sln`
   - Right-click on the solution in Solution Explorer
   - Select "Restore NuGet Packages" to install required dependencies

3. **Configuration**
   - Open the project's configuration file
   - Update the database connection string with your SQL Server details:
     ```
     Server=YOUR_SERVER_NAME;Database=elms;Trusted_Connection=True;
     ```

4. **Running the Application**
   - Press F5 or click the "Start" button in Visual Studio
   - The application should launch with the login screen
   - Use the default credentials (if any) or create a new account

### Troubleshooting
- If you encounter database connection issues:
  - Verify SQL Server is running
  - Check the connection string in the configuration file
  - Ensure the database 'elms' exists and is accessible
