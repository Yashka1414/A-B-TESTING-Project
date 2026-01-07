# Marketing Campaign Effectiveness Analysis  
## A/B Testing, Regression, and Time Series Analysis

---

## 1. Business Problem

Organizations often distribute marketing budgets across multiple digital advertising platforms without a clear, data-driven understanding of which channel delivers the highest return on investment (ROI).

In this project, the client is running parallel advertising campaigns on **Facebook Ads** and **Google Ads (AdWords)** to drive customer conversions.

Despite similar budget allocations, there is limited visibility into which platform performs better in terms of **engagement, conversion efficiency, cost effectiveness, and revenue generation**. Making budget decisions without analytical validation increases the risk of inefficient spend and reduced campaign profitability.

This analysis aims to provide a structured comparison of both platforms using statistical and analytical techniques.

---

## 2. Business Objective

The primary objective of this analysis is to identify which advertising platform—**Facebook Ads or Google Ads**—delivers superior performance and higher ROI.

This is achieved through:

- Exploratory Data Analysis (EDA)  
- Comparative campaign performance evaluation  
- A/B hypothesis testing  
- Regression analysis to identify key performance drivers  
- Time series analysis to evaluate performance trends over time  

---

## 3. Data Overview

The dataset contains daily campaign-level data for both advertising platforms, including:

- Impressions  
- Clicks  
- Conversions  
- Advertising Spend  
- Revenue  

Derived metrics calculated for analysis:

- Click-Through Rate (CTR)  
- Cost per Click (CPC)  
- Cost per Acquisition (CPA)  
- Conversion Rate  
- Return on Investment (ROI)  

---
## Dataset
**Dataset Name:** A_B_testing_dataset.csv

The dataset contains user-level data used to perform A/B testing analysis, comparing control and variant groups.

Key columns include:
- user_id
- group (control / variant)
- conversion
- revenue (if applicable)

The dataset was used to evaluate experiment performance and statistical significance.
---

## 4. Exploratory Data Analysis (EDA)

Exploratory Data Analysis was performed to understand data distribution, variability, and overall campaign behavior.

### Key EDA Activities
- Summary statistics for clicks, conversions, spend, and revenue  
- Comparison of average CTR, CPC, CPA, and ROI by platform  
- Identification of outliers and anomalies  
- Visualization of metric distributions  

EDA helped establish baseline performance differences and guided further statistical analysis.

---

## 5. Campaign Performance Comparison

A comparative analysis was conducted to evaluate differences between Facebook Ads and Google Ads across key performance indicators.

### Metrics Compared
- Click-Through Rate (CTR)  
- Conversion Rate  
- Cost per Click (CPC)  
- Cost per Acquisition (CPA)  
- Return on Investment (ROI)  

This comparison provides an initial descriptive understanding of platform efficiency and effectiveness.

---

## 6. A/B Testing and Hypothesis Formulation

A/B testing was applied to statistically validate observed differences in performance.

### Hypotheses

- **Null Hypothesis (H₀):**  
  There is no statistically significant difference in campaign performance between Facebook Ads and Google Ads.

- **Alternative Hypothesis (H₁):**  
  There is a statistically significant difference in campaign performance between Facebook Ads and Google Ads.

A two-sample statistical test was conducted at a **95% confidence level (α = 0.05)** on key metrics such as conversion rate and CPA.

---

## 7. Regression Analysis

Regression modeling was used to identify the factors influencing campaign success.

### Model Objective
To quantify the impact of platform choice and engagement metrics on conversions and ROI.

### Model Structure
- **Dependent Variables:**  
  - Conversions  
  - ROI  

- **Independent Variables:**  
  - Advertising platform (Facebook = 0, Google = 1)  
  - Advertising spend  
  - Click volume  
  - Cost per Click (CPC)  
  - Click-Through Rate (CTR)  

Regression coefficients and p-values were analyzed to identify statistically significant predictors.

---

## 8. Time Series Analysis

Time series analysis was conducted to evaluate campaign performance trends over time.

### Objectives
- Identify trends in clicks, conversions, and spend  
- Detect seasonality or fluctuations  
- Compare platform stability and consistency  

Daily metrics were analyzed to assess sustained performance patterns.

---

## 9. Key Insights

- Statistically significant performance differences were observed between platforms  
- Platform choice, ad spend, and click volume strongly influenced conversions  
- Cost efficiency metrics such as CPA directly impacted ROI  
- Time series analysis revealed differences in performance consistency  

---

## 10. Conclusion and Business Recommendation

By combining **EDA, A/B testing, regression analysis, and time series analysis**, this project delivers a comprehensive evaluation of marketing campaign performance.

The findings support data-driven budget allocation decisions, helping organizations optimize marketing spend, improve conversion efficiency, and maximize ROI.

---

## 11. Tools and Skills Demonstrated

- Exploratory Data Analysis (EDA)  
- A/B Testing and Hypothesis Testing  
- Regression Modeling  
- Time Series Analysis  
- Marketing Analytics  
- Business-Oriented Data Interpretation  
