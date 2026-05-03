# Travel, Tourism & Hospitality – Customer Retention and Dynamic Pricing Analysis

## Project Overview

This project focuses on solving two major problems in the hospitality industry:

1. High booking cancellation rates  
2. Unoptimized pricing strategies leading to revenue loss

Using historical hotel booking data, the project analyzes customer cancellation behavior, pricing trends, and seasonal demand patterns to support better customer retention and dynamic pricing decisions.

The final output includes data cleaning, exploratory data analysis (EDA), predictive modeling, and an interactive dashboard for business decision-making.

---

## Dataset Description

Dataset Used: Hotel Booking Demand Dataset

The dataset contains historical booking records for:

- City Hotels
- Resort Hotels

Important columns include:

- hotel
- is_canceled
- lead_time
- arrival_date_year
- arrival_date_month
- stays_in_weekend_nights
- stays_in_week_nights
- adults
- children
- babies
- market_segment
- deposit_type
- customer_type
- adr (Average Daily Rate)
- reservation_status

Additional engineered features created:

- total_stay
- total_guests
- arrival_date

---

## Tools and Technologies Used

- Python (Pandas, NumPy)
- Matplotlib
- Seaborn
- Scikit-Learn
- Tableau / Power BI
- Jupyter Notebook
- GitHub

---

## Project Workflow

### Week 1 – Data Cleaning and Feature Engineering

- Handled missing values
- Removed duplicates
- Treated ADR outliers
- Created new features:
  - total_stay
  - total_guests
  - arrival_date

---

### Week 2 – Exploratory Data Analysis (EDA)

Performed analysis on:

- Cancellation distribution
- ADR vs cancellation
- Lead time vs booking behavior
- Hotel type comparison
- Market segment analysis
- Deposit type impact
- Customer segmentation
- Seasonality trends
- Booking curve analysis
- Correlation heatmap

---

### Week 3 – Predictive Modeling

Built machine learning models to predict booking cancellations.

Models used:

- Logistic Regression
- Random Forest

Evaluation metrics:

- Accuracy
- Precision
- Recall
- Confusion Matrix
- ROC-AUC Score

Random Forest achieved the best performance with strong prediction accuracy.

---

### Week 4 – Dashboard Development

Created an interactive dashboard for:

- Dynamic Pricing Analysis
- Revenue Optimization
- ADR Trends
- Pricing vs Demand
- Pricing vs Cancellation Behavior
- Revenue by Customer Segment
- Hotel Type Comparison

---

## Key Dashboard Findings

### 1. Online Travel Agency (OTA) segment generates the highest revenue

The Online TA segment contributes the highest overall revenue, making it the most important customer channel for pricing optimization.

---

### 2. City Hotels have higher ADR compared to Resort Hotels

City Hotels show stronger pricing power and higher average daily rates, indicating stronger urban demand.

---

### 3. Higher ADR improves revenue but may increase cancellations

Aggressive pricing strategies increase revenue, but very high ADR can also increase cancellation risk for price-sensitive customers.

---

### 4. Seasonal demand strongly affects pricing

ADR trends show clear fluctuations across different time periods, confirming the need for dynamic pricing rather than fixed pricing.

---

### 5. Revenue optimization requires balancing demand and pricing

Higher pricing does not always lead to higher booking volume. Hotels must balance occupancy and room pricing carefully.

---

## Strategic Recommendations

### 1. Promote Non-Refundable Deposit Options

This reduces cancellation rates and improves revenue stability.

---

### 2. Apply Dynamic Pricing During Peak Seasons

Use seasonal demand trends to optimize ADR and improve RevPAR.

---

### 3. Focus Retention Campaigns on High-Risk Segments

Especially OTA users and transient customers who show higher cancellation behavior.

---

### 4. Build Loyalty Programs for Repeat Guests

Repeat guests show lower cancellation rates and higher retention value.

---

### 5. Use Lead Time as an Early Warning Signal

Customers with long booking lead times are more likely to cancel and should be targeted early.

---

## Setup Instructions

### Step 1: Clone the Repository

```bash
git clone https://github.com/Jerolin911/Travel-Tourism-Hospitality-Customer-Retention-Analysis-Dynamic-Pricing
