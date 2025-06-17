# Teleco-Customer-Segmentation-and-Churn-Prediction
Customer Segmentation and Churn Prediction
Overview
This project analyzes the Telco Customer Churn dataset (~7,043 customers) to segment customers using clustering and visualize churn patterns. Built interactive Power BI dashboards to uncover insights into churn drivers (e.g., contract type, services) and customer segments, providing actionable retention strategies.
Tools and Technologies

Power BI: Interactive dashboards for churn analysis
Python: pandas, scikit-learn for preprocessing and clustering (optional)
SQL: Data querying (simulated for dataset)
Excel: Data validation and preprocessing

Methodology

Data Preprocessing: Imported processed_data.csv, rescaled numerical columns (tenure, MonthlyCharges, TotalCharges), and created derived columns for Contract and PaymentMethod using DAX.
Exploratory Data Analysis (EDA): Analyzed churn rates by demographics, services, and clusters.
Clustering: Used Cluster column (precomputed) to segment customers into 4 groups.
Visualization: Developed Power BI dashboards with 10 visuals (e.g., Pie Chart, Stacked Bar, Scatter Plot) to explore churn patterns.
Recommendations: Proposed retention strategies like discounts for month-to-month contract customers.

Results

Identified 26% churn rate, with highest churn in month-to-month contracts and fiber optic users.
Cluster analysis revealed high-risk segments (e.g., short-tenure, high-charge customers).
Dashboards enabled interactive exploration of churn drivers.

Visualizations

Power BI Dashboard: Churn distribution, churn by services, cluster analysis, and more.
Key visuals: Churn by Contract (Donut Chart), Tenure vs. Churn (Histogram), Total Charges vs. Tenure (Scatter Plot).

Repository Structure

data/: processed_data.csv
powerbi/: churn_dashboard.pbix
README.md: Project overview
screenshots/: Dashboard images

How to Run

Clone the repo: git clone https://github.com/yourusername/churn-prediction
Open powerbi/churn_dashboard.pbix in Power BI Desktop.
Import data/processed_data.csv if needed.
Explore dashboards with slicers for gender, SeniorCitizen, Cluster.

Future Improvements

Integrate predictive modeling using Python (e.g., random forest).
Add time-series analysis for churn trends.
Publish dashboard to Power BI Service for real-time access.

