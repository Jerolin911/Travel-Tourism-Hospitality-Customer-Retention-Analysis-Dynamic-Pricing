
---

# Travel, Tourism & Hospitality – Customer Retention and Dynamic Pricing Analysis

## Project Overview
This project focuses on solving two major problems in the hospitality industry:
*   High booking cancellation rates
*   Unoptimized pricing strategies leading to revenue loss

Using historical hotel booking data, the project analyzes customer cancellation behavior, pricing trends, and seasonal demand patterns to support better customer retention and dynamic pricing decisions. The final output includes data cleaning, exploratory data analysis (EDA), predictive modeling, and an interactive dashboard for business decision-making.

---

The project includes a comprehensive **Customer Retention & Loyalty Analysis** dashboard designed to track high-level performance metrics and behavioral trends.

### Key Visual Components:
*   **Executive KPI Cards:** Real-time tracking of the **Retention Rate (3.86%)**, total **Repeat Customer count (3,363)**, and **Repeat Revenue** generation.
*   **Customer Segmentation (Donut Chart):** Visualizes the massive gap between New ($96.14\%$) and Repeat ($3.86\%$) customers to highlight the growth potential in loyalty programs.
*   **Market Segment Analysis:** A deep dive into retention rates across different channels, showing that the **Corporate** and **Aviation** segments lead in loyalty.
*   **Geographic Retention Map:** A global mapping of customer types (Contract, Group, Transient) across North America, Europe, and Asia to identify regional loyalty hotspots.
*   **Behavioral Correlation:** A "Retention vs. Cancellation" analysis confirming that repeat guests exhibit significantly lower cancellation frequencies compared to new guests.

---

## Dataset Description
**Dataset Used:** Hotel Booking Demand Dataset  
The dataset contains historical booking records for **City Hotels** and **Resort Hotels**.

**Important columns include:**
*   `hotel`, `is_canceled`, `lead_time`, `arrival_date_year`, `arrival_date_month`
*   `stays_in_weekend_nights`, `stays_in_week_nights`
*   `adults`, `children`, `babies`
*   `market_segment`, `deposit_type`, `customer_type`
*   `adr` (Average Daily Rate), `reservation_status`

**Additional engineered features:** `total_stay`, `total_guests`, `arrival_date`.

---

## Tools and Technologies Used
*   **Python** (Pandas, NumPy)
*   **Visualization:** Matplotlib, Seaborn
*   **Machine Learning:** Scikit-Learn
*   **BI Tools:** Tableau / Power BI
*   **Version Control:** GitHub

---

## Project Workflow

### Week 1 – Data Cleaning and Feature Engineering
*   Handled missing values and removed duplicates.
*   Treated ADR outliers.
*   Engineered new features: `total_stay`, `total_guests`, and `arrival_date`.

### Week 2 – Exploratory Data Analysis (EDA)
*   Analyzed ADR vs. Cancellation trends and Lead Time behavior.
*   Performed Market Segment and Deposit Type impact analysis.
*   Studied seasonality trends and booking curves.

### Week 3 – Predictive Modeling
*   Built machine learning models to predict booking cancellations.
*   Models used: **Logistic Regression** and **Random Forest**.
*   **Random Forest** achieved the best performance with strong prediction accuracy.

### Week 4 – Dashboard Development
*   Created an interactive dashboard focusing on Dynamic Pricing Analysis and Revenue Optimization.

---

## Strategic Recommendations
1.  **Promote Non-Refundable Deposit Options:** Reduces cancellation rates and stabilizes revenue.
2.  **Apply Dynamic Pricing During Peak Seasons:** Optimize ADR to improve RevPAR based on seasonal demand.
3.  **Focus on High-Risk Segments:** Target OTA users and transient customers who show higher cancellation behavior.
4.  **Build Loyalty Programs:** Specifically for repeat guests who show lower cancellation rates.

---
## 📊 Dashboard Overview: Customer Retention & Loyalty Analysis
<img width="1521" height="823" alt="dashboard_screenshot" src="https://github.com/user-attachments/assets/0c1bd27a-ad39-4ac1-b5d2-ae60bd4d7d6e" />

The project includes a comprehensive **Customer Retention & Loyalty Analysis** dashboard designed to track high-level performance metrics and behavioral trends.


## Team Project By:
*   **Jerolin Mathew**
*   **Penchala Aneel Gaddam**
*   **Rupali Thakur**
*   **Kiruthika**

---

## Setup Instructions
**Step 1: Clone the Repository**
```bash
git clone [https://github.com/Jerolin911/Travel-Tourism-Hospitality-Customer-Retention-Analysis-Dynamic-Pricing](https://github.com/Jerolin911/Travel-Tourism-Hospitality-Customer-Retention-Analysis-Dynamic-Pricing)
