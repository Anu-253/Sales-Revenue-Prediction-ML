#  Sales Revenue Prediction using Multiple Linear Regression

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-150458?logo=pandas)
![Scikit Learn](https://img.shields.io/badge/Scikit--Learn-Machine_Learning-orange?logo=scikitlearn)
![Google Colab](https://img.shields.io/badge/Google_Colab-Notebook-F9AB00?logo=googlecolab&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success)

##  Project Overview

This project uses **Multiple Linear Regression** to predict monthly sales revenue based on advertising expenditure across three marketing channels:

- 📺 TV Advertising
- 💻 Digital Advertising
- 📰 Newspaper Advertising

The objective is to understand how advertising investments influence sales revenue and build a predictive model that estimates future sales based on marketing budgets.

## Problem Statement

An e-commerce company wants to analyze the relationship between its advertising expenditure and monthly sales revenue.

Using historical advertising data, a Multiple Linear Regression model is developed to:

- Identify relationships between advertising channels and sales.
- Understand the contribution of different advertising channels.
- Predict monthly sales revenue based on advertising investments.
- Evaluate model performance using regression metrics.

##  Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical computations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Scikit-learn | Machine Learning model development |
| Google Colab | Development environment |

##  Dataset Description

The dataset contains monthly advertising expenditure and corresponding sales revenue for 12 months.

All monetary values are represented in ₹ thousands.

| Feature | Description |
|---|---|
| Month | Month of observation |
| TV_Ads | TV advertising expenditure |
| Digital_Ads | Digital advertising expenditure |
| Newspaper_Ads | Newspaper advertising expenditure |
| Sales_Revenue | Monthly sales revenue (Target Variable) |

**Dataset size:** 12 observations × 5 columns.

##  Project Workflow

The project follows a standard Machine Learning workflow:

**1. Data Loading**
- Created and loaded the dataset using Pandas.

**2. Exploratory Data Analysis (EDA)**
- Examined dataset structure and statistical summaries.
- Checked for missing values.
- Explored relationships between advertising expenditure and sales.

**3. Data Visualization**
- Created monthly expenditure visualizations.
- Generated scatter plots.
- Created a correlation heatmap.

**4. Feature Selection**
- Independent Variables: TV Ads, Digital Ads, Newspaper Ads.
- Dependent Variable: Sales Revenue.

**5. Model Training**
- Split the dataset into training and testing sets.
- Applied Multiple Linear Regression using Scikit-learn.

**6. Model Evaluation**
Evaluated model performance using:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

**7. Sales Prediction**
- Compared actual and predicted sales.
- Identified the strongest advertising channel.
- Predicted sales revenue for a new advertising budget.

##  Model Performance

The model was evaluated using a 75:25 training-testing split.

| Evaluation Metric | Result |
|---|---:|
| MAE | 7.40 |
| MSE | 78.42 |
| RMSE | 8.86 |
| R² Score | 0.9894 |

The model achieved an R² score of approximately **98.94%** on the selected test split.

*Note: The dataset contains only 12 observations, with just 3 observations in the test set. These metrics are illustrative and should not be interpreted as evidence of reliable real-world predictive performance.*

##  Challenge: Predicting Monthly Sales Revenue

The company plans the following advertising expenditure:

| Advertising Channel | Investment |
|---|---:|
| TV Ads | ₹2,40,000 |
| Digital Ads | ₹75,000 |
| Newspaper Ads | ₹40,000 |

**Predicted Monthly Sales Revenue:**

### ₹5,72,719 (approximately)

This prediction was generated using the trained Multiple Linear Regression model.

##  Key Learnings

Through this project, I explored:

- Data manipulation using Pandas.
- Exploratory Data Analysis (EDA).
- Correlation analysis and heatmaps.
- Independent and dependent variables.
- Training and testing datasets.
- Multiple Linear Regression.
- Regression coefficients and intercept.
- Model evaluation metrics.
- Predictive analysis using Scikit-learn.

##  How to Run the Project

1. Clone this repository:

   ```bash
   git clone https://github.com/Anu-253/Sales-Revenue-Prediction-ML.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Sales-Revenue-Prediction-ML
   ```

3. Open the notebook using Google Colab or Jupyter Notebook.

4. Execute the cells sequentially to reproduce the analysis and predictions.

##  Project Structure

```text
Sales-Revenue-Prediction-ML/
│
├── cba_py.ipynb
└── README.md
```

##  Future Improvements

- Use a larger real-world advertising dataset.
- Perform cross-validation for more reliable evaluation.
- Compare Multiple Linear Regression with other regression algorithms.
- Explore feature importance and residual analysis.
- Improve prediction accuracy using additional relevant features.

##  Author

**Anagha P Kulkarni**

Computer Science & Engineering Student

GitHub: [@Anu-253](https://github.com/Anu-253)

---

⭐ If you find this project interesting, feel free to explore the repository!
