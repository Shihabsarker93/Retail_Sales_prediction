Retail Sales Prediction Spring 2025
Overview
This project, developed for CSE422: Artificial Intelligence (Spring 2025), predicts customer spending (Total Spent) in a retail store using machine learning. The goal is to model purchasing behavior to support retail strategies like revenue forecasting and inventory management. The dataset includes transaction records, and we applied Linear Regression, Decision Tree, Random Forest, and Neural Network models, with Random Forest achieving the best performance (R² = 0.9754, MAPE = 3.68%).
Authors:

Md Shihab Sarker (ID: 22101516)

Date: May 15, 2025
Dataset
The dataset (retail_store_sales.csv) contains 12,575 transactions with 11 features:

Numerical: Price Per Unit, Quantity, Total Spent (target).
Categorical: Transaction ID, Customer ID, Category, Item, Payment Method, Location, Discount Applied.
Key Preprocessing:
Dropped 604 rows with missing Total Spent.
Imputed missing values (e.g., Price Per Unit with median 23.0).
Added Price Category feature.
Encoded categorical features and scaled numerical ones.



Models and Results
Four models were trained and evaluated:

Linear Regression: R² = 0.8757, MAPE = 59.28%
Decision Tree: R² = 0.9712, MAPE = 3.85%
Random Forest (Best): R² = 0.9754, MAPE = 3.68%
Neural Network: R² = 0.9724, MAPE = 9.41%

Random Forest excelled due to its ability to capture non-linear relationships. Visualizations (bar charts, scatter plots) are saved as PNGs.
Output includes:

Data exploration summaries.
Model performance metrics (R², RMSE, MAE, MAPE).
Visualizations saved as model_comparison.png, actual_vs_predicted.png, feature_importance.png.


Acknowledgments
We thank [Instructor Name] for guidance and the CSE422 course for providing the project framework.
Contact
For questions, contact:

Md Shihab Sarker:  shihabsarker650@gmail.com

