# E-Commerce Sales Data Analytics

## Overview
This is a master’s-level project that performs **comprehensive data analysis** on a large-scale e-commerce sales dataset. The goal is to extract actionable insights on **sales trends, product performance, and customer behavior**, and provide **data-driven recommendations** for business optimization.

## Dataset
The dataset contains transactional data with the following columns:  
- `InvoiceNo` – Invoice number  
- `StockCode` – Product code  
- `Description` – Product name  
- `Quantity` – Number of units sold  
- `InvoiceDate` – Date and time of purchase  
- `UnitPrice` – Price per unit  
- `CustomerID` – Unique customer ID  
- `Country` – Customer country  

## Project Steps

1. **Data Cleaning and Preprocessing**  
   - Handled missing values and removed negative/zero quantities.  
   - Converted columns to appropriate data types.  
   - Calculated `Revenue` = Quantity × UnitPrice.

2. **Exploratory Data Analysis (EDA)**  
   - Identified top products and categories by revenue.  
   - Analyzed monthly sales trends and revenue distribution by country.  
   - Calculated KPIs such as Average Order Value (AOV) and Repeat Customer Rate.

3. **RFM (Recency, Frequency, Monetary) Analysis**  
   - Calculated Recency (days since last purchase), Frequency (number of purchases), and Monetary (total spend) per customer.  
   - Assigned RFM scores (1–5) and segmented customers into: Champion, Loyal, Potential, Needs Attention, At-Risk.  

4. **Data Visualization and Dashboard**  
   - Created static and interactive charts for top products, categories, monthly revenue, and customer segments.  
   - Built an interactive dashboard using Plotly for easy exploration.

## Tools & Technologies
- Python  
- Pandas & NumPy  
- Matplotlib & Seaborn  
- Jupyter Notebook  
- Plotly (for interactive dashboards)

## Key Insights
- Identified **top-selling products and categories** driving revenue.  
- Discovered **seasonal sales trends**, with peaks during holidays.  
- Segmented customers to highlight **high-value groups** for targeted marketing.  
- Provided recommendations to **optimize inventory, marketing campaigns, and customer engagement**.
