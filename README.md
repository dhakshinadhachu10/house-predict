Project Overview
The goal of this project is to build a regression model that can accurately estimate housing prices. By processing features like location (longitude/latitude), housing age, and proximity to the ocean, the model learns to identify the key drivers of real estate value.

🛠️ Tech Stack
Language: Python

Libraries: * pandas & numpy: Data manipulation and cleaning.

scikit-learn: Model training, data splitting, and evaluation.

RandomForestRegressor: The primary ensemble learning algorithm used for prediction.

🚀 Workflow
Data Loading: Imports the California housing dataset (CSV format).

Data Cleaning: Handles missing values in the total_bedrooms column by imputing the median.

Feature Engineering: * Converts the categorical ocean_proximity feature into numerical format using One-Hot Encoding.

Data Splitting: Divides the dataset into training (80%) and testing (20%) sets to ensure unbiased evaluation.

Model Training: Utilizes a Random Forest Regressor with 100 estimators to capture complex patterns in the data.

Evaluation: Measures performance using:

RMSE (Root Mean Squared Error): To understand the average dollar-amount deviation.

R-squared Score: To determine how much variance in price is explained by the model.

Feature Importance: Identifies which variables (e.g., median income, location) have the biggest impact on the final price.

📊 Performance Metrics
After running the script, the model outputs:

RMSE: The standard deviation of the prediction errors.

R² Score: A value closer to 1.0 indicates a highly predictive model.

Top Features: A summary of the most influential variables.

📂 How to Use
