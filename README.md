🛒 Olist Brazilian E-Commerce Business Analytics

An end-to-end Business Analytics project on the Olist Brazilian E-Commerce dataset, covering data cleaning, feature engineering, exploratory data analysis, statistical hypothesis testing, and business recommendations using Python.

📖 Project Overview

Olist is one of Brazil's largest e-commerce marketplaces connecting thousands of sellers with customers across the country.

This project analyzes more than 119,000 e-commerce transactions to uncover customer purchasing behavior, revenue trends, delivery performance, seller insights, payment preferences, and factors affecting customer satisfaction.

Rather than focusing only on visualization, this project follows a complete business analytics workflow, beginning with business understanding and ending with statistical validation of the findings.

🎯 Business Objectives

This project answers important business questions such as:

How is the business growing over time?
Which states generate the highest revenue?
Which product categories perform best?
What affects customer satisfaction?
Does late delivery reduce review scores?
Which payment methods are most popular?
Does product price influence customer ratings?
What business strategies can improve revenue and customer experience?

📂 Dataset

Dataset: Olist Brazilian E-Commerce Public Dataset

The analysis combines 9 relational datasets including:

Customers
Orders
Order Items
Products
Sellers
Payments
Reviews
Geolocation
Product Category Translation

🛠️ Tech Stack
Python
Pandas
NumPy
Matplotlib
Seaborn
SciPy
Jupyter Notebook

📁 Project Structure
Olist-Business-Analytics/

│── 00_Business_Understanding.ipynb
│── 01_Data_Loading_and_Understanding.ipynb
│── 02_Data_Cleaning_and_Preprocessing.ipynb
│── 03_Feature_Engineering.ipynb
│── 04_Business_Analysis.ipynb
│── 05_Statistical_Analysis.ipynb

│── images/
│── README.md

🔄 Project Workflow

1️⃣ Business Understanding
Defined business objectives
Identified business questions
Designed analytical workflow

2️⃣ Data Understanding
Loaded all datasets
Checked missing values
Verified duplicate records
Examined dataset structure
Validated data quality

3️⃣ Data Cleaning
Removed duplicate geolocation records
Converted date columns
Handled missing values
Validated Primary Keys
Validated Foreign Keys

4️⃣ Feature Engineering

Created new analytical features including:

Purchase Year
Purchase Month
Purchase Day
Purchase Hour
Weekend Purchase Flag
Delivery Time
Delivery Delay
Late Delivery Indicator

5️⃣ Business Analysis

Performed detailed analysis on:

Business Growth
Customer Analysis
Product Analysis
Revenue Analysis
Delivery Performance
Seller Performance
Payment Behaviour
Correlation Analysis

6️⃣ Statistical Analysis

Validated findings using:

Independent T-Test
One-Way ANOVA
Pearson Correlation
95% Confidence Interval

📊 Key Visualizations

Include screenshots of only the best charts from your notebook inside an images/ folder.

📈 Monthly Revenue Trend
Shows how revenue grew throughout the business lifecycle.
<img width="1589" height="590" alt="image" src="https://github.com/user-attachments/assets/3a3a22c7-ed0f-4546-8980-122cc342c9c5" />

📦 Monthly Order Trend
Visualizes customer demand over time.
<img width="1489" height="590" alt="image" src="https://github.com/user-attachments/assets/70bf92fc-a204-4486-82eb-ff2f2185ca8f" />

🏆 Revenue by State
Highlights the highest revenue-generating regions.
<img width="1189" height="590" alt="image" src="https://github.com/user-attachments/assets/5c82d557-d830-407c-8c8d-1928eb91908c" />

🛍️ Top Product Categories
Shows the best-performing product categories.
<img width="1389" height="690" alt="image" src="https://github.com/user-attachments/assets/b450fb5d-d35d-4a8a-90d5-c96e30e0fe2c" />

⭐ Delivery Delay vs Review Score
Shows the impact of logistics performance on customer satisfaction.
<img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/c49d699f-55a5-401b-90c0-453a933a687d" />

💳 Payment Method Distribution
Displays customer payment preferences.
<img width="762" height="790" alt="image" src="https://github.com/user-attachments/assets/8a873193-d16a-47df-9ebd-5aa6c184de67" />

🔥 Correlation Heatmap
Highlights relationships among important business variables.
<img width="861" height="790" alt="image" src="https://github.com/user-attachments/assets/149bf67e-b946-4829-8944-ac841b2632a1" />


📌 Key Business Insights
📈 Business Growth
Revenue increased significantly between 2017 and 2018, indicating rapid marketplace expansion.
Monthly order volume also showed consistent growth, reflecting increasing customer demand.

👥 Customer Insights
São Paulo contributed the largest customer base and generated the highest revenue.
Most customers placed only one order, suggesting an opportunity to improve customer retention.

🛍️ Product Insights
A small number of product categories generated a substantial share of total sales, following a Pareto-like distribution.
Higher product prices did not lead to better customer ratings.

🚚 Delivery Insights
Average delivery time was approximately 12 days.
Around 7,500+ orders experienced late delivery.
Customers gave significantly lower ratings when deliveries were delayed.

💳 Payment Insights
Nearly 74% of all transactions were completed using credit cards.
Payment amounts differed significantly across payment methods.

📊 Statistical Findings
The statistical analysis validated several important observations:
✅ Late deliveries significantly reduce customer review scores (T-Test, p < 0.05).
✅ Payment values differ significantly across payment methods (ANOVA, p < 0.05).
✅ Product price has no statistically significant correlation with review scores (Pearson Correlation).
✅ The average customer review score was approximately 4.02, with a 95% confidence interval of 4.008–4.024.

💼 Business Recommendations

Based on the analysis, Olist can improve business performance by:

Reducing delivery delays through logistics optimization.
Increasing customer retention using loyalty programs and personalized offers.
Prioritizing inventory for high-performing product categories.
Expanding marketing efforts in high-revenue regions while targeting growth opportunities in underperforming markets.
Promoting credit-card-based campaigns, given its widespread adoption.
Monitoring seller performance to maintain delivery quality and customer satisfaction.













