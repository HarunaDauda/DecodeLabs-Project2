#Decodelab Data Analytics — Project2


#About
Building on the foundation laid in Project 1, this project 
moves into the discovery phase of Data Analytics. The goal 
was not just to look at numbers — it was to interrogate them. 
To ask the right questions, follow the patterns and uncover 
the story hidden inside a real e-commerce dataset. This is 
where raw data starts speaking the language of business.

#The Dataset
A real-world e-commerce orders dataset containing 1,200 
records across 14 columns — covering order details, product 
categories, payment methods, shipping addresses, coupon usage, 
referral sources and order statuses spanning from 2023 to 2025.

#What I Did
**Phase 1 — Basic Statistics**
Calculated mean, median and count across key numeric columns 
including UnitPrice, TotalPrice, Quantity and ItemsInCart to 
establish a statistical baseline for the dataset.

**Phase 2 — Trend Analysis**
Investigated patterns across the business by analyzing which 
products sell the most, which payment methods customers prefer, 
where customers come from, which products generate the most 
revenue and how orders trend month by month over time.

**Phase 3 — Outlier Detection**
Applied the IQR method to detect abnormal values in UnitPrice, 
TotalPrice and Quantity. Zero outliers were found across all 
three columns confirming the dataset is statistically clean 
and consistent.

**Phase 4 — Key Observations**
Translated every statistical finding into a plain business 
insight by applying the So What test — moving beyond what 
the data says to what it actually means for the business.

#Key Findings
- All 1,200 records were analyzed with zero outliers detected
- Order values are consistent with no dramatic spikes or drops
- Cancelled and returned orders represent a notable portion 
  of total orders and deserve further business investigation
- One referral source consistently brings in the most customers
  making it the strongest marketing channel in the dataset
- Monthly order trends are stable across 2023 2024 and 2025
  with no significant seasonal disruptions observed

## Tools Used
- Python
- Pandas
