## Ecommerce Customer Spending Analysis

This project investigates the factors influencing yearly spending by customers of an e-commerce platform. We utilize a linear regression model to understand the relationship between customer behavior (average session length, time on app/website, length of membership) and their spending patterns.

**Dataset:**

The analysis is based on the "Ecommerce Customers" dataset, containing information on customer sessions, app/website usage, membership duration, and yearly spending.

**Methodology:**

1. **Exploratory Data Analysis (EDA):**  We visualize the relationships between variables to gain insights into their distributions and correlations.
2. **Linear Regression:** A linear regression model is trained to predict yearly spending based on the selected features.
3. **Model Evaluation:** The model's performance is assessed using Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).
4. **Coefficient Interpretation:** The coefficients of the linear model are examined to understand the impact of each feature on predicted spending.
5. **Additional Analysis:** (Optional) We investigate multicollinearity and feature importance to further refine our understanding of the model.

**Key Findings:**

* Time spent on the mobile app has a significantly stronger positive impact on yearly spending compared to time spent on the website.
* Length of membership is a strong predictor of increased spending, highlighting the importance of customer loyalty.

**Recommendations:**

* Prioritize investments in enhancing the mobile app experience to drive higher customer engagement and spending.
* Develop loyalty programs and initiatives to incentivize longer memberships and foster customer retention.

**How to Run:**

1. Ensure you have the required libraries installed (`pandas`, `scikit-learn`, `seaborn`, `matplotlib`).
2. Place the `Ecommerce Customers.csv` file in the same directory as the code.
3. Execute the `Linear Regression-Ecommerce Customers .ipynb` (or `.py`) script.
