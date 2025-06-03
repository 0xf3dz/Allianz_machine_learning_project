# Allianz Client Investment Predictions

This repository contains the deliverables for the Allianz Predictive Analytics course project, which aims to develop a data-driven strategy to optimize weekly client outreach. The core goal is to identify and prioritize the 1,500 most promising clients (from a weekly pool of ~7,500 leads) based on their investment potential.

Allianz is a global financial services and insurance firm with ~$1.8 trillion in AUM. The firm seeks to maximize expected profit from client investments while minimizing outreach costs. This repository documents the evolution of our approach over five weeks, culminating in a final predictive model and strategic recommendation.

# Project Objectives

Optimize client selection each week to maximize expected profit, defined as:

Expected Profit = (Probability of Purchase × Predicted Investment) / 2
 
Ensure efficient allocation of resources by only contacting 1,500 out of 7,500 weekly leads.

Account for a 5 EUR marketing cost per contact.

Use an average 5% return on invested capital and a 22% conversion rate of current balance into new investment products.

Incorporate both classification and regression modeling across stages of the project.

Leverage historical data (period_0.csv) and iterative learning from weekly outcomes.

# Weekly Submissions

Each week, we refined our methodology to better capture client behavior and expected investment value.
Each prediction file includes the selected 1,500 clients based on the ranking strategy for that week.

# Final Report
The file Allianz_report.pdf provides:

📊 Comprehensive Analysis: Offers a full walkthrough of the data collection, preprocessing, feature engineering, and model training pipeline used to predict investor success probability.

🤖 Model Evaluation: Compares multiple classification models—including Logistic Regression, Random Forest, and Gradient Boosting—based on accuracy, precision, recall, and F1-score to identify the top 20% of potential investors.

🧪 Testing & Deployment: Includes the final test results on unseen data and discusses deployment strategies for integrating the model into Allianz’s lead management workflow.
