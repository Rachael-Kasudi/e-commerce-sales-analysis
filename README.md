# E-Commerce Sales Data Analysis

## Project Overview
In this project, I performed an end-to-end analysis of an e-commerce sales dataset to uncover trends, evaluate business performance, and generate actionable insights.
This project simulates a real-world data analyst workflow — from raw data cleaning to delivering business recommendations.

## Business Problem
E-commerce businesses generate large volumes of transactional data but often struggle to translate this data into actionable insights.

This project answers key business questions such as:
-What drives revenue growth?
-Which products perform best?
-When do customers buy the most?
-Where are there opportunities to improve sales?  

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
- Python(Pandas, numpy)  
- Data visualisation(Matplotlib, seaborn)  
- Google colab

# Methodology
## 1.Data Cleaning
- Removed duplicate records  
- Dropped rows with missing CustomerID values  
- Filtered out returns (negative quantities)  
- Removed invalid (zero/negative) prices  
- Created a Revenue column (Quantity × UnitPrice)  
- Extracted time-based features (Month, Day, Hour)  

## 2.Exploratory Data Analysis

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

## Key Skills Demonstrated
-Data Cleaning & Preprocessing
-Exploratory Data Analysis (EDA)
-Data Visualization
-Business Insight Generation
-Analytical Thinking

## Conclusion
This project demonstrates the ability to transform raw e-commerce data into meaningful insights that can guide strategic decision-making and improve business performance.

## Limitations
- Some transactions (returns) were removed for simplicity  
- Dataset lacks detailed customer demographic information
  
## Sample visualisations
<img width="646" height="650" alt="Top 10 products bar chart" src="https://github.com/user-attachments/assets/6fd8ee5b-0ab9-49dc-b830-9505761c2b0a" />
<img width="550" height="459" alt="Monthly revenue trend line chart" src="https://github.com/user-attachments/assets/78049aaf-62d2-476d-ab59-3a15b3a69699" />

## 🔗 Project Files
- Notebook: 'https://github.com/Rachael-Kasudi/e-commerce-sales-analysis/blob/d140a7b09645762e598c70d2bd8b00ccc526e8dc/e_commerce_analysis.ipynb'
