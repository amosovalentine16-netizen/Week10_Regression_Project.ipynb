Sales Revenue Prediction باستخدام Linear Regression
Project Overview
This project applies **Supervised Machine Learning (Regression)** to predict **Sales Revenue** based on key business factors such as advertising spend, product pricing, store size, and seasonal effects.
The project follows a complete machine learning workflow:
- Data generation
- Exploratory Data Analysis (EDA)
- Feature preparation
- Model training
- Evaluation and comparison
Objective
To build a predictive model that estimates continuous values (Sales Revenue) and provides insights to support business decision-making.
Dataset Description
The dataset contains the following features:
Feature           Description 
Advertising_Spend  Monthly marketing budget (USD) 
Product_Price      Average product price (USD) 
Store_Size         Store size (square meters) 
Holiday_Season     Whether it is a holiday season (1 = Yes, 0 = No)
Sales_Revenue      Total revenue generated (Target Variable)
Note: The dataset is synthetically generated to simulate real-world business scenarios.
Exploratory Data Analysis (EDA)
- Pairplots were used to visualize relationships between variables
- A correlation heatmap was used to identify key predictors
 Key Insights:
- Advertising Spend has a strong positive impact on revenue
- Product Price negatively affects sales
- Store Size contributes positively to revenue
- Holiday Season increases sales performance
Model Development
Models Implemented:
- Linear Regression
- Polynomial Regression
- Ridge Regression
- Lasso Regression
Model Performance
Model     R² Score 
Linear     0.771   
Polynomial  0.718   
Ridge       0.769   
Lasso       0.771   
Interpretation
- Linear Regression performed best, explaining ~77% of the variance in sales revenue
- Polynomial Regression reduced performance, indicating relationships are mostly linear
- Ridge and Lasso performed similarly, showing minimal overfitting
Visualizations
- Actual vs Predicted Sales Plot
- Residual Distribution Plot
- Correlation Heatmap
Business Insights
- Increasing advertising spend significantly boosts rrevenue
- Higher product prices may reduce sales
- Larger store sizes contribute to higher revenue
- Holiday seasons are key drivers of increased sales
 Conclusion
The Linear Regression model proved to be the most effective for this dataset due to its simplicity and strong performance.
This model can be used by businesses to:
- Forecast revenue
- Optimize pricing strategies
- Improve marketing decisions

 Tools & Technologies
- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn

 Future Improvements
- Use real-world datasets
- Apply advanced models (e.g., Random Forest, XGBoost)
- Deploy as a web app using Streamlit
- Integrate with business dashboards (Power BI)

 Author
Valentine Amoso 
Mathematics Teacher | Aspiring Data Analyst  

---
