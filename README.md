# Learning Management System

## Introduction

This is a simple Java-based project which aims to build a streamlined, user-friendly Online Learning Management System (LMS) tailored to the needs of small institutions and individual instructors. The project demonstrates how to set up a website of the same while using JDBC for the necessary database connectivity. 

---

## Table of Contents

1. [Requirements](#requirements)
2. [Project Setup](#project-setup)
3. [Database Setup](#database-setup)
4. [Project Structure](#project-structure)
5. [How to Run](#how-to-run)
6. [Future Improvements](#future-improvements)
7. [Troubleshooting](#troubleshooting)

---

## Requirements
To run this project, you'll need:

1. Java Development Kit (JDK) 8 or later - [Download here](https://www.oracle.com/in/java/technologies/downloads/)
2. MySQL Database Server - [Download here](https://www.mysql.com/downloads/)
3. Java IDE (such as IntelliJ, Eclipse, or NetBeans)

## Project Setup

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/BankManagementSystem.git
   cd BankManagementSystem
   ```

2. **Set Up JDK**

   - Install the JDK following the instructions on the Oracle website.
   - Configure the JDK path in your IDE:
     - In **IntelliJ IDEA**: Go to `File > Project Structure > Project SDK` and set it to your JDK location.
     - In **Eclipse**: Go to `Window > Preferences > Java > Installed JREs` and add the JDK location if needed.

3. **Open Project in IDE**

   - Open the project folder in your chosen IDE.

---

## Database Setup

### Step 1: Install and Configure MySQL

- Download and install MySQL from [here](https://dev.mysql.com/downloads/installer/).
- Set up a root user with a secure password.
- Open the MySQL command line or use a GUI like **MySQL Workbench**.

### Step 2: Create the Database and Tables

1. **Login to MySQL**:

   ```bash
   mysql -u root -p
   ```

2. **Run the SQL Commands to Create Database and Tables**:








- **User Management**: Admins can create, update, and delete user accounts.
- **Course Management**: Instructors can easily create and manage their courses.
- **Enrollment Management**: Students can enroll in available courses.
- **Intuitive Interface**: Simple navigation and minimal design to avoid unnecessary complexity.

## Target Users
- **Administrators**: Manage users and oversee system operations.
- **Instructors**: Create and manage courses.
- **Students**: Enroll in and track their courses.

## Technical Stack
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Java with JDBC (Java Database Connector) for MySQL integration
- **Database**: MySQL
- **Development Tools**: Visual Studio Code (IDE), Git (Version Control)

## Current Status
The initial development includes:
- **Login Page Prototype**: Created using HTML, CSS, and JavaScript as a foundational framework, stored in the project’s GitHub repository.
- **Database Setup**: MySQL database setup has been initiated.
- **Site Flowchart**: A functional flowchart outlines the site's navigation for each user type (Admin, Instructor, Student).

## Future Plans
We plan to expand the system with additional features based on user feedback and project requirements. These may include enhanced course management tools, performance tracking, and expanded user settings.

## Project Members and Contributions
- **Hysha Singh Dadwal**: Database management, presentation creation
- **Mehak Rana**: Webpage design, programming
- **Vived Singh**: Website styling, feature design
- **Yuvika Pundir**: Project management, team coordination

## Repository Link
[GitHub Repository for LMS Project](https://github.com/HyshaDadwal/LMS-Project-GUVI.git)

## Getting Started
1. Clone the repository:  
   ```bash
   git clone https://github.com/HyshaDadwal/LMS-Project-GUVI.git
