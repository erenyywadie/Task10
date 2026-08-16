# 📚 Stackly — Book Library Management System

> A web application built to make browsing and managing a library's collection simple and accessible online.

---

## 📖 Project Description

The Book Library System is a web application designed to make it easier for users to browse and manage books online.

Users can create an account, log in, explore the available books, and view detailed information about each title. Administrators are granted extended permissions to manage the book catalog and oversee registered users.

The goal of this project is to provide an organized, easy-to-use platform for running a digital library — from the reader's first search to the administrator's day-to-day catalog management.

---

## 👥 Target Users

The system is designed around two primary user roles:

### 🛡️ Admin
Responsible for managing the library and its data.

| Permissions |
|---|
| Add new books |
| View books |
| Edit book information |
| Delete books |
| Manage users |
| Access the admin dashboard |

### 👤 User
Can browse and interact with the available books.

| Permissions |
|---|
| Register and log in |
| View available books |
| View book details |
| Manage their profile |
| View their borrowing history |

---

## ✨ Main Features

### 🔐 Authentication
- User registration
- User login
- User logout
- Password protection
- User profile management

### 🛂 Authorization
Access is governed by role-based permissions:
- **Admin** — full access to management features
- **Regular Users** — access limited to browsing and profile features
- **Protected Features** — sensitive actions restricted to authorized roles only

### 🔄 CRUD Operations
The core resource in the system is the **Book**:

| Operation | Description |
|---|---|
| **Create** | Add a new book |
| **Read** | View all books · View book details |
| **Update** | Edit book information |
| **Delete** | Delete a book |

### 📕 Book Management
Each book record includes:

- Title
- Author
- Category
- Price
- Description
- Cover Image

### 🖼️ Image / File Upload

| Allowed Types | Max Size | Uploaded By |
|---|---|---|
| JPG, JPEG, PNG | 5 MB | Admin (when adding or editing a book) |

---

## 🗺️ Main Pages

1. Login Page
2. Register Page
3. Home / Books Page
4. Book Details Page
5. Admin Dashboard
6. Add Book Page
7. Edit Book Page
8. User Profile Page

---

## 🎨 UI Design

The interface design was created in Canva and covers the system's main screens — sign in, register, the books page, book details, the admin dashboard, the add/edit book pages, and the user profile.

**Canva Design:** [View UI Design](https://canva.link/6juu9576kwy8vn0)

---

## 🏗️ Project Structure
