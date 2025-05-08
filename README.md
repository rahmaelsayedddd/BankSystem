# BankSystem(May 2022)

A desktop application for managing a multi-bank system simulating real-world banking operations, including customer management, loan processing, account handling, and employee administration.

## 🛠️ Technologies Used

- **C# & .NET** – Backend logic and business rules
- **Windows Forms** – Desktop user interface
- **SQL Server** – Relational database for data storage and queries

## 🧱 System Overview

- **Banks**: Each bank has a unique name, code, and address.
- **Branches**: A bank can have multiple branches, each with its own address and branch number.
- **Customers**: Each branch serves multiple customers. Customers have SSN, name, phone, and address.
- **Accounts**: A customer may have multiple accounts. Each account stores an account number, type, and balance.
- **Loans**: Branches offer different types of loans (industry, commercial, personal). Each loan has a number, type, and amount.
- **Employees**: Responsible for managing customers and loans.

## 🔧 Key Features

### 👥 User Management
- Sign up new users (customers or employees)
- Update existing user details

### 🏦 Bank & Branch Management (Admin)
- Add a new bank
- Add branches to existing banks

### 👤 Customer Management (Employee)
- Add new customers
- View list of customers

### 💰 Loan Management
- View available loan types (industry, commercial, personal)
- View list of loans with customer and employee names
- **Customer actions**: request a loan, start a loan
- **Employee actions**: accept, reject, and process loan payments

## 📊 SQL Queries Included

- **Query A**: Branches with no customers  
- **Query B**: Branches with no employees  
- **Query C**: Employee who added the highest number of loans  
- **Query D**: Customer(s) with the most loans  
- **Query E**: Customers who did not take any loans  
- **Query F**: Each customer’s details and the number of employees they dealt with
