# 🚖 OLA Data Analysis | Power BI Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-Data%20Analysis-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Data Analytics](https://img.shields.io/badge/Data%20Analytics-Dashboard-00A86B?style=for-the-badge)
![Status](https://img.shields.io/badge/Project-Completed-success?style=for-the-badge)

## 📊 Project Overview

**OLA Data Analysis** is an interactive **Power BI dashboard** designed to analyze ride-booking performance for OLA.

The dashboard provides a consolidated view of booking volume, booking status, revenue, vehicle performance, cancellations, distance travelled, and customer ratings. Users can filter the analysis by date and explore different business areas through the dashboard navigation.

The analysis covers the period **01 July 2024 to 30 July 2024**.

---

## 🎯 Project Objectives

The main objectives of this project are to:

- Analyze overall ride-booking performance.
- Understand successful and unsuccessful booking patterns.
- Compare different vehicle types.
- Analyze revenue by payment method.
- Identify major reasons for driver and customer cancellations.
- Track ride volume and distance travelled over time.
- Evaluate customer ratings across vehicle categories.
- Present business insights through an interactive dashboard.

---

## 🛠️ Tools & Technologies

| Tool / Technology | Purpose |
|---|---|
| **Power BI** | Dashboard development and data visualization |
| **Power Query** | Data cleaning and transformation |
| **DAX** | Measures and analytical calculations |
| **Microsoft Excel** | Data source / data preparation |
| **Data Visualization** | Business reporting and insight generation |

---

## 📌 Dashboard Pages

The report contains **5 analytical sections**:

### 1. Overall Performance

The Overall page provides a high-level summary of the business.

**Key metrics and visuals include:**
- Total Bookings
- Total Booking Value
- Booking Status Breakdown
- Ride Volume Over Time
- Date-based filtering

From the dashboard, the selected period shows approximately:

- **40,539 Total Bookings**
- **₹14M Total Booking Value**
- Successful bookings account for the largest share of bookings.

---

### 2. Vehicle Type Analysis

The Vehicle Type page compares performance across different vehicle categories.

**Vehicle categories include:**
- Prime Sedan
- Prime SUV
- Prime Plus
- Mini
- Auto
- Bike
- E-Bike

**Metrics analyzed:**
- Total Booking Count
- Total Booking Value
- Successful Booking Value
- Average Distance Travelled
- Total Distance Travelled

This page helps identify differences in booking activity, revenue contribution, and distance travelled across vehicle types.

---

### 3. Revenue Analysis

The Revenue page focuses on payment and distance-related performance.

**Analysis includes:**
- Revenue by Payment Method
- Distance Travelled by Date
- Customer-level booking value summary

The dashboard shows **Cash and UPI** as the major payment methods by booking value, with smaller contributions from credit and debit card payments.

---

### 4. Cancellation Analysis

The Cancellation page analyzes why rides are cancelled.

It separates cancellations into:

#### Driver Cancellations
Reasons include:
- Personal & Car related issue
- Customer-related issue
- Customer was coughing/sick
- More than permitted people in the vehicle

#### Customer Cancellations
Reasons include:
- Driver is not moving towards pickup
- Driver asked to cancel
- Change of plans
- AC is not working
- Wrong address

This analysis can help identify operational issues and potential areas for improving customer and driver experience.

---

### 5. Customer Ratings

The Ratings page analyzes customer ratings across vehicle types.

The dashboard shows an overall average customer rating of approximately **4.01**, with individual vehicle categories maintaining ratings close to 4.0.

This helps evaluate customer satisfaction across different vehicle categories.

---

## 📈 Key Dashboard Insights

Based on the dashboard:

- The analysis contains **40K+ ride bookings** during the selected period.
- Total booking value is approximately **₹14 million**.
- Successful bookings represent the largest portion of total bookings.
- **Cash** and **UPI** contribute the majority of booking value among payment methods.
- Vehicle categories show differences in booking volume, successful booking value, and distance travelled.
- Both driver-side and customer-side cancellations are broken down by specific reasons.
- Customer ratings remain around **4.0**, indicating generally strong customer satisfaction.
- Ride volume changes from day to day, allowing daily booking trends to be monitored.

---

## 🔄 Data Analysis Workflow

The project follows a typical business intelligence workflow:

```text
Raw Data
   ↓
Data Cleaning & Transformation
   ↓
Data Modeling
   ↓
DAX Measures
   ↓
Interactive Visualizations
   ↓
Business Insights
```

### Data Preparation

The data was prepared and transformed before visualization to make it suitable for analysis.

### Data Modeling

Relevant fields were organized to support analysis across:

- Booking information
- Vehicle type
- Payment method
- Booking status
- Cancellation reasons
- Distance travelled
- Customer ratings
- Date

### DAX & Measures

DAX-based calculations were used to generate analytical metrics such as:

- Total Bookings
- Total Booking Value
- Successful Booking Value
- Average Distance
- Total Distance
- Average Customer Rating
- Booking status analysis

---

## 📂 Repository Structure

```text
OLA_Data_Analysis/
│
├── olaPowerBI.pbix
├── README.md
└── dashboard_images/
    ├── overall.png
    ├── vehicle-type.png
    ├── revenue.png
    ├── cancellation.png
    └── ratings.png
```

> The `dashboard_images` folder is optional. Add the dashboard screenshots to this folder if you want them displayed directly on the GitHub README.

---

## 🖥️ Dashboard Preview

### Overall Performance
<img width="849" height="489" alt="Screenshot 2026-09-09 005257" src="https://github.com/user-attachments/assets/d5581779-e2a1-485f-a085-8721d2946b23" />


### Vehicle Type Analysis
<img width="843" height="475" alt="Screenshot 2026-09-09 005307" src="https://github.com/user-attachments/assets/67b3d971-bb96-4250-9604-2f8acf64603e" />

### Revenue Analysis
<img width="845" height="481" alt="Screenshot 2026-09-09 005316" src="https://github.com/user-attachments/assets/4c60c838-dcb2-4f4c-97f3-cb2996de9549" />


### Cancellation Analysis
<img width="848" height="485" alt="Screenshot 2026-09-09 005324" src="https://github.com/user-attachments/assets/40f3edad-2a9e-43f6-a5f5-ea393a17bb31" />



### Customer Ratings
<img width="855" height="477" alt="Screenshot 2026-09-09 005332" src="https://github.com/user-attachments/assets/483796f7-4498-41cc-95ff-1496b580f879" />



---

## 💡 Business Questions Answered

This dashboard can be used to answer questions such as:

1. How many rides were booked during the selected period?
2. What is the total booking value?
3. What percentage of rides were successful?
4. Which vehicle types generate the highest booking activity?
5. Which vehicle types have the highest successful booking value?
6. Which payment methods contribute the most revenue?
7. What are the major reasons for driver cancellations?
8. What are the major reasons for customer cancellations?
9. How does ride volume change over time?
10. What is the average customer rating across vehicle types?

---

## 🎓 Skills Demonstrated

This project demonstrates practical skills in:

- **Power BI**
- **Power Query**
- **DAX**
- **Data Cleaning**
- **Data Transformation**
- **Data Modeling**
- **KPI Development**
- **Data Visualization**
- **Business Analysis**
- **Interactive Dashboard Design**

---

## 👨‍💻 Author

**Sundram**

Aspiring Data Analyst

**Skills:** Power BI • SQL • Excel • Python • Data Analytics

---

## ⭐ Project

If you found this project useful or interesting, feel free to ⭐ the repository.

