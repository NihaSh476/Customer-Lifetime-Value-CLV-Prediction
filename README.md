# Customer Lifetime Value (CLV) Prediction

**Project Overview:**

This project aims to estimate Customer Lifetime Value (CLV) using historical transaction data through predictive modeling. CLV is a key business metric that estimates the total revenue a business can expect from a customer throughout their entire relationship. Accurately predicting CLV allows companies to optimize customer acquisition, retention, and overall marketing strategies.

The analysis and modeling have been executed using Python, focusing on probabilistic models, particularly the BG/NBD (Beta-Geometric/Negative Binomial Distribution) model for predicting purchase frequency and the Gamma-Gamma model for estimating the average transaction value.

**Objectives:**
- Analyze customer transaction behavior based on frequency, recency, and monetary value.
- Predict the number of future transactions using the BG/NBD model.
- Estimate the average revenue per transaction using the Gamma-Gamma model.
- Calculate the expected Customer Lifetime Value (CLV) for each customer.
- Visualize key insights for business decision-making.
  
**Tools & Technologies Used:**
Language: Python
Libraries:
- pandas – Data manipulation
- numpy – Numerical calculations
- matplotlib and seaborn – Visualization
- lifetimes – Customer lifetime value modeling
  
**Key Steps in the Workflow:**
1. Data Preprocessing
   - Load and clean transactional data.
   - Aggregate data to calculate key metrics per customer: frequency, recency, and age (T).
2. Model Building
   - BG/NBD Model: Predicts how many future purchases a customer is expected to make.
   - Gamma-Gamma Model: Estimates the average monetary value per transaction.
3. CLV Prediction
   - Combine both models to estimate the total expected value from each customer over a defined time period.
4. Data Visualization
   - Distribution of customer frequency and recency.
   - Scatter plots showing relationship between frequency, recency, and monetary value.
   - Histogram of predicted CLV.

**Benefits & Use Cases:**
- Customer Segmentation: Identify and prioritize high-value customers.
- Targeted Marketing: Allocate marketing budgets more efficiently.
- Revenue Forecasting: Improve financial planning and decision-making.
- Retention Strategy: Focus retention efforts on high-value segments.


