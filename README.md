# California House Price Prediction using Machine Learning

This project builds a data-driven solution for predicting house prices in California by analyzing key real-estate attributes such as median income, population density, location, proximity to ocean, and housing characteristics. The model enables smarter and faster decision-making for buyers, sellers, real-estate agencies, and financial institutions.

# Business Problem

Real-estate pricing in California fluctuates significantly and is heavily influenced by both economic and geographic factors. Traditional pricing methods rely on historical averages and manual analyst judgment, which often leads to:

Overpricing → Reduced buyer interest and delayed sale

Underpricing → Revenue loss and undervaluation of assets

A machine learning–based price estimator reduces subjectivity and allows stakeholders to take data-driven investment decisions.

# Project Objectives
Goal	Outcome
Identify key drivers behind property pricing	Feature engineering + EDA insights
Predict house prices with high accuracy	Multiple regression model comparison
Build an interpretable ML system	Explainability through feature importance
Provide insights for real-estate decision-makers	Pricing strategy recommendations
# Machine Learning Workflow

Data Cleaning & Preprocessing

Outlier removal, missing values imputation

Categorical encoding and feature scaling

Exploratory Data Analysis (EDA)

Geographical housing heatmaps

Correlation between income, location, and pricing

Neighborhood-wise price segmentation

Model Development

Linear Regression

Random Forest Regressor

Gradient Boosting / XGBoost (if applied)

Hyperparameter tuning and cross-validation

Evaluation Metrics

MAE, MSE, RMSE, R² Score

# Key Insights from the Model
Factor	Impact on Pricing
Location & proximity to ocean	Very high
Median household income	High
Population density	Medium
Housing age	Moderate
Rooms-to-bedrooms ratio	Moderate

These insights can be used strategically by real-estate platforms and agencies.
<img width="1034" height="541" alt="Screenshot 2025-12-02 190207" src="https://github.com/user-attachments/assets/91b875da-7ae5-41af-9db8-a3c3c76cf029" />

# Business Use Cases
Stakeholder	Value Delivered
Real-estate agencies	Price optimization & competitive listing
Buyers & sellers	Fair valuation before negotiation
Banks / loan companies	Accurate mortgage and risk assessment
Property investment groups	Identify undervalued high-ROI areas
Government & policy analysts	Housing demand and affordability studies
# Future Scope

Planned enhancements to make the model more robust and production-ready:

Integrate real-time market pricing API for up-to-date predictions

Build a Streamlit / Flask web app for end-user interaction

Add geospatial features (latitude-longitude clustering)

Train on multi-state US housing dataset for broader market trends

Introduce SHAP-based model explainability for transparent decision-making

Deploy on AWS / Azure / GCP with CI/CD pipeline for scalability


# Tech Stack

Python | Pandas | NumPy | Scikit-learn | Matplotlib | Seaborn | Jupyter Notebook
