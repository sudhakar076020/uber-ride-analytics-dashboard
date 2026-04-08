# 🚗 Uber Ride Analytics Dashboard (Tableau)

## 📊 Live Dashboard
🔗 https://public.tableau.com/views/Uber_Ride_Analytics_Dashboard/HomePage?:language=en-GB&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

---

## 📌 Project Overview
This project presents an interactive Tableau dashboard analyzing ride booking data to uncover insights related to performance, demand patterns, and cancellations.

The solution includes a **multi-dashboard navigation system with a home page**, providing a structured and user-friendly experience.

---

## 🎯 Objectives
- Analyze overall ride performance and revenue
- Identify peak demand hours and high-demand locations
- Understand ride patterns across vehicle types
- Analyze cancellation behavior of customers and drivers

---

## 📁 Dataset
- 150,000 ride records
- Features include:
  - Date & Time
  - Booking Status
  - Vehicle Type
  - Pickup & Drop Locations
  - Ride Distance & Duration
  - Revenue (INR)
  - Ratings (Driver & Customer)
  - Payment Method

---

## 🧹 Data Preparation
- Removed columns with high null values
- Converted columns to appropriate data types
- Created calculated fields:
  - Hour, Day, Month
  - Revenue (INR)
  - Cancellation Type
  - Distance Category
  - Rating Categories
- Handled outliers without removal to preserve real-world patterns

---

## 📊 Dashboards

### 🔵 1. Ride Performance Overview
- Total Rides, Revenue, Avg Ratings (KPIs)
- Ride trends over time
- Booking status distribution
- Vehicle type demand
- Payment method usage

---

### 🟢 2. Ride Demand Analysis
- Peak demand hour identification
- Ride demand by hour (with highlight)
- Top pickup locations
- Revenue comparison (Weekday vs Weekend)
- Distance category distribution

---

### 🔴 3. Ride Cancellation Analysis
- Cancellation distribution (Customer vs Driver)
- Cancellation trends by hour
- Cancellation by vehicle type (highlighted)

---

## 🎨 Key Features
- Interactive filters (Month, Vehicle Type, Day Type)
- Dynamic KPI cards
- Top value highlighting using WINDOW_MAX()
- Consistent color themes across dashboards
- Home page navigation with buttons

---

## 🛠 Tools Used
- Tableau (Visualization)
- Python (Data Cleaning)
- Pandas

---

## 📈 Key Insights
- Peak ride demand occurs around **6 PM**
- UPI is the most used payment method
- Auto and Go Mini dominate ride demand
- Most rides are successfully completed
- Certain vehicles show higher cancellation rates

---

## 🚀 Conclusion
This project demonstrates end-to-end data analysis including data cleaning, feature engineering, dashboard design, and storytelling using Tableau.

---

## 🙌 Author
Sudhakar
