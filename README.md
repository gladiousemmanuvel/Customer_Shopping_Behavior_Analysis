# 🛍️ Customer Shopping Behavior & Demographics Analytics Dashboard

## 📌 Project Overview
This project explores retail customer demographics, purchasing behavior, item preferences, and spending patterns using the **Customer Shopping Behavior** dataset. Using Python for exploratory data analysis (EDA), MySQL for relational data modeling, and Power BI for interactive dashboarding, it provides key consumer insights for targeted business strategies.

## ⚙️ Process
* **Data Cleaning & Handling Nulls:** Handled missing values, standardized data types, and verified record consistency using Python (Pandas).
* **Database Modeling & ETL:** Loaded the preprocessed dataset (`cleaned_customer_data`) into MySQL for transactional querying and aggregations.
* **DAX & KPI Development:** Modeled measures in Power BI for Total Revenue, Average Purchase Value, Active Subscriptions, and Customer Ratings.
* **Interactive Dashboard Construction:** Designed visual charts and dynamic slicers for demographics, product categories, and purchasing frequency.

## 🛠️ Tools & Technologies Used
* **Programming Language:** Python (Pandas, Seaborn, Matplotlib)
* **Database & Querying:** MySQL Workbench (`cleaned_customer_data`)
* **Data Visualization:** Power BI (`Customer_Behavior_Dashboard`)
* **Development Environment:** Jupyter Notebook

## 📁 Repository & Folder Structure
```text
Customer_Shopping_Behavior_Analysis/
├── data/
│   ├── raw_data/
│   │   └── customer_shopping_behavior.csv
│   └── cleaned_data/
│       └── cleaned_customer_data.csv
├── sql/
│   └── customer_behavior_queries.sql
├── Customer_Shopping_Behavior_Analysis.ipynb
├── Customer_Behavior_Dashboard.pbix
├── Customer Behavior Dashboard.png
└── README.md
```
## 📊 Dashboard Preview
## 💡Project Insights
Demographic Driver: Young Adults and adult male shoppers account for the largest proportion of transaction volume.

Category Performance: Clothing and Accessories emerge as the top revenue-generating product categories.

Subscription Rate: Approximately 73% of total shoppers are non-subscribers, presenting a key opportunity for conversion programs.

Spending Behavior: The overall average purchase value per transaction stands at $59.76.

## 🏁 Final Conclusion
To maximize overall retail revenue, a strategic marketing plan focusing on promoting subscription programs to repeat non-subscribed customers should be implemented. Loyalty programs tailored towards high-volume categories like Clothing and Accessories will further drive customer engagement and average order values.
