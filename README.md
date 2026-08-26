# Last-Mile Delivery Operations Analytics

## 📌 Project Overview

This is a **MySQL-based Business Analytics project** focused on analyzing last-mile delivery operations for QuickRoute Logistics.

The project analyzes delivery demand, customer ordering behavior, delivery performance, driver and vehicle utilization, and operational problems to generate data-driven business insights.

## 🎯 Business Objectives

* Understand delivery demand across different zones.
* Analyze customer order behavior and high-value customers.
* Evaluate delivery performance across zones and service types.
* Analyze driver workload and vehicle utilization.
* Identify failed, pending, rescheduled and repeated delivery attempts.

## 🛠️ Tools & Technologies

* MySQL
* SQL
* MySQL Workbench
* Relational Database Concepts
* ER Diagram

## 🗄️ Database Overview

The project contains five main tables:

| Table      | Records | Purpose                                             |
| ---------- | ------: | --------------------------------------------------- |
| Customers  |     400 | Customer details and customer type                  |
| Orders     |   3,000 | Order information, service type, priority and value |
| Deliveries |   3,500 | Delivery status, attempts, distance and duration    |
| Drivers    |      80 | Driver details, rating and active status            |
| Vehicles   |      50 | Vehicle type, fuel type and capacity                |

### Database Relationships

* Customers → Orders
* Orders → Deliveries
* Drivers → Deliveries
* Vehicles → Deliveries

## 🔍 SQL Analysis

The project includes analysis of:

* Total customers, orders and deliveries
* Orders by delivery zone
* Orders by service type
* Orders by priority
* Customer order frequency
* Customer order value
* Delivery success and problem rates
* Delivery duration and distance
* Driver workload and success rate
* Vehicle usage and performance
* Multiple delivery attempts
* Problematic delivery zones
* Delivery demand trends

## 📊 Key Findings

* **ZONE0005** recorded the highest demand with **240 orders**.
* **Standard** service recorded the highest order volume with **620 orders**.
* **High-priority** orders recorded the highest volume with **1,035 orders**.
* Order demand increased from **608 orders in 2022 to 1,229 orders in 2024**.
* **2,581 of 3,500 delivery records** were delivered.
* **ZONE0020** recorded the weakest delivery performance.
* **165 delivery records** required more than one attempt, approximately **4.71%** of delivery records.
* **ZONE0019** recorded the highest multiple-attempt rate.
* **75 of 80 drivers** were active.

## 💡 Business Recommendations

* Allocate more resources to high-demand delivery zones.
* Investigate performance issues in ZONE0020.
* Review Economy service performance.
* Reduce multiple delivery attempts to improve operational efficiency.
* Optimize driver and vehicle allocation based on workload and performance.
* Monitor high-frequency customers to support customer retention.
* Use growing order demand for future capacity planning.

## 📂 Project Files

### SQL Project

`SQL_Project_Code.sql` contains the MySQL database and analytical queries used in the project.

### Project Presentation

`SQL_Final_PPT.pptx` contains the project presentation, database structure, analysis, findings and recommendations.

## 👩‍💻 Author

**Vasavi**

MCA | Aspiring Data Analyst

GitHub: [21Vasavik](https://github.com/21Vasavik)
