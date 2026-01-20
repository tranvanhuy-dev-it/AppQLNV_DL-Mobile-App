# AppQLNV_DL

## Overview
AppQLNV_DL is a cross-platform mobile application built with **.NET MAUI**, designed to manage employees and job assignments efficiently.  
The application follows the **MVVM architecture** and communicates with a **RESTful API** to handle business logic and data processing.

The system supports both **employees** and **customers**, allowing managers to assign tasks to employees and enabling customers to place service requests directly through the app.

---

## Frontend (Mobile App)

The frontend is developed using **.NET MAUI** with the **MVVM pattern**, responsible for:
- User interface rendering
- User interaction handling
- Communication with backend APIs

---

## Features

### Authentication
- Login / Logout
- Role-based access (Admin / Employee / Customer)
- Persistent login using local storage

### Employee Management
- View employee list
- Search and filter employees
- Add / edit / delete employee information

### Job Assignment
- Create and manage job tasks
- Assign tasks to employees
- Track task status (Pending / In Progress / Completed)

### Customer Features
- Customer account registration and login
- View available services
- Place job requests directly through the app
- Track assigned jobs and job status

---

## Technologies
- **.NET MAUI**
- **XAML**
- **MVVM Pattern**
- **CommunityToolkit.Mvvm**
- **HttpClient**
- **RESTful API**

---
  
## Folder Structure
- Views/       
- ViewModels/   
- Models/      
