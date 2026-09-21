# 🚖 OLA Data Analytics Project — SQL + Power BI

An end-to-end **Data Analytics project** using OLA ride-booking data.  
The project combines **Excel, MySQL/SQL, and Power BI** to analyze ride volume, booking outcomes, vehicle performance, revenue, cancellations, ride distance, and customer/driver ratings.

## 👤 Author
**Avadhesh Kumar Rathaur**  
B.Tech — Computer Science

---
## 🎥 Dashboard Demo

https://github.com/user-attachments/assets/10702493-0cce-4e39-83f4-f462d10010f3

---

## 🧰 Tools & Technologies

- **Microsoft Excel** — dataset inspection and source data
- **MySQL 8.0 / MySQL Workbench** — SQL analysis and reusable views
- **Microsoft Power BI** — interactive dashboard and visualization
- **GitHub** — project versioning and portfolio documentation

---

## 📊 Dataset

Verified dataset summary:

- **103,024 booking records**
- **20 columns**
- **94,544 unique customers**
- **7 vehicle types**
- Date range: **1 July 2024 – 31 July 2024**
- Successful bookings: **63,967**
- Successful booking rate: **62.09%**
- Total booking value from successful rides: **₹35,080,467**
- Average ride distance: **14.19**

See `docs/data_dictionary.csv` for the complete column reference.

---

## 🧠 SQL Analysis

The SQL analysis covers 10 business questions:

1. Retrieve all successful bookings
2. Find average ride distance for each vehicle type
3. Count customer-cancelled rides
4. Identify the top 5 customers by number of rides
5. Count driver cancellations caused by personal/car-related issues
6. Find maximum and minimum driver ratings for Prime Sedan
7. Retrieve rides paid through UPI
8. Find average customer rating by vehicle type
9. Calculate total booking value of successful rides
10. List incomplete rides with their reasons

Below is the SQL analysis file:
[ola analysis SQL.sql](https://github.com/user-attachments/files/32450195/ola.analysis.SQL.sql)
---

## 📈 Power BI Dashboard

File: `powerbi/OLA_Data_Analytics.pbix`

The dashboard is organized around:

- **Overall** — ride Volume Over Time and Booking Status Breakdown
- **Vehicle Type** — key analysis by vehicle type
- **Revenue** — revenue by Payment Method, top 5 Customers by Total Booking Value & ride Distance Distribution Per Day
- **Cancellation** — cancelled Rides Reasons (Customer) & cancelled Rides Reasons(Drivers)
- **Ratings** — driver/customer rating analysis

The dashboard is designed to turn raw booking records into operational and business insights.

---

## 📑 Project Presentation

`media/OLA_Data_Analytics_Project_Presentation.pptx`

The presentation summarizes:

- Project objective
- Dataset
- Technology stack
- SQL analysis
- Power BI dashboard
- Key findings
- Portfolio deliverables

---

## ▶️ How to Use

### 1. Excel
Open:

```text
data/Bookings.xlsx
```

### 2. MySQL
Create the database and import the dataset into a table named `bookings`.

Then run:

```sql
USE ola;
```

Open and execute:

```text
sql/ola_analysis.sql
```

### 3. Power BI
Open:

```text
powerbi/OLA_Data_Analytics.pbix
```

If Power BI requests a source refresh, reconnect the dataset according to your local file/database setup.

---

## 📌 Resume Description

**OLA Data Analytics Dashboard | Excel, SQL, Power BI**

- Analyzed **103,024 OLA ride-booking records** using Excel and MySQL to study booking trends, cancellations, revenue, ride distance, and ratings.
- Developed SQL views and queries for successful bookings, customer/driver cancellations, top customers, UPI payments, vehicle performance, and incomplete rides.
- Built an interactive Power BI dashboard covering ride volume, booking status, vehicle type, revenue, cancellations, and customer/driver ratings.

---

## 📁 Portfolio Deliverables

- [x] Excel source dataset
- [x] Power BI dashboard
- [x] SQL analysis queries
- [x] Data dictionary
- [x] Dashboard demo video
- [x] Project presentation
- [x] GitHub-ready README

---

## ⚠️ Note

This repository is intended as a portfolio/learning project. Before publishing publicly, make sure the source dataset is permitted for redistribution and does not contain confidential or personally identifiable information.

---

**Built by Avadhesh Kumar Rathaur**
