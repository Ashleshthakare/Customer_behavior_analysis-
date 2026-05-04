## 📊 Dashboard Preview

![Dashboard Demo](./assets/dashboard-demo.gif)

# Customer_behavior_analysis-
Data-driven analysis of customer shopping behavior to identify high-value segments, optimize discounts, and improve marketing strategies.

🛍️ Customer Shopping Behavior Analysis
📌 Project Overview

This project focuses on analyzing customer shopping behavior using transactional data from 3,900 purchases across multiple product categories.

The primary goal is to extract meaningful insights into:

Customer spending patterns
Product preferences
Customer segmentation
Subscription behavior

These insights help businesses make data-driven decisions to increase revenue and improve customer retention.

📊 Dataset Summary
Total Records: 3,900
Total Features: 18
Key Data Points:
Customer Details: Age, Gender, Location, Subscription Status
Purchase Information: Item, Category, Amount, Season, Size, Color
Behavioral Data:
Discount usage
Purchase frequency
Review ratings
Shipping type

⚠️ Missing Values:

37 missing values in the Review Rating column
🧹 Data Cleaning & Preparation (Python)

Performed using Python (Pandas):

Data loading and structure analysis
Handling missing values using median imputation (category-wise)
Column standardization (snake_case)
Feature engineering:
age_group creation
purchase_frequency_days calculation
Removed redundant columns (promo_code_used)
Data consistency checks
🗄️ Database Integration (PostgreSQL)
Connected Python pipeline to PostgreSQL
Loaded cleaned dataset into database
Enabled structured querying for business insights
🔍 Business Analysis (SQL)

Key business questions solved:

Revenue comparison by gender
High-spending customers using discounts
Top 10 products based on ratings
Shipping type impact on purchase value
Subscriber vs Non-subscriber revenue comparison
Discount-dependent products
Customer segmentation:
New
Returning
Loyal
Top products per category
Subscription likelihood of repeat buyers
Revenue contribution by age group
📈 Power BI Dashboard

An interactive dashboard was built in Power BI to visualize:

Revenue trends
Customer segments
Product performance
Purchase behavior

This enables quick decision-making for stakeholders.

💡 Key Insights
Discount usage does not always reduce revenue (high-value customers still spend more)
Loyal customers contribute significantly to total revenue
Subscription users show higher engagement
Certain products are highly dependent on discounts
🚀 Business Recommendations
🎯 Boost Subscriptions: Offer exclusive benefits
🔁 Loyalty Programs: Convert repeat buyers into loyal customers
💰 Optimize Discounts: Maintain balance between revenue and margins
⭐ Promote Top Products: Highlight high-rated & best-selling items
📊 Targeted Marketing: Focus on high-value age groups & express shipping users
🛠️ Tech Stack
Python (Pandas, Data Cleaning)
SQL (PostgreSQL)
Power BI (Dashboard & Visualization)
📁 Project Structure
├── data/                 # Raw & cleaned datasets
├── notebooks/           # Python analysis notebooks
├── sql/                 # SQL queries
├── dashboard/           # Power BI file (.pbix)
├── README.md
🎯 Project Objective (Career Angle)

This project demonstrates:

End-to-end data analytics workflow
Ability to convert raw data → business insights
Strong alignment with:
Data Analyst roles
Marketing Analyst roles
Business Analyst / Consulting roles
📬 Connect With Me

If you’re interested in data-driven marketing and analytics, feel free to connect on LinkedIn 🚀
