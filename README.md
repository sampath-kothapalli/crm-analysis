
   # E-commerce Customer Analytics and Business Insights

This project focuses on analyzing customer behavior, retention, and acquisition trends in an e-commerce dataset. It employs techniques like RFM analysis, cohort analysis, segmentation, and visualization to uncover actionable insights, helping businesses improve their customer lifetime value (CLV) and optimize retention strategies.

## 📌 Table of Contents

- [Overview](#e-commerce-customer-analytics-and-business-insights)
- [Technologies Used](#-technologies-used)
- [Project Type](#project-type)
- [Data Description](#data-description)
- [Solution Approach](#solution-approach)
- [Key Data Insights](#-key-data-insights)
- [Business Recommendations](#-business-recommendations)

## 🛠 **Technologies Used**

- **Python** (Pandas, NumPy, Matplotlib, Seaborn, lifetimes)
- **Jupyter Notebook & Google Colab**

## **Project Type**

- Data Preprocessing/Cleaning and Feature Engineering
- Advanced Visualization Techniques, RFM Analysis, CLV Segmentation, and Cohort Analysis

## **Data Description**

| Column Name     | Description                                                                                                     |
| --------------- | --------------------------------------------------------------------------------------------------------------- |
| **InvoiceNo**   | Invoice number that consists of 6 digits. If this code starts with the letter 'C', it indicates a cancellation. |
| **StockCode**   | Product code that consists of 5 digits.                                                                         |
| **Description** | Product name.                                                                                                   |
| **Quantity**    | The quantities of each product per transaction.                                                                 |
| **InvoiceDate** | This represents the day and time when each transaction was generated.                                           |
| **UnitPrice**   | Product price per unit.                                                                                         |
| **CustomerID**  | Customer number that consists of 5 digits. Each customer has a unique customer ID.                              |
| **Country**     | Name of the country where each customer resides.                                                                |

## **Solution Approach**

This project follows a structured data analysis workflow:

1. **Data Cleaning & Preprocessing:** Handling missing values, outliers, and data transformations.
2. **Exploratory Data Analysis (EDA):** Visualizing customer behavior, revenue trends, and segmentation insights.
3. **RFM Analysis:** Categorizing customers based on Recency, Frequency, and Monetary values.
4. **Cohort Analysis:** Analyzing retention trends over time.
5.

## 📈 **Key Data Insights**

1. **Customer Segmentation:**
   - Identified **1,306 loyal customers** contributing significantly to monthly revenue.
   - **At-risk customers** represent a key area for retention strategies.
2. **📊 Customer Lifecycle Analysis:**
   - Retention rates declined sharply after the **second cohort month**, highlighting the need for stronger engagement post-onboarding.
3. **💰 Revenue Contribution:**
   - Loyal customers contribute **over 75% of the revenue**, emphasizing the value of retention efforts.
4. **🛍️ Purchasing Behavior:**
   - **Weekdays** observed a higher purchasing frequency, suggesting **optimal times for targeted campaigns**.

## 🔑 **Business Recommendations**

1. **🔄 Retention Strategies:**
   - Develop **loyalty programs and personalized offers** for at-risk customers.
   - Automate **re-engagement campaigns** using email or app notifications.
2. **📢 Acquisition Optimization:**
   - Invest in **digital ads targeting high-growth regions** like California.
   - Run **location-based promotional campaigns** to tap underperforming regions.
3. **⭐ Customer Experience Enhancement:**
   - Analyze **feedback from at-risk customers** to address concerns and improve satisfaction.
   - Offer **exclusive benefits for customers in their first two months** to boost retention.
4. **📊 Data-Driven Campaigns:**
   - Leverage **RFM analysis** to run **targeted promotions** for high-value segments.
   - Use **geographic insights** to tailor regional marketing campaigns.

