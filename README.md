This project leverages machine learning to develop a regression model for predicting the prices of used cars based on various features such as brand, mileage, age, accident history, and more. The goal is to assist buyers and sellers in making informed decisions in the dynamic used car market.

Features of the Project

Dataset:
Contains 4,009 vehicle listings with features such as:

Brand & Model: Reflects brand reputation and design appeal.
Model Year: Indicates age and depreciation.
Mileage: Represents wear and tear.
Accident History & Clean Title: Highlights vehicle condition and legal ownership.
Transmission & Fuel Type: Represents buyer preferences and operating costs.

Data Preprocessing:

Addressed missing values and outliers using the Interquartile Range method.
Employed OrdinalEncoder for categorical features to reduce dimensionality while preserving relationships.
Scaled numerical features to enhance model performance.

Machine Learning Models:

Linear Regression: Established a baseline model.

Gradient Boosting Machines (GBM): Achieved superior accuracy with an RMSE of $12,200 by capturing complex feature interactions.

Evaluation Metrics:

Root Mean Square Error (RMSE): Primary metric to evaluate predictive accuracy.
Mean Absolute Error (MAE): Supplementary metric for interpretability of deviations.

Key Insights

Most Influential Features:

Model Year, Mileage, and Brand were the top contributors to price predictions.

Accident History and Clean Title significantly impacted cars with legal or damage-related concerns.

Outcome:

The final model provides actionable insights into used car valuations, ensuring fair pricing for both buyers and sellers.

Future Work

Incorporating additional features like regional market data or repair costs.
Enhancing feature interactions with advanced neural networks.
Deploying the model via a web or mobile interface for wider accessibility.

Contributors

Josh Torres: Project Lead
Mohsen Alavin: Data Organization, Software Lead
Saad Irfan: Algorithms and Analytics
Lynn Lee: Data Organization
