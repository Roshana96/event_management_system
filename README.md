# event_management_system
A C# Windows Forms application for managing events, registrations, and user authentication with a simple, user-friendly interface.

# Colombo Event Management System (CEM)

## Project Overview
A Windows-based Event Management System developed for the Colombo Event Management (CEM) organization to streamline event planning, customer management, participant registration, and quotation generation.

### The system supports three user roles:

- Administrator – Manages user accounts (create, update, delete)

- Manager – Handles customer details, event information, quotations

- User – Views event and customer records (read-only)

### Technologies Used
- Frontend: Windows Forms (C#)

- Backend: .NET Framework

- Database: SQL Server

- IDE: Visual Studio 2015+

- Testing: Black Box & White Box Testing

- Deployment: ClickOnce Deployment (via Visual Studio)
--- 
## Installation & Setup
### 1. Prerequisites

- Windows OS

- Visual Studio 2015 or later

- SQL Server (Express or higher)

- .NET Framework 4.5+

### 2. Database Setup

 - Restore the provided database backup (CEM_DB.bak) in SQL Server.

 - Update the connection string in App.config:
```bash
<connectionStrings>
    <add name="MyConnection" 
         connectionString="Data Source=YourServer;Initial Catalog=CEM_DB;Integrated Security=True" />
</connectionStrings>
```
### 3. Build & Run
* Open WindowsFormsApplication1.sln in Visual Studio.

* Restore NuGet packages if prompted.

* Build the solution (Ctrl+Shift+B).

* Run the project (F5).

### User Roles & Features
####  Administrator
* Register new users (Admin, Manager, User)

 * Update/delete existing users

* Manage user credentials and permissions

### Manager
* Add/update/delete customer details

* Create/edit events and assign packages

* Generate and manage quotations

* Search and filter records

### User
* View customer and event records

* No modification rights

## Testing
* Black Box Testing – Functional validation (32 test cases included)

* White Box Testing – Code-level verification

* Test cases cover login validation, CRUD operations, and error handling.

##  Deployment
The application is deployed using ClickOnce Deployment:

1. Right-click project → Publish

2. Choose location (local folder, network, FTP)

3. Configure updates (optional)

4. Generate setup files (setup.exe, .application)

Thank you!

#### [author]: Roshana Atapattu 
#### [e-mail]: (roshana96.atapattu@gmail.com)
