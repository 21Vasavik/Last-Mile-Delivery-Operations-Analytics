# Last-Mile Delivery Operations Analytics

## 📌 Project Overview

**Last-Mile Delivery Operations Analytics** is a MySQL-based business analytics project developed for **QuickRoute Logistics**, a last-mile delivery company.

The project analyzes delivery demand, customer ordering behavior, delivery performance, driver and vehicle utilization, and operational problems to provide data-driven recommendations for improving delivery planning and operational efficiency.

## 🎯 Business Objectives

The analysis focuses on five major business objectives:

1. **Understand Delivery Demand**

   * Analyze order volume across delivery zones.
   * Compare demand across service types and priority levels.
   * Identify changes in order demand over time.

2. **Analyze Customer Order Behaviour**

   * Identify high-frequency customers.
   * Analyze customer order value.
   * Compare Business and Individual customers.

3. **Evaluate Delivery Performance**

   * Analyze delivery outcomes.
   * Compare delivery performance across zones.
   * Analyze delivery duration and distance.

4. **Understand Driver & Vehicle Performance**

   * Analyze driver workload and delivery performance.
   * Compare vehicle utilization.
   * Evaluate delivery duration across vehicle types.

5. **Identify Delivery Problems**

   * Analyze Failed, Pending and Rescheduled deliveries.
   * Identify multiple delivery attempts.
   * Investigate delivery problem areas.

## 🛠️ Tools & Technologies

* **MySQL**
* SQL
* MySQL Workbench
* ER Diagram
* Relational Database Concepts

## 🗄️ Database Structure

The project contains five main tables:

* `customers`
* `orders`
* `deliveries`
* `drivers`
* `vehicles`

### Relationships

```text
customers
    |
    | customer_id
    ↓
orders
    |
    | order_id
    ↓
deliveries
   / \
  /   \
 ↓     ↓
drivers vehicles
```

The database contains primary and foreign key relationships connecting customers, orders, deliveries, drivers and vehicles.

## 📊 Dataset Overview

| Table      | Records | Purpose                                             |
| ---------- | ------: | --------------------------------------------------- |
| Customers  |     400 | Customer details and customer type                  |
| Orders     |   3,000 | Order information, service type, priority and value |
| Deliveries |   3,500 | Delivery status, attempts, distance and duration    |
| Drivers    |      80 | Driver details, ratings and active status           |
| Vehicles   |      50 | Vehicle type, fuel type and capacity                |

## 🔍 SQL Analysis Performed

The project includes SQL analysis for:

* Total customers, orders and deliveries
* Service types
* Active drivers
* Order volume by delivery zone
* Order volume by service type
* Order volume by priority
* Order demand over time
* Top customers by order count
* Top customers by order value
* Business vs Individual customers
* Delivery outcomes
* Average delivery distance and duration
* Driver workload
* Driver delivery performance
* Vehicle utilization
* Vehicle performance
* Multiple delivery attempts
* Delivery problem statuses
* Problematic delivery zones
* Package weight vs delivery duration

## 📈 Key Findings

* **ZONE0005** recorded the highest order volume with **240 orders**.
* **Standard** service had the highest order volume with **620 orders**.
* **High-priority** orders represented the largest priority category with **1,035 orders**.
* Order demand increased from **608 orders in 2022 to 1,229 orders in 2024**.
* The highest-volume customer placed **19 orders**.
* **2,581 of 3,500 delivery records** were delivered.
* **ZONE0020** showed the weakest delivery performance.
* **165 delivery records** required multiple attempts, approximately **4.71%** of delivery records.
* **ZONE0019** had the highest multiple-attempt delivery rate.
* Cargo Bikes and Trucks handled high delivery volumes.
* Package weight did not show a strong relationship with delivery duration in the available dataset.

## 💡 Business Recommendations

Based on the analysis:

* Allocate additional resources to high-demand zones.
* Closely monitor **ZONE0005** because of its high order volume.
* Investigate delivery performance issues in **ZONE0020**.
* Review **Economy** service because of its weaker delivery outcomes.
* Monitor high-frequency and high-value customers.
* Balance driver workloads using delivery volume and performance.
* Optimize vehicle allocation according to delivery requirements.
* Investigate deliveries requiring multiple attempts.
* Monitor zones with high Failed, Pending and Rescheduled deliveries.
* Use delivery demand trends for future capacity planning.

## 📂 Project Files

### SQL

The `SQL` folder contains the complete MySQL project code, including:

* Database creation
* Table creation
* Primary and foreign keys
* Data validation
* Basic analysis
* Objective-based analysis
* Business findings
* Business recommendations

### Documentation

The `Documentation` folder contains the project presentation explaining the business scenario, database structure, analysis, findings and recommendations.

## 👩‍💻 Author

**Vasavi**

MCA | Aspiring Data Analyst

GitHub: https://github.com/21Vasavik

