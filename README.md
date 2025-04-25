# Credit Policy A/B Testing Analysis
📊 Project Overview
This repository presents a comprehensive analysis of the effects of a credit policy change using multivariate A/B testing. The goal is to evaluate how the policy impacted key financial and operational metrics across various dealerships.

The analysis focuses on the following metrics:

✅ Loan approval rates

📈 Average credit scores

⚠️ Default rates

🚗 Sales volumes

🗂️ Dataset Description
The dataset contains dealership-level data, split into test and control groups. Each record includes metrics from both pre and post policy implementation periods.

Features:
dealership_id: Unique identifier for each dealership

group: Indicates if the dealership was in the test or control group

loan_approval_rate: % of loan applications approved

avg_credit_score: Average credit score of applicants

default_rate: % of loans that defaulted

sales_volume: Total number of completed sales

delta_*: Change in each key metric between pre and post periods

🔍 Key Findings
Loan Approval Rates: Mixed results across dealerships. Notably, dealership #9 saw an 18.55% increase.

Credit Scores: Overall improvement in average credit scores, typically increasing by 12 to 60 points.

Default Rates: Remained largely stable, indicating no major risk increase.

Sales Volumes: Results varied. Some dealerships experienced significant sales boosts, while others had minor declines.

🧪 Methodology
The analysis uses multivariate A/B testing to isolate and measure the true effects of the credit policy change. The methodology includes:

Pre-Post Analysis: Evaluating metric changes within the test group.

Delta Calculation: Quantifying changes across pre and post periods.

Statistical Testing: Assessing the significance of observed changes.

Correlation Analysis: Exploring relationships among key business metrics.
