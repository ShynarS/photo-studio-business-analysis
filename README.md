# Photo Studio Business Analysis

## Project Overview

This project analyzes the operational and financial performance of a photo studio business.  
The goal is to identify revenue drivers, customer behavior patterns, underutilized booking hours, and opportunities to improve occupancy and profitability.

The analysis was performed using SQL, Power BI, and Excel.

---

## Business Problem

The studio management wants to:

- increase hall occupancy;
- reduce idle booking hours;
- identify the most profitable halls;
- understand customer retention;
- evaluate cancellation patterns;
- optimize marketing effectiveness.

---

## Dataset

The dataset contains simulated booking and customer data for a photo studio.

### Main table: `bookings`

| Column | Description |
|---|---|
| booking_id | Unique booking identifier |
| client_id | Unique client identifier |
| booking_date | Booking date |
| start_time | Session start time |
| duration_hours | Session duration |
| hall | Studio hall |
| revenue | Revenue from booking |
| source | Customer acquisition source |
| canceled | Booking cancellation status |

Dataset size:
- 5,000 bookings
- 1 year of operations
- Multiple halls and acquisition channels

---

## Tools Used

- SQL (PostgreSQL)
- Power BI
- Excel
- Python (Pandas)

---

## Analysis Performed

### SQL Analysis

Key business metrics calculated:

- Total revenue
- Occupancy rate
- Average booking value
- Cancellation rate
- Repeat customer rate
- Revenue by hall
- Peak booking hours
- Monthly seasonality trends

Example SQL tasks:
- GROUP BY analysis
- CTEs
- Window functions
- Retention analysis

---

## Dashboard

The Power BI dashboard includes:

- Revenue overview
- Booking trends
- Hall performance
- Peak hours analysis
- Customer retention
- Cancellation analysis
- Marketing source performance

---

## Key Insights

### Revenue Concentration
Approximately 68% of total revenue is generated after 5 PM, indicating strong evening demand.

### Underutilized Morning Slots
Morning sessions before 12 PM show low occupancy rates and represent a potential revenue opportunity.

### Customer Retention
Returning customers generate significantly higher average revenue compared to first-time visitors.

### Hall Performance
Studio Hall A consistently outperforms other halls in both occupancy and revenue.

### Cancellation Trends
Most cancellations occur within 24 hours before booking time.

---

## Recommendations

### Dynamic Pricing
Introduce discounted weekday morning sessions to increase occupancy during low-demand periods.

### Loyalty Program
Implement a retention strategy for repeat customers through discounts or membership packages.

### Marketing Optimization
Increase investment in acquisition channels with the highest customer conversion rates.

### Cancellation Policy
Test partial prepayment to reduce last-minute cancellations.

---

## Project Structure

```text
photo-studio-analysis/
│
├── data/
├── sql/
├── dashboard/
├── notebooks/
├── screenshots/
└── README.md
