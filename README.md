# data-Analyst-FinalProject

________________________________________
# E-commerce Return Rate Reduction Analysis

## 📌 Objective
This project aims to analyze and reduce product return rates in an e-commerce platform. By identifying key factors that drive returns, such as product categories, geography, and marketing channels, we provide actionable insights to minimize return-related losses and improve customer satisfaction.

## 🛠️ Tools & Technologies
- **Python** – Data cleaning, analysis, and logistic regression modeling  
- **Power BI** – Interactive dashboard and return risk score visualization  
- **SQL** – Data extraction and aggregation

## 📊 Key Deliverables
- ✅ **Interactive Power BI Dashboard**  
   Includes drill-through filters by category, geography, and marketing channel to explore return rates and risk scores.
  
- ✅ **Python Codebase**  
   Scripts for data preprocessing, return rate analysis, and logistic regression modeling to predict return probability.

- ✅ **CSV Output**  
   A list of **high-risk products** based on predicted return probability from the logistic regression model.


## 📂 Project Structure

ecommerce-return-analysis/
│
├── data/
│ ├── orders.csv
│ ├── returns.csv
│ └── high_risk_products.csv # Output file
│
├── notebooks/
│ └── return_rate_analysis.ipynb
│
├── dashboard/
│ └── return_risk_dashboard.pbix
│
├── scripts/
│ └── model_logistic_regression.py
│
├── README.md
└── requirements.txt

---

## 🔍 Analysis Overview

- **Data Cleaning**  
  - Removed duplicates and nulls from both orders and returns datasets  
  - Standardized category, channel, and location values

- **Exploratory Analysis**  
  - Return % calculated by category, supplier, geography, and marketing source  
  - Identified high-return segments and patterns

- **Predictive Modeling**  
  - Applied logistic regression to predict the likelihood of a product being returned  
  - Features include: product category, price, customer region, previous return history, etc.

- **Visualization**  
  - Power BI dashboard with slicers, maps, and bar charts  
  - Drill-through pages for deep dives into return metrics

---

## 📈 Results
- Identified product categories and marketing channels with the highest return rates  
- Built a logistic regression model with ~X% accuracy (update with actual score)  
- Generated list of high-risk products for operational intervention


________________________________________
👤 Author
Shivansh Jain
GitHub Profile (Replace with your actual GitHub URL if different)
________________________________________
🙌 Contributions
Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.
________________________________________
📜 License
This project is open-source and available under the MIT License.
