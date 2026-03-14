# 🎬 Film Rental Store Data Analysis (MySQL Project)

---

## 📌 Project Overview

- This project focuses on analyzing a **Film Rental Store database using MySQL** to extract meaningful business insights from rental transactions and customer activity.  
- The objective of this project is to use **SQL for data analysis** to understand customer behavior, rental trends, film popularity, and revenue performance.  
- By analyzing relational data from multiple tables, the project demonstrates how SQL can be used to support **business decision-making in the entertainment rental industry.**

---

## 🎯 Project Objectives

- Analyze **customer rental behavior**
- Identify **popular films and categories**
- Evaluate **store and staff performance**
- Track **revenue generation**
- Discover **business insights from transactional data**

---

## 🗄️ Database Description

The project uses a **relational database** representing a film rental business system.

The database contains several interconnected tables that store information about **films, customers, rentals, payments, and stores.**

### Key Tables

| Table | Description |
|------|-------------|
| film | Contains movie details such as title, release year, and rental rate |
| actor | Stores information about actors |
| category | Movie genres (Action, Comedy, Drama, etc.) |
| customer | Customer personal details |
| rental | Records of movie rentals |
| payment | Payment transactions |
| inventory | Movies available in store inventory |
| store | Store location details |
| staff | Employees working in stores |

These tables are connected using **primary keys and foreign keys**, allowing complex relational queries.

---

## 🛠️ Tools & Technologies Used

- MySQL  
- SQL  
- MySQL Workbench  
- Git  
- GitHub  

---

## 📊 SQL Analysis Performed

This project includes multiple SQL queries designed to answer business-related questions.

### 1️⃣ Customer Behavior Analysis

- Identify the **most active customers**
- Find customers with the **highest rental frequency**
- Analyze **customer spending patterns**

### 2️⃣ Film Performance Analysis

- Determine the **most rented films**
- Identify **top revenue generating movies**
- Analyze **film popularity by category**

### 3️⃣ Revenue Analysis

- Calculate **total revenue generated**
- Identify **top paying customers**
- Analyze **revenue by category**

### 4️⃣ Store Performance Analysis

- Compare **store rental activity**
- Measure **store revenue performance**
- Evaluate **staff rental transactions**

### 5️⃣ Rental Trends

- Identify **peak rental periods**
- Analyze **monthly rental trends**
- Find **high demand categories**

---

## 📈 Business Insights

Through SQL analysis, the project helps identify:

- **Most profitable films and categories**
- **High-value customers**
- **Rental demand trends**
- **Revenue distribution**
- **Store performance differences**

These insights can support **better marketing strategies, inventory planning, and customer engagement.**

---

---

## 🚀 How to Run the Project

### 1️⃣ Install Required Tools

- Install **MySQL Server**
- Install **MySQL Workbench**

### 2️⃣ Import Database Schema

Run the schema file to create all tables:

```sql
SOURCE Divya-schema.sql;
