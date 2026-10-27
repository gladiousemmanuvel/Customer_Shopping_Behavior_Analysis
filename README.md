# 🛍️ Customer Shopping Behavior & Demographics Analytics Dashboard

## 📌 Project Overview
Designed to uncover consumer purchasing patterns, segment buyer demographics, and forecast subscription loyalty trends to optimize retail marketing strategies. This project analyzes multi-category retail datasets using Python for EDA, MySQL for data modeling (`cleaned_customer_data`), and Power BI for interactive visualization.

## ⚙️ Analytical Workflow
* **Data Cleaning & Integration:** Processed multi-category retail datasets, handling null values and verifying data types using Python (Pandas).
* **ETL & Relational Modeling:** Loaded preprocessed customer transaction records (`cleaned_customer_data`) into MySQL Workbench for analytical querying and aggregation.
* **DAX & KPI Development:** Built custom DAX metrics in Power BI to evaluate core performance metrics, customer subscription ratios, and spending thresholds.
* **Interactive Dashboard Construction:** Designed dynamic cross-filtering by subscriber status, gender, age groups, product categories, and preferred shipping methods.

## 🛠️ Tools & Technologies Used
* **Dataset:** Customer Shopping Behavior Dataset (`customer_shopping_behavior` raw data)
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
├── Customer_Shopping_Behavior_Analysis.ipynb
├── Customer_Behavior_Dashboard.pbix
├── Customer Behavior Dashboard.png
└── README.md
```

## 📊 Dashboard Preview
## 📈 Impact & Core Metrics
Customer Base Evaluated: Analyzed 3.9K individual customer records across various demographic profiles.

Subscription Split: Revealed that non-subscribers account for 73% of the customer base, highlighting a major opportunity for loyalty conversion.

Top Revenue Drivers: Identified Clothing and Accessories as the top revenue-generating categories.

Average Order Value: Maintained an average purchase value of $59.76 across product categories.

## 🏁 Final Conclusion
To maximize overall retail revenue, targeted digital marketing and personalized promotional strategies should be directed toward converting the 73% non-subscriber base. Introducing tailored loyalty rewards around high-volume categories like Clothing and Accessories will significantly boost customer retention and lifetime value.
