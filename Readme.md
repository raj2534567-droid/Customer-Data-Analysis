# Customer Data Analysis – Business Insights using Python

## 1. Project Overview

This project analyzes customer purchasing behavior using data analytics techniques to uncover insights that can help businesses improve marketing strategies and revenue generation.

Using Python-based exploratory data analysis, the study focuses on identifying high-value customers, understanding purchasing patterns, and segmenting customers based on their transaction behavior.

The analysis provides insights into how businesses can better understand their customer base and design targeted engagement strategies.

---
# Business Objectives

The main objectives of this project are:

- Identify top revenue generating customers
- Perform **RFM (Recency, Frequency, Monetary) segmentation**
- Analyze revenue contribution by different customer segments
- Understand customer purchasing behavior
- Demonstrate the **Pareto Principle (80/20 rule)** in customer revenue contribution
- Generate business insights using data visualization

---

## 2. Dataset Description

This project uses a synthetic retail dataset containing **23,050 transactions made by 1,000 unique customers**.

The dataset is structured into two related tables to simulate a real-world retail database environment.

---

### 2.1 Customer Master Data

This dataset contains demographic and profile information for each customer.

| Column Name | Description |
|-------------|-------------|
| CustomerID | Unique identifier for each customer |
| Name | Customer's full name |
| Email | Customer's email address |
| Gender | Male, Female, or Not Disclosed |
| Age | Customer age (between 18 and 75) |
| City | City where the customer resides |
| MaritalStatus | Single, Married, Divorced, Widowed |
| NumChildren | Number of children in the household |
| JoinDate | Date when the customer first registered |

---

### 2.2 Transaction Data

This dataset contains purchase transactions made by customers.

| Column Name | Description |
|-------------|-------------|
| CustomerID | Links transaction to the customer master dataset |
| TransactionDate | Date when the transaction occurred |
| TransactionAmount | Amount spent in the transaction (₹) |

The relational structure between these datasets allows analysis of purchasing patterns, customer value, and revenue contribution.

---

## 3. Data Preparation & Processing

Before performing the analysis, several preprocessing steps were conducted to ensure data quality and consistency:

- Verified dataset structure and variable types
- Checked for missing or inconsistent values
- Merged customer and transaction datasets
- Calculated customer-level metrics required for RFM analysis
- Prepared aggregated transaction data for revenue analysis

After preprocessing, the dataset was ready for exploratory data analysis.

---

## 4. Exploratory Data Analysis (EDA)

Exploratory analysis was conducted to understand customer purchasing behavior and revenue distribution.

---

## Customer Segment Distribution

Customers were segmented using RFM analysis and categorized into the following segments:

- Regular Customers
- Potential Loyalists
- Big Spenders
- Champions
- Loyal Customers
- At Risk
- Lost Customers

The following chart shows how customers are distributed across these segments.

![Customer Segment Distribution](segment_distribution.png)

### Insight

The distribution reveals that:

- A large portion of customers fall into the **Regular Customer** category.
- **Potential Loyalists** represent an important growth opportunity.
- **Champions and Loyal Customers** represent high-value customers.
- **At Risk and Lost Customers** indicate segments that may require retention strategies.

Understanding the distribution of customer segments helps businesses prioritize marketing and engagement strategies.

---

## Revenue Contribution by Customer Segment

This visualization illustrates the percentage contribution of each customer segment to total business revenue.

![Revenue Contribution](revenue_contribution.png)

### Insight

Key observations from this chart include:

- **Regular Customers contribute the largest share of revenue**.
- **Big Spenders and Champions generate significant revenue despite smaller segment size**.
- **Loyal Customers provide stable recurring revenue**.
- **At Risk and Lost customers contribute smaller revenue shares**, highlighting potential revenue loss due to customer churn.

This analysis demonstrates that not all customers contribute equally to revenue generation.
##  Business Insights

The analysis produced several valuable insights regarding customer behavior:

- A small percentage of customers generate a large portion of overall revenue.
- **Champion and Loyal customers** contribute significantly to business value.
- **At-risk customers** represent an important group for retention efforts.
- Customer segmentation enables more effective targeting and personalized marketing strategies.

---
## Recency vs Monetary Scatter Plot

The scatter plot below visualizes the relationship between **Recency and Monetary value** for different customer segments.

![RFM Scatter](rfm_scatter.png)

### Insight

The scatter plot provides deeper insights into customer purchasing behavior:

- Customers with **low recency and high monetary values** represent **champions and loyal customers**.
- Customers with **high recency and lower spending** are often classified as **at-risk or lost customers**.
- **Big spenders appear clustered in high monetary value regions**.
- Regular customers are distributed across moderate recency and spending ranges.

This visualization helps businesses understand how customer engagement relates to revenue generation.
---
## Pareto Analysis – Top Customers vs Revenue

Pareto analysis was used to determine how revenue is distributed among customers.

![Pareto Analysis](pareto.png)

The chart illustrates the **Pareto principle (80/20 rule)** where a small percentage of customers contribute a large portion of total revenue.

### Insight

- The top **20% of customers generate a large share of total revenue**.
- The remaining customers contribute smaller portions individually.
- Businesses can increase profitability by focusing on retaining high-value customers.

This analysis highlights the importance of **customer retention strategies and targeted marketing efforts**.

---

# Key Business Insights

The analysis generated several important insights about customer behavior:

- A small percentage of customers contribute a significant share of total revenue.
- **Champions and loyal customers represent the most valuable customer segments**.
- **Potential loyalists represent an opportunity for future revenue growth**.
- **At-risk customers may require targeted retention strategies**.
- Customer segmentation allows businesses to create more personalized marketing strategies.
---
# Business Recommendations

Based on the analysis, the following business strategies are recommended:

### Customer Retention

Focus on retaining **champions and loyal customers** since they contribute significantly to revenue.

### Loyalty Programs

Offer rewards or loyalty programs to encourage repeat purchases from valuable customers.

### Targeted Marketing

Use segmentation to design personalized marketing campaigns for different customer groups.

### Customer Re-Engagement

Develop targeted campaigns for **at-risk customers** to bring them back before they become lost customers.

### Revenue Optimization

Businesses should prioritize high-value customers while also nurturing potential loyalists.

---

## 7. Tools & Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Jupyter Notebook  
- Data Visualization  

---

# Conclusion

This project demonstrates how exploratory data analysis can uncover meaningful insights from customer transaction data.

By applying **RFM segmentation and Pareto analysis**, the project identifies high-value customers and highlights patterns in customer purchasing behavior.

These insights can help businesses improve customer retention, optimize marketing strategies, and increase overall revenue.


---

## 9. Scope for Future Work

Future improvements to this project may include:

- Incorporating demographic and geographic customer data
- Performing time-series analysis of customer purchasing patterns
- Building predictive models for customer lifetime value
- Developing interactive dashboards for business monitoring

---

## Author

**Rajeshwari Patel**  
Aspiring Data Analyst |From Agriculture Graduate to Data Analytics
