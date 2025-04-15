Email Marketing Campaign Optimization
Project Overview
In this project, I analyzed an e-commerce email marketing campaign to understand its performance and explore ways to improve the Click-Through Rate (CTR) using data-driven insights and machine learning.

What I Did
1. Data Preprocessing
Loaded and merged three datasets:
email_table.csv, email_opened_table.csv, link_clicked_table.csv.

Created new binary target columns:

opened — whether the email was opened.

clicked — whether the email's link was clicked.

Handled categorical variables using One-Hot Encoding.

Scaled numeric features for model input.

2. Exploratory Analysis
Calculated:

Open Rate: 10.35%

Click-Through Rate: 2.12%

Identified class imbalance in the dataset.

Detected patterns related to:

Email text type (short vs long).

Email version (personalized vs generic).

Send hour and user country.

User past purchase history.

3. Model Development
Trained a Random Forest Classifier to predict link clicks.

Addressed class imbalance by applying SMOTE for balanced sampling.

Evaluated model using:

Classification Report

ROC-AUC Score

4. Model Results
Imbalanced Model:

ROC-AUC: 0.929

F1-Score for clicked class: 0.21

Balanced Model (SMOTE):

ROC-AUC: 0.920

F1-Score for clicked class: 0.25

Estimated that targeting the top 10% predicted users could boost CTR to 21.13% from a baseline of 2.12%.

5. Visualization and Insights
Created visual plots for:

Open vs Click Rate by Email Text Type.

Click Rate by User Country.

Click Rate by Hour Sent.

Past Purchases vs Click Behavior.

These plots revealed clear insights into how different user segments behave and how future campaigns can be optimized.

