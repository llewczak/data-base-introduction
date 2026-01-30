## Manufacturing & Sales Management System
A comprehensive MS SQL Server database solution designed to streamline production planning, sales operations, and warehouse management.
## 🚀 Key Features
- Production Management: Automated scheduling, Bill of Materials (BOM) tracking, and real-time production status monitoring.
- Inventory Control: Management of raw components and finished products, including low-stock alerts and automated reservation systems.
- Sales & Logistics: Full order lifecycle management for both individual customers and companies, including shipping and automated pricing.
- Financial Reporting: Built-in views for VAT accounting, sales performance, production costs, and quarterly spending analysis.
- Role-Based Security: Pre-defined database roles (Management, Sales, Production, Warehouse) and employee hierarchy management.
## 📂 Project Structure
- Database Script: The full SQL script to generate the schema, roles, views, and stored procedures is located at ```db/script.sql```.
- Technical Documentation: For a detailed description of the data model, table relationships, and business logic, please refer to ```db/documentation.pdf```.
## 🛠 Tech Stack
- Database Engine: Microsoft SQL Server
- Language: T-SQL (Stored Procedures, Triggers, Views, Indexes)
## 🏁 Getting Started
- Connect to your SQL Server instance.
- Run the script located in ```db/script.sql``` to initialize the database structure.
- Use the included stored procedures (prefixed with usp_) to manage customers, products, and production cycles.
## 🎓 Academic Context
This project was developed for the **Fundamentals of Databases** course at AGH UST. The primary objective was to design a normalized relational database and implement complex business logic directly within the database engine using advanced T-SQL features.
## 👥 Authors
This system was designed and implemented by:
- [Kamil Gieras](https://github.com)
- [Stanisław Wawrylak](https://github.com)
- [Łukasz Lewczak](https://github.com/llewczak)
