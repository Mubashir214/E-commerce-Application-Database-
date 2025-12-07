📦 E-Commerce Application
Complete Windows Forms Application with 3-Tier Architecture & Oracle Database Integration

This project is the final deliverable for the E-Commerce Application. It includes a fully functional Windows Forms GUI, complete business logic tier, data access tier, and Oracle database integration with stored procedures. The system supports multiple user roles, secure access control, and complete CRUD operations for products, orders, inventory, and delivery tasks.

📁 Project Overview

The E-Commerce Application is built using a 3-Tier Architecture:

Presentation Layer: Windows Forms (C# .NET)

Business Logic Layer (BLL): Classes handling all e-commerce operations

Data Access Layer (DAL): Oracle database connection & stored procedures

The application is designed around role-based interfaces and provides a refined, responsive UI for all user types.

🎯 Objectives

Deliver a complete E-Commerce store with a polished GUI

Ensure role-specific workflows (Customer, Cashier, Manager, Inventory Staff, Delivery Personnel, Admin)

Implement all business operations (Products, Orders, Inventory, Delivery Management)

Integrate fully with Oracle Database using stored procedures

Provide complete CRUD functionality across all modules

Submit well-organized project structure including all source code and database scripts

🧩 Core Features
✔️ 1. Full-Scale GUI Development (Windows Forms)

Modern, consistent, and user-friendly UI across all roles

Dashboard and forms for each role:

Customer → Browse products, place orders

Cashier → Process payments, confirm orders

Manager → Manage inventory, update products

Inventory Staff → Stock control, update quantities

Delivery Personnel → Update delivery status

Admin → Manage users and system settings

Responsive design within Windows Forms for different screen sizes

✔️ 2. Business Logic Layer (2nd Tier)

Dedicated logic classes for:

Product Management

Order Management

Inventory Management

Delivery Tracking

Functions include:

AddProduct()

ProcessOrder()

UpdateInventory()

UpdateDeliveryStatus()

Role-Based Access Control ensures only authorized users can perform certain actions

✔️ 3. Data Access Layer (3rd Tier)

Oracle database connection class

CRUD operations using stored procedures

Procedure examples:

sp_AddProduct

sp_ProcessOrder

sp_UpdateInventory

Real-time updates between UI and DB

✔️ 4. Database Schema & Stored Procedures

Enhanced schema including:

Products

Orders

Order Details

Inventory

Users & Roles

Delivery Tracking

Enforced constraints:

Primary & foreign keys

Referencing tables

Data validation rules

Stored procedures for:

Product Management

Order Processing

Inventory Control

Delivery Updates
