🎮 Video Game Sales Forecasting

Machine learning project that analyzes historical video game sales data to identify patterns in the gaming market and forecast future sales performance.

The goal of this project is to understand what factors influence video game success and to build models capable of predicting potential sales trends.

📌 Project Overview

The video game industry generates billions of dollars annually, and understanding what drives successful game releases is valuable for developers, publishers, and investors.

This project explores historical sales data to answer questions such as:

What factors influence video game sales?

Do platform or genre choices impact performance?

How do critic and user scores relate to sales?

Can we build models that help forecast sales trends?

The analysis combines exploratory data analysis, statistical insights, and machine learning models.

🛠️ Tools & Technologies

This project was developed using common tools used in data science workflows:

Python

Pandas — data manipulation

NumPy — numerical operations

Matplotlib / Seaborn — data visualization

Scikit-learn — machine learning

Jupyter Notebook — analysis environment

📂 Dataset

The dataset contains historical information about video games, including:

Game title

Platform

Genre

Release year

Regional sales (North America, Europe, Japan, Other regions)

Global sales

Critic scores

User scores

ESRB rating

Each row represents a single video game, while each column represents a feature that may influence sales performance.

⚙️ Project Workflow

The project follows a standard data science workflow.

1️⃣ Data Exploration (EDA)

Exploratory data analysis was conducted to understand:

Trends in global game sales

Platform popularity over time

Genre performance

Relationships between review scores and sales

Visualization and summary statistics were used to identify key market trends.

2️⃣ Data Cleaning

Before modeling, the dataset was cleaned and prepared:

Handling missing values

Converting data types

Removing unrealistic or inconsistent entries

This ensures that the analysis is based on reliable and consistent data.

3️⃣ Feature Analysis

Important features that influence game sales were examined, including:

Platform popularity

Genre distribution

Review scores

Release timing

Understanding these variables helps reveal patterns in the gaming market.

4️⃣ Model Development

Machine learning models were used to estimate and forecast sales performance.

Typical models tested include:

Linear Regression

Random Forest

Gradient Boosting

The dataset was split into training and testing sets to evaluate model performance.

5️⃣ Model Evaluation

Model performance was evaluated using metrics appropriate for regression models, such as:

RMSE (Root Mean Squared Error)

MAE (Mean Absolute Error)

R² Score

These metrics help measure how accurately the model predicts sales values.

📈 Results

The analysis revealed several important patterns:

Platform popularity changes significantly over time

Certain genres consistently perform better in specific regions

Higher review scores tend to correlate with stronger sales

The machine learning models were able to capture these patterns and generate reasonable sales forecasts.

🎯 Key Insights

Some important insights from the project include:

The gaming market evolves quickly with platform life cycles

Regional preferences play a large role in sales performance

Critic and user scores can influence sales outcomes

Data-driven analysis can help publishers make more informed decisions
