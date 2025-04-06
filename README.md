# Customer Churn Rate Analysis

# Table of Contents
1. Executive Summary
2. Introduction
   
   2.2. Background of Objectives
   
   2.3. Scope of Analysis
   
3. Key Findings
   
   3.2. Churn by Demographics
   
   3.3. Churn by Subscription time
   
4. Recommendation and Actionable Insight
   
# 1. Executive Summary

This interactive Power BI dashboard delivers a comprehensive and actionable analysis of customer churn for TechX Telecommunications, empowering the company to proactively address and mitigate factors driving customer attrition. By integrating a rich dataset encompassing customer demographics, service utilization, and billing details, this dashboard transforms complex data into clear, compelling visualizations.

The dashboard's core functionality centers on identifying key drivers of churn. Interactive charts and slicers enable a granular exploration of churn rates across diverse customer segments, including gender, senior citizen status, partner/dependent presence, and tenure. This allows TechX to pinpoint specific demographics exhibiting higher churn tendencies.

Service usage patterns are meticulously analyzed, highlighting correlations between service adoption (PhoneService, InternetService, MultipleLines, OnlineSecurity, OnlineBackup, TechSupport) and customer churn. Visualizations reveal potential areas for service improvement.

![Image Alt](https://github.com/eziukwuinnocent/Images/blob/1d25454151c95f51a89a526702f8d2bc6a3a2890/CR_1.jpg)

Furthermore, the dashboard provides a detailed financial impact assessment, analyzing MonthlyCharges and TotalCharges to quantify the revenue loss associated with customer attrition. This enables TechX to prioritize retention efforts for high-value customers at risk. The relationship between payment methods, contract types, and churn is also explored, informing strategic retention initiatives.

# 2. Introduction

In today's competitive landscape, customer churn represents a significant challenge to sustained success. Losing customers not only impacts revenue but also increases acquisition costs and potentially damages brand reputation. This report addresses this critical issue by presenting a comprehensive analysis of customer churn for a period of six years. My objective is to move beyond simply quantifying attrition to understanding its root causes, allowing us to implement targeted strategies that proactively reduce churn and foster stronger customer relationships.

# 2.2. Background of Objectives

 Customer retention is a critical driver of sustainable growth and profitability for TechX Telecommunications. High churn rates can significantly impact revenue, increase customer acquisition costs, and negatively affect brand perception. Recognizing the importance of minimizing customer attrition, this analysis was initiated to gain a deeper understanding of why customers are leaving and to identify key areas for improvement in our customer experience and offerings.

The primary objectives of this Churn Analysis Report are to:

1. Quantify the overall customer churn rate for the period of six years and identify any significant trends.
  
2. Identify key drivers of churn by analyzing various customer attributes, behaviors, and interactions.

3. Segment customers based on their churn risk to enable targeted retention efforts.

4. Evaluate the churn rates across different customer segments, products and services.

5. Provide actionable recommendations based on the findings to reduce churn and improve customer loyalty.

# 2.3. Scope of Analysis

The timeframe for this Churn Analysis focused on customers' transaction data for the first six years of the company's inception. The analysis includes all customers who were active at any point during this period. Data from key sources, including our Salesforce CRM, which tracks customer demographics and interactions and Keras, our billing system, providing subscription and payment history, was integrated and transformed for analysis within Power BI. The visualizations presented in this report, created using Power BI's robust capabilities, explore churn rates across various dimensions, including but not limited to:

1. Customer demographics (e.g., Gender, SeniorCitizen [>50 years of age], Partners [married or not married], and Dependent [<18 years of age]).

2. Contract [duration of Patronage] (Month-to-Month, One year, Two year).

3. Product/service (PhoneService, OnlineSecurity, MultipleLines, InternetService, etc.).

4. PaymentMethod (Bank transfer(automatic), Credit card (automatic), Electronic check, Mailed check)

Key behavioral indicators. To facilitate this detailed analysis, Power BI's Data Analysis Expressions (DAX) language was extensively used to create calculated columns for segmenting customers based on specific criteria and to develop key performance measures related to churn rate, customer engagement, and other relevant metrics. This scope allows for a comprehensive understanding of churn patterns and the identification of correlations that can inform effective retention initiatives.

# 3. Key Findings

![Image Alt](https://github.com/eziukwuinnocent/Images/blob/b1d3e619a11b0aee8253e45a1a0f1f1b9b0fcd69/CR_2.jpg)



Ultimately, this Power BI dashboard empowers TechX to:

1. Identify and understand the root causes of customer churn.
2. Develop and implement data-driven retention strategies.
3. Optimize service offerings and pricing models.
4. Minimize revenue loss due to customer attrition.
5. Enhance overall customer satisfaction and loyalty.
   
By providing a clear and insightful view of customer churn, this dashboard serves as a vital tool for TechX to strengthen customer relationships and drive sustainable growth.

Please find attached the Power BI file for [TechX_churn_rate_analysis]. You can use it to drill down and explore the data further for a comprehensive understanding.

Download File:

https://github.com/eziukwuinnocent/Customer_Churn_Rate_Analysis/blob/cddc34fd351d4d255c9592689ffbfe18ade4df3b/TechX_churn_rate_analysis.pbix

