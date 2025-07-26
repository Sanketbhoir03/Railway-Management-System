# Railways Management System - VB.NET Windows Forms Application

## Overview

**Railways Management System** is a desktop-based application built using **Visual Basic .NET** and **Windows Forms** in Visual Studio. It simulates a basic railway booking and management system for both users and administrators.

This project is structured using multiple forms, each representing specific modules such as login, ticket booking, cancellations, data entry, and admin operations.

---

## Project Structure

- **Login System**: `Form2` manages user and admin login.
- **User Dashboard**: `Form4` allows users to book tickets, cancel, or view train details.
- **Admin Panel**: `Form5` provides access to add/update/delete railway data.
- **Forms 6–10**: Admin utilities such as train addition, user data form, station info, etc.
- **Forms 11–14**: User ticket booking and data collection.
- **Form16**: Ticket cancellation and refund messages.
- **Form17**: Reserved for future functionality or reports.
- `App.config`: Centralized configuration (e.g., DB connections).
- `*.Designer.vb` & `*.resx`: UI components and localization resources.
- `AssemblyInfo.vb`: Application metadata.

---

## Requirements

- **.NET Framework 4.x**
- **Visual Studio 2019 or later**
- **Windows OS**

---

## How to Run the Project

1. **Open Solution**: Open `WindowsApp13.sln` in Visual Studio.
2. **Build Project**: Use `Ctrl + Shift + B` or go to **Build > Build Solution**.
3. **Set Startup Form**: Right-click project > Properties > Application > Startup form (e.g., `Form2`).
4. **Run**: Press `F5` or click **Start Debugging**.

---

## Login Credentials

| Role    | Username | Password |
|---------|----------|----------|
| User    | *(Leave blank)* | *(Leave blank)* |
| Admin   | Admin    | 143      |

---

## Features

- User/Admin login system
- Ticket booking & passenger detail input
- Ticket cancellation with refund handling
- Admin dashboard for railway data management
- Clear/reset forms for easy reuse
- Modular UI with multiple forms and buttons
- Built fully in VB.NET for Windows platform

---

## Form Breakdown (Summary)

| Form      | Purpose                                          |
|-----------|--------------------------------------------------|
| `Form2`   | Login form for both user and admin               |
| `Form3`   | Data entry form for user information             |
| `Form4`   | User dashboard – book ticket, cancel, view info  |
| `Form5`   | Admin dashboard – manage backend functions       |
| `Form6-10`| Admin forms (train, station, passenger input)    |
| `Form11-14`| Booking and journey forms for users             |
| `Form16`  | Ticket cancellation with refund messages         |
| `Form17`  | Placeholder for future enhancements              |

---

## Deployment

1. Switch to **Release Mode** in Visual Studio.
2. Build the solution.
3. Locate the executable in `bin\Release\`.
4. Distribute `.exe` along with any required DLLs.

---

## Customization Ideas

- Connect forms to a **SQL Server** or **Access** database.
- Add **printable reports** for bookings.
- Implement **search** and **filter** features.
- Apply **user validation** and **session control**.
- Integrate **charts** or **data visualization** for train usage.

---

## Developed With

- Visual Basic .NET
- Windows Forms (WinForms)
- Visual Studio IDE

---

## License

This project is intended for educational use. Feel free to modify and expand upon it. If distributing, please add an appropriate license.

---

## Author

**Sanket Bhoir**  
B.E. Information Technology Engineering  
GitHub Profile : https://github.com/Sanketbhoir03

