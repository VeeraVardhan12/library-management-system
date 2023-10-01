# Library-Management-System
# Library Management System

Welcome to the Library Management System project! This system is designed to efficiently manage the operations of a library, allowing administrators to oversee various tasks and registered students to access and request books. Below, you will find an overview of the system's key features for both administrators and students.

## Features

### Admin

- **Add Book**: Administrators can easily add new books to the library catalog, including details such as title, author, ISBN, and availability status.
- **Add Category**: The system supports categorizing books into different categories or genres, helping users browse and locate books more effectively.
- **Add Publication**: Administrators can input publication information, including publisher name, publication date, and more.
- **Admin Dashboard**: Provides a centralized dashboard for administrators to monitor the library's activities and statistics.
- **Change Password**: Allows administrators to update their login credentials for enhanced security.
- **Issue Book**: Admins can facilitate the process of issuing books to registered students, keeping track of due dates.
- **Manage Books**: Comprehensive book management capabilities, including editing, updating, and removing book records.
- **Manage Categories**: Enables administrators to manage and maintain the library's categories and genres.
- **Manage Publications**: Provides tools to oversee and manage publication records.
- **Manage Requested Books**: Administrators can handle book requests from students, ensuring a smooth lending process.
- **Overdue Report**: Generates reports highlighting overdue books, assisting administrators in following up with students.
- **Registered Students**: Allows administrators to create and manage student accounts and set fine amounts for late returns.

### Student

- **Login**: Registered students can log in securely to access the library system.
- **Signup**: students can register via email
- **Request Book**: Students can browse the catalog and request books they wish to borrow.
- **Change Password**: Enables students to update their login credentials for security purposes.

## Getting Started

These instructions will guide you through setting up the Library Management System on your local machine for development and testing purposes. Before you begin, it's helpful to have a basic understanding of HTML, CSS, PHP, and MySQL. We'll be using the XAMPP server, which works well on various operating systems.

### Prerequisites

Before you start, make sure you have the following:

- **XAMPP Server**: We'll use XAMPP because it's cross-platform and eliminates operating system compatibility issues. You can download and install it from [this link](https://www.apachefriends.org/download.html).

### Setting up the Environment

Follow these steps to set up the environment:

1. **Download and Extract the Project**: First, download the project's source code and extract it to your local machine.

2. **Copy to htdocs**: Paste the extracted source code in the "htdocs" folder of your XAMPP installation. The default path for this folder is usually "C:\xampp\htdocs".

3. **Start Apache & MySQL**: Open the XAMPP Control Panel and start the Apache and MySQL services.

4. **Access phpMyAdmin**: Open your web browser and go to "http://localhost/phpmyadmin/". This should take you to the phpMyAdmin page, which is used for managing databases.

5. **Create a Database**: Create a new, empty database named "library". After creating it, select the "library" database and import the SQL file that comes with the source code. This file contains the necessary database structure and data.

6. **Review Configuration Files**: Inside the project's "includes" folders, there are configuration files. You should review these files and update the username and password settings to match your MySQL credentials.

7. **Access the Website**: In your web browser, go to "http://localhost/foldername-in-htdocs-directory/". This will take you to the login page of the Library Management System.

8. **Admin Login**: You can log in as an admin using the following credentials:
   - Username: admin
   - Password: admin

9. **User Login**: To log in as a regular user, use any credentials from the database. The password for all user accounts is set to "Test@123".

These steps should help you set up and run the Library Management System on your local machine.

