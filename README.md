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
- **7 vehicle types**
- Date range: **1 July 2024 – 31 July 2024**

See [bookings.xlsx](https://github.com/user-attachments/files/32450361/bookings.xlsx) for the complete column reference.

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

This is the SQL analysis file 📑:
[ola SQL.sql](https://github.com/user-attachments/files/32450837/ola.SQL.sql)
---

## 📈 Power BI Dashboard


The dashboard is organized around:

- **Overall** — ride Volume Over Time and Booking Status Breakdown
- **Vehicle Type** — key analysis by vehicle type
- **Revenue** — revenue by Payment Method, top 5 Customers by Total Booking Value & ride Distance Distribution Per Day
- **Cancellation** — cancelled Rides Reasons (Customer) & cancelled Rides Reasons(Drivers)
- **Ratings** — driver/customer rating analysis

The dashboard is designed to turn raw booking records into operational and business insights.

---


## 📑Powerpoint Slides that i used

Slide 1 :
<img width="1280" height="720" alt="Image" src="https://github.com/user-attachments/assets/1eb01a43-c3a1-4ce4-a268-c44e1bf97689" />

Slide 2:
<img width="1280" height="720" alt="Image" src="https://github.com/user-attachments/assets/75386503-f0bd-4951-b440-d8fd3f17f187" />

Slide 3 :
<img width="1280" height="720" alt="Image" src="https://github.com/user-attachments/assets/18ee0f57-c318-458b-944a-e901ffb7f9dc" />

Slide 4:
<img width="1280" height="720" alt="Image" src="https://github.com/user-attachments/assets/4b92bfe0-1732-44bf-8795-bfcb0522a013" />

Slide 5:
<img width="1280" height="720" alt="Image" src="https://github.com/user-attachments/assets/c5e3d5a3-c1f0-4473-899c-aa4f59f3f44e" />



## ▶️ How to Use

### 1. Excel
Open:


[bookings.xlsx](https://github.com/user-attachments/files/32450361/bookings.xlsx)


### 2. MySQL
Create the database and import the dataset into a table named `bookings`.

Then run:

```sql
USE ola;
```

Open and execute:


[ola SQL.sql](https://github.com/user-attachments/files/32450837/ola.SQL.sql)


### 3. Power BI
Open:

```text
OLA.pbix
```

If Power BI requests a source refresh, reconnect the dataset according to your local file/database setup.

---

## 📌 Resume Description

**OLA Data Analytics Dashboard | Excel, SQL, Power BI**

- Analyzed **103,024 OLA ride-booking records** using Excel and MySQL to study booking trends, cancellations, revenue, ride distance, and ratings.
- Developed SQL views and queries for successful bookings, customer/driver cancellations, top customers, UPI payments, vehicle performance, and incomplete rides.
- Built an interactive Power BI dashboard covering ride volume, booking status, vehicle type, revenue, cancellations, and customer/driver ratings.

---

**Built by Avadhesh Kumar Rathaur**
