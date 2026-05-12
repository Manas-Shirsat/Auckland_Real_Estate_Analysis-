# Auckland Housing Market Analysis – Power BI

An interactive Power BI dashboard analysing Auckland housing market trends including sale prices, rental prices, and regional activity from 2021–2025.

This project explores housing affordability, rental yield, and regional market dynamics using data modelling and DAX-driven analytics.

---
## Dashboard Preview
<img width="1120" height="630" alt="Market Overview" src="https://github.com/user-attachments/assets/fd33c8ae-2a2a-407a-9f14-69fda92780ae" />


# Tools & Technologies

Power BI  
Power Query (ETL)  
DAX  
Data Modelling (Star Schema)  
Data Visualization  

---

# Key Skills Demonstrated

Data Cleaning  
Data Transformation  
Power BI Dashboard Development  
DAX Calculations  
Time Intelligence  
Real Estate Market Analysis  

---

# Dashboard Screenshots

## Market Overview
<img width="1120" height="630" alt="Market Overview" src="https://github.com/user-attachments/assets/30991e5c-9242-4095-9e50-9fadbca454f0" />



##  Investment Analysis
<img width="1120" height="630" alt="Investment Analysis" src="https://github.com/user-attachments/assets/f68baba9-20a8-43ac-acfa-ed5e36185361" />


##  Suburb Analysis
<img width="1120" height="630" alt="Suburb Analysis" src="https://github.com/user-attachments/assets/057bbae5-2546-48c7-a71e-f5bfdda2250b" />


---

#  Data Source

Housing market data used in this analysis was sourced from monthly market reports published by Barfoot & Thompson, one of Auckland’s largest real estate agencies.

The dataset includes monthly market indicators such as:

• Average sale price  
• Average rental price  
• Sales volume  
• Rental volume  

Data covers the period **2021–2025** and was processed and transformed for analytical purposes using Power Query and Power BI.

Source: Barfoot & Thompson Monthly Housing Market Reports

#  Data Preparation & Cleaning

Collected monthly Auckland housing market data (2021–2025) from Barfoot & Thompson market reports including:

• Average sale price  
• Average rental price  
• Sales volume  
• Rental volume  

Data preparation steps included:

• Standardized inconsistent region naming  
• Created region mapping table to normalize categories  
• Removed null and blank records using Power Query  
• Unpivoted wide tables to create time-series format  
• Converted month and year fields into a proper Date column  

---

#  Data Modeling

Built a **star schema data model**.

### Dimension Tables

Dim_Date  
Dim_Region  
Dim_Suburb  
Dim_Bedrooms  

### Fact Tables

Sales Price Fact Table  
Sales Volume Fact Table  
Rental Price Fact Table  
Rental Volume Fact Table  

Relationships created between dimension tables and fact tables enabling efficient filtering and aggregation.

---

#  DAX Measures

Key analytical measures created:

• Total Sales Volume  
• Average Sale Price  
• Average Rent Price  
• Previous Year Sales Price  
• Year-over-Year Change %  
• Rental Yield %

----

#  Interactive Dashboard Features

### KPI Cards

• Average Sale Price  
• Average Rent Price  
• Sales Volume  
• Previous Year comparison  
• YoY percentage change  

### Trend Analysis

Dual-axis line chart showing:

• Average Sale Price  
• Average Rent Price  

Secondary axis used to handle scale differences.

### Regional Analysis

Treemap visualizing regional sales distribution  

Pie charts comparing sales vs rental volume  

---

#  Visualization & UX Enhancements

• Consistent region-based colour palette  
• Conditional formatting using DAX measures  
• Dynamic dashboard title based on region selection  
• Cross-filtering interactions between visuals  
• Optimized layout and spacing for readability  

---

#  Insights Enabled

The dashboard allows users to:

• Compare housing prices vs rental prices by region  
• Identify regions with strongest market activity  
• Analyse housing trends over time  
• Evaluate property investment potential via rental yield  
• Explore regional housing dynamics interactively  

---

#  Project Outcome

Developed an interactive Power BI dashboard enabling exploration of Auckland’s housing market trends from 2021–2025 through dynamic filtering, region-level insights, and investment-oriented metrics.

#  Market Overview
Shows declining sale prices and rising rents, indicating improving rental yield.
---

#  Repository Contents

Power BI Dashboard (.pbix)  
Dataset  
Dashboard Screenshot  
Project Documentation
