# Caravan-Insurance-Customer-Propensity-Segmentation-Model

📌 Project Overview

This project focuses on building an end-to-end predictive analytics solution to identify high-probability customers for caravan insurance. Using machine learning and statistical modeling, the solution enables data-driven marketing decisions, improves targeting efficiency, and maximizes return on investment (ROI).

The model analyzes customer demographics, behavioral attributes, and historical product ownership to predict insurance purchase propensity and segment customers into actionable probability-based cohorts.

🎯 Business Problem

Insurance marketing teams often face:

Low conversion rates from untargeted campaigns

High customer acquisition costs (CAC)

Inefficient allocation of marketing budgets

Objective:
Identify customers most likely to purchase caravan insurance and prioritize outreach to maximize conversions and ROI.

📊 Dataset

Records: 9,822 customers

Features: 86 demographic, behavioral, and product-related variables

Target Variable: Caravan insurance purchase (binary)

Data Source: Public insurance marketing dataset (structured tabular data)

🛠 Tools & Technologies

Programming: Python (Pandas, NumPy, Scikit-learn)

Data Analysis: Exploratory Data Analysis (EDA), Feature Engineering

Machine Learning: Logistic Regression, Decision Trees

Visualization: Power BI

Data Handling: SQL

Methods: Predictive Analytics, Statistical Modeling, Forecasting, Automation

🔄 Data Pipeline & Processing

Data Ingestion: Loaded structured customer data into Python and validated schema consistency

Data Cleaning:

Missing value imputation

Outlier detection and treatment

Data normalization and standardization

Feature Engineering & Selection:

Business-driven variable filtering

Reduction of noise from low-variance features

Exploratory Data Analysis (EDA):

Trend analysis

Correlation analysis

Distribution and class imbalance assessment

The pipeline was designed to be modular and reproducible, enabling future retraining and scalability.

🤖 Modeling & Validation

Multiple models were trained and benchmarked:

Model	Accuracy	Sensitivity (Recall)
Logistic Regression	89.45%	94.6%
Decision Tree	Benchmarked	Benchmarked

Model Selection Criteria:

High recall to minimize false negatives

Stability across cross-validation folds

Business interpretability

Evaluation Techniques:

Cross-validation

ROC-AUC

Precision–Recall analysis

📈 Key Insights & Segmentation

Customers in the top probability deciles contributed disproportionately to potential conversions

Clear high-value customer segments were identified based on demographics and product ownership

Targeted outreach to top segments significantly improves marketing efficiency

💡 Business Impact

Projected ROI uplift: +48.15%

Improved conversion efficiency through targeted marketing

Reduced CAC by prioritizing high-propensity customers

Enabled data-driven campaign planning using probability-based segmentation

📊 Visualization & Reporting

Built interactive Power BI dashboards to:

Visualize propensity score distributions

Compare customer segments

Track business KPIs (Conversion Rate, CAC, ROI)

Present insights clearly to non-technical stakeholders

⚠️ Assumptions & Limitations

Assumes historical behavior is predictive of future purchases

Dataset represents a specific market segment; generalization may vary

Model performance may change with evolving customer behavior

🚀 Future Enhancements

Integrate real-time data via APIs

Experiment with ensemble models (Random Forest, Gradient Boosting)

Deploy model using Flask/FastAPI

Automate campaign recommendations based on propensity thresholds

📌 Key Skills Demonstrated

✔ Predictive Analytics
✔ Statistical Modeling & Forecasting
✔ Machine Learning
✔ Data Engineering Fundamentals
✔ Business Insight Generation
✔ Stakeholder Communication
