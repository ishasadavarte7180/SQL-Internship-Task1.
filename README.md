# SQL Internship - Task 1

## 📌 Objective
The goal of this task is to design a relational database schema, create the tables using SQL, and represent the structure with an ER diagram.


## 🛠 Domain Chosen: E-commerce
I selected **E-commerce** as the domain. The schema covers the following:
**Customers** who purchase products
**Products** that are being sold
**Orders** placed by customers
**Order_Items** to handle multiple products in an order


## 📂 Project Files
- **README.md** → Explanation of the project 
- **schema.sql** → SQL script to create the database and tables  
- **ERD.png** → ER diagram of the database schema  
 


## 🗄 Database Schema

### **1. Customers**
- `CustomerID` (PK)  
- Name  
- Email  
- Phone  
- Address  

### **2. Products**
- `ProductID` (PK)  
- ProductName  
- Price  
- Stock  

### **3. Orders**
- `OrderID` (PK)  
- `CustomerID` (FK → Customers.CustomerID)  
- OrderDate  

### **4. Order_Items**
- `OrderItemID` (PK)  
- `OrderID` (FK → Orders.OrderID)  
- `ProductID` (FK → Products.ProductID)  
- Quantity  


## 📊 ER Diagram
Below is the Entity–Relationship Diagram showing how the tables are connected:

[ER_Diagram.png](https://github.com/ishasadavarte7180/SQL-Internship-Task1./blob/84b1968f5a3feeb7c08e89240cdf6c18beee9322/ER_Diagram.png)


## 📜 SQL Script

schema.sql → SQL script to create schema (https://github.com/ishasadavarte7180/SQL-Internship-Task1./blob/7f38d92f6c18edf86cb9b38157ecf3299697d4b5/Schema.sql)


   


