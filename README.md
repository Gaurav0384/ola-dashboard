# 🚕 OLA Dashboard: Ride Booking & Revenue Analytics

An interactive Power BI dashboard designed to analyze OLA ride-booking data, with a focus on booking performance, revenue, payment methods, vehicle types, booking status, and daily booking trends.

---

## 1. Project Title / Headline

### 🚕 OLA Ride Analytics: Booking, Revenue & Performance Dashboard

A dynamic and interactive Power BI dashboard built to explore OLA ride-booking data and provide insights into booking trends, revenue generation, cancellation patterns, payment methods, and vehicle-type performance.

---

## 2. Short Description / Purpose

The OLA Dashboard is a visually interactive Power BI report developed to analyze ride-booking performance for the selected period. The dashboard helps users understand total bookings, booking value, booking status, payment methods, vehicle-type demand, revenue distribution, and daily booking trends.

The main purpose of this dashboard is to transform raw ride-booking data into meaningful business insights that can support operational monitoring and data-driven decision-making.

---

## 3. Tech Stack

The dashboard was built using the following tools and technologies:

- 📊 **Power BI Desktop** – Main data visualization and dashboard development platform.
- 🔄 **Power Query** – Used for data cleaning, transformation, and preparation.
- 🧮 **DAX (Data Analysis Expressions)** – Used for calculated measures, KPIs, aggregations, and analytical calculations.
- 🗂️ **Data Modeling** – Used to organize and connect the data for effective analysis and filtering.
- 📁 **Microsoft Excel / CSV** – Used as the source format for the ride-booking dataset.
- 🖼️ **Power BI Visuals** – Used to represent booking, revenue, payment, vehicle, and trend-related insights.

---

## 4. Data Source

### Source: OLA Ride Booking Dataset

The dashboard is based on a structured OLA ride-booking dataset containing information about individual bookings and their associated attributes.

The dataset includes fields related to:

- Date
- Booking ID
- Booking Status
- Booking Value
- Customer ID
- Vehicle Type
- Payment Method
- Ride/Booking information

The data was cleaned and transformed before being used in Power BI to ensure accurate analysis and visualization.

---

## 5. Features / Highlights

### 🔹 Business Problem

Ride-hailing platforms generate large volumes of booking data every day. Without an effective analytical dashboard, it can be difficult to monitor booking performance, identify cancellation patterns, compare vehicle categories, and understand revenue trends.

The OLA Dashboard provides a centralized view of important business metrics to make this analysis easier and faster.

---

### 🔹 Goal of the Dashboard

The main goals of this dashboard are:

- Monitor overall booking performance.
- Analyze total booking value/revenue.
- Understand booking status distribution.
- Identify successful and cancelled bookings.
- Analyze bookings based on payment methods.
- Compare bookings across different vehicle types.
- Track daily booking trends.
- Provide an interactive platform for business analysis.

---

## 6. Dashboard KPIs

The dashboard provides important high-level KPIs such as:

### 💰 Total Booking Value

Displays the overall booking value generated during the selected date range.

### 🚕 Total Bookings

Shows the total number of bookings recorded in the dataset.

### 📅 Date Filter

Users can select a specific date range to dynamically filter all dashboard visuals.

---

## 7. Key Dashboard Visuals

### 📌 Booking Status Breakdown

A pie chart represents the distribution of bookings across different booking statuses, including:

- Success
- Cancelled by Driver
- Cancelled by Customer
- Driver Not Found

This visual helps identify the proportion of successful and unsuccessful bookings.

---

### 📌 Booking by Payment Method

A donut chart shows bookings according to different payment methods, such as:

- Cash
- UPI
- Credit Card
- Debit Card
- Other / Null values

This helps understand customer payment preferences.

---

### 📌 Bookings by Vehicle Type

A bar chart compares the number of bookings across different vehicle categories, including:

- Prime Sedan
- eBike
- Auto
- Prime Plus
- Bike
- Prime SUV
- Mini

This visual helps identify which vehicle categories receive the highest booking demand.

---

### 📌 Booking Revenue by Booking Status

A line chart displays booking value/revenue according to booking status.

It helps compare the financial contribution of:

- Successful bookings
- Cancelled bookings
- Driver-related cancellations
- Customer-related cancellations
- Other booking outcomes

---

### 📌 Daily Booking Trend

A line chart tracks the total number of bookings across individual days.

This allows users to identify:

- High-booking days
- Low-booking days
- Changes in demand
- Overall booking patterns during the selected period

---

## 8. Key Insights

The dashboard can be used to identify several important business insights:

- A large proportion of bookings are successfully completed.
- Booking cancellations can be analyzed separately based on whether they were initiated by customers or drivers.
- Different vehicle categories show different levels of customer demand.
- Payment-method analysis provides an overview of customer payment preferences.
- Daily booking trends help identify fluctuations in ride demand.
- Revenue can be compared across different booking statuses to understand the financial impact of cancellations.
- Interactive date filtering allows users to analyze specific periods rather than relying only on overall figures.

---

## 9. Business Impact

The dashboard can help OLA/business analysts with:

- 📈 **Performance Monitoring** – Track booking and revenue performance.
- 🚕 **Fleet Planning** – Understand demand for different vehicle categories.
- ❌ **Cancellation Analysis** – Identify booking cancellation patterns.
- 💳 **Payment Analysis** – Understand preferred payment methods.
- 📅 **Demand Analysis** – Monitor daily changes in booking volume.
- 💰 **Revenue Tracking** – Evaluate booking value across different statuses.
- 🎯 **Decision Making** – Support data-driven operational decisions.

---

## 10. Dashboard Navigation

The dashboard contains multiple analytical sections that allow users to explore different aspects of OLA's booking data.

### 🏠 Overall

Provides a high-level overview of:

- Total Booking Value
- Total Bookings
- Booking Status
- Payment Method
- Vehicle Type
- Revenue by Booking Status
- Daily Booking Trend

### 🚗 Vehicle Type

Provides deeper analysis of bookings across different vehicle categories.

### 💰 Revenue

Focuses on booking value and revenue-related performance.

### ❌ Cancellation

Helps analyze cancellation patterns and their impact on bookings.

### ⭐ Ratings

Can be used to analyze customer/driver rating-related information where available in the dataset.

---

## 11. Interactive Features

The dashboard provides interactive functionality through:

- 📅 Date range slicers
- 🔍 Visual-level filtering
- 📊 Interactive charts
- 🚕 Vehicle-type analysis
- 💳 Payment-method filtering
- 📈 Dynamic KPI calculations
- 🔄 Cross-filtering between visuals

Selecting a value in one visual automatically updates the related dashboard components.

---

## 12. Project Structure

```text
OLA-Dashboard/
│
├── README.md
│
├── Dashboard/
│   ├── OLA_Dashboard.pbix
│   └── Dashboard_Preview.png
│
├── Dataset/
│   └── OLA_Ride_Booking_Data.csv
│
├── Images/
│   └── OLA_Dashboard_Screenshot.png
│
└── Documentation/
    └── Project_Documentation.md
