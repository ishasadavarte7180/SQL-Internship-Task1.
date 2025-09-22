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

![ERD](ERD.png)

---

## 📜 SQL Script

schema.sql → SQL script to create schema

ERD.png → Entity Relationship Diagram
   


