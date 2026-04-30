# E-Commerce Sales Data Analysis

## Project Overview
This project analyzes an e-commerce dataset to uncover key insights into sales performance, customer behavior, and product trends. The goal is to provide actionable recommendations that can help improve revenue and decision-making.

## Objectives
- Identify top-performing products  
- Analyze customer spending patterns  
- Understand sales trends over time  
- Provide data-driven business recommendations  

## Dataset Description
The dataset contains transactional data from an online retail store, including:
- InvoiceNo: Unique transaction ID  
- StockCode: Product ID  
- Description: Product name  
- Quantity: Number of items purchased  
- InvoiceDate: Date and time of purchase  
- UnitPrice: Price per unit  
- CustomerID: Unique customer identifier  
- Country: Customer location  

## Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Matplotlib    
- Google colab 

## Data Cleaning
- Removed duplicate records  
- Dropped rows with missing CustomerID values  
- Filtered out returns (negative quantities)  
- Removed invalid (zero/negative) prices  
- Created a Revenue column (Quantity × UnitPrice)  
- Extracted time-based features (Month, Day, Hour)  

## Exploratory Data Analysis

### Business Overview
- Calculated total revenue, average order value, number of customers, and transactions  

### Top Products
- Identified highest revenue-generating products  

### Customer Analysis
- Analyzed spending patterns and identified high-value customers  

### Time Trends
- Examined monthly, daily, and hourly sales patterns  

##  Key Insights
- Revenue is highly concentrated among a small percentage of products  
- A small group of customers contributes most of the total revenue  
- Sales show clear seasonal trends across different months  

##  Recommendations
- Focus marketing and inventory on top-performing products  
- Implement loyalty programs for high-value customers  
- Run targeted promotions during low-sales periods  
- Align marketing campaigns with peak shopping hours  

## Conclusion
This analysis highlights key drivers of revenue and customer behavior in an e-commerce business. By focusing on high-performing products, retaining valuable customers, and leveraging seasonal trends, the business can improve overall performance and profitability.

## Limitations
- Some transactions (returns) were removed for simplicity  
- Dataset lacks detailed customer demographic information
  
## Sample visualisations
<img width="646" height="650" alt="Top 10 products bar chart" src="https://github.com/user-attachments/assets/6fd8ee5b-0ab9-49dc-b830-9505761c2b0a" />
<img width="550" height="459" alt="Monthly revenue trend line chart" src="https://github.com/user-attachments/assets/78049aaf-62d2-476d-ab59-3a15b3a69699" />

## 🔗 Project Files
- Notebook: e_commerce_analysis.ipynb
