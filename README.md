================================================================================
                        DATA ANALYSIS PORTFOLIO
                           João H. Camargo
================================================================================

Hi there! I'm João, a Data Analyst with a background in Supply Chain Operations
at Dow. I leverage hands-on experience in demand planning and production
scheduling to build data solutions grounded in real business problems — from
exploratory analysis and SQL to machine learning and big data with PySpark.

All projects are built in Python using Google Colab. You can find the full
notebooks in the Github repository linked below.

GitHub Repository:
https://github.com/Joa1Camargo/Analise-de-Dados

--------------------------------------------------------------------------------
PROJECTS
--------------------------------------------------------------------------------

1. JOÃO STORE — Retail Data Analysis
   File: Case_João_Store.ipynb

   Context:
   João Store is a Brazilian retail chain founded in 2002, with 200+ stores
   located primarily in shopping malls, operating nationwide.

   What was done:
   - Revenue analysis by month and product line
   - Analysis of best-selling products
   - New customer acquisition vs. returning customer trends
   - Marketing channel performance (Google Ads, Facebook Ads, Email, Organic)
   - Profit margin analysis by product and product line
   - Customer profile analysis (age, region, income bracket)

   Data sources used: SQLite databases (sales transactions, product info,
   customer registration), CSV (traffic origin), XLSX (media spending)

   Tools: Python, pandas, numpy, seaborn, matplotlib, SQLAlchemy

--------------------------------------------------------------------------------

2. CONTAINER DELIVERY DATE PREDICTION — Machine Learning
   File: Container_delivery_date_prediction.ipynb

   Context:
   Predicting the actual delivery date of shipping containers based on
   available logistics data, directly applicable to supply chain planning.

   What was done:
   - Data cleaning and preprocessing
   - Feature engineering (e.g., actual delivery time in days, outlier removal)
   - Machine learning modeling with Random Forest and Gradient Boosting
   - Model evaluation using MAE, MSE, and cross-validation
   - Hyperparameter tuning with GridSearchCV

   Tools: Python, pandas, scikit-learn (RandomForestRegressor,
   GradientBoostingRegressor, Ridge, Lasso, GridSearchCV)

--------------------------------------------------------------------------------

3. CREDIT RISK ANALYSIS — Classification with ML
   File: Risco_de_Credito.ipynb

   Context:
   Building a credit risk model to predict the probability of loan default,
   simulating a real use case for financial institutions.

   What was done:
   - Exploratory data analysis (EDA) on loan applicant data
   - Handling class imbalance with SMOTE
   - Testing multiple classifiers: Logistic Regression, Random Forest,
     LightGBM, CatBoost
   - Model evaluation with ROC-AUC, Precision-Recall curves, and
     Confusion Matrix
   - Iterative imputation for missing values

   Tools: Python, pandas, scikit-learn, imbalanced-learn (SMOTE), LightGBM,
   CatBoost, matplotlib, seaborn

--------------------------------------------------------------------------------

4. VEHICLE PRICE PREDICTION — Regression
   File: Previsão_Preço_de_veículos.ipynb

   Context:
   Predicting the market price of used vehicles based on their characteristics
   (age, mileage, brand, etc.).

   What was done:
   - Data reading and understanding
   - ETL: feature creation (vehicle age), column renaming
   - Exploratory Data Analysis (univariate analysis)
   - Predictive modeling: Linear Regression, Random Forest, Gradient Boosting
   - Cross-validation and hyperparameter tuning (RandomizedSearchCV)
   - Model evaluation with R² score

   Tools: Python, pandas, numpy, scikit-learn, seaborn, matplotlib

--------------------------------------------------------------------------------

5. ENERGY DEMAND FORECASTING — Time Series
   File: Previsao_demanda_Energia.ipynb (João Energy)

   Context:
   Forecasting energy demand using time series techniques, working with
   seasonality, trends, and autocorrelation patterns.

   Tools used in this project include statsmodels and Prophet, pointing to
   a time series approach (decomposition, ACF/PACF analysis).

   Tools: Python, pandas, statsmodels, Prophet (or similar forecasting libs)

--------------------------------------------------------------------------------

6. FARMASAÚDE — Demand Forecasting & Business Analysis
   File: Case_FarmaSaúde.ipynb

   Context:
   FarmaSaúde operates in the pharmaceutical, veterinary, and wellness sectors
   for over 10 years, with physical stores in Northeast Brazil and nationwide
   e-commerce. The project was structured as a real business case, answering
   strategic questions from the company's CEO.

   What was done:
   - Exploratory analysis of sales across pharmaceutical, veterinary, and
     wellness categories
   - Demand forecasting with multiple approaches:
       * ARIMA / Auto-ARIMA (pmdarima)
       * Prophet (Facebook's forecasting model)
       * XGBoost with MultiOutputRegressor and TimeSeriesSplit
   - Fourier features for seasonality modeling
   - Identification of seasonality cycles and outliers
   - Branch-level analysis revealing different demand behaviors per location

   Tools: Python, pandas, pmdarima, Prophet, XGBoost, statsmodels (ACF, PACF,
   seasonal decompose), scikit-learn, plotly, matplotlib

--------------------------------------------------------------------------------

7. PYSPARK ML — Movie Recommendation + Classification
   File: PySpark_ML.ipynb

   Context:
   Two machine learning workflows built in PySpark, covering collaborative
   filtering for movie recommendations and a classification pipeline —
   demonstrating big data tooling beyond standard pandas workflows.

   What was done:
   - Movie recommendation engine using ALS (Alternating Least Squares)
   - Binary classification model (Logistic Regression and Random Forest)
   - Cross-validation and hyperparameter tuning with PySpark ML Pipelines
   - Converting Spark DataFrames to Pandas for visualization

   Tools: Python, PySpark (SparkContext, MLlib — ALS, LogisticRegression,
   RandomForestClassifier, Pipeline, CrossValidator), matplotlib, seaborn

--------------------------------------------------------------------------------

8. SQL & EDA — Google Analytics Data (BigQuery)
   File: SQL | EDA of Google Analytics Data

   Context:
   Acting as a Data Analyst for the Google Merchandise Store, analyzing
   Google Analytics session data from BigQuery using SQL, for the period
   August 2016 to August 2017.

   What was done:
   - Extracted and explored session data from BigQuery public datasets
   - Identified most popular landing pages and bounce/exit rates
   - Analyzed sessions by browser and device type
   - Mapped the customer conversion funnel (product view → checkout →
     completed purchase)
   - Identified best-selling product categories by revenue
   - Forecasted demand for top categories using 7-day moving averages

   Tools: Python, SQL (BigQuery), pandas, seaborn, matplotlib, plotly

--------------------------------------------------------------------------------
SKILLS DEMONSTRATED
--------------------------------------------------------------------------------

Languages & Tools:
  Python, SQL, PySpark

Libraries:
  pandas, numpy, scikit-learn, LightGBM, CatBoost, XGBoost, imbalanced-learn,
  statsmodels, Prophet, pmdarima, PySpark MLlib, plotly, seaborn, matplotlib,
  SQLAlchemy

Techniques:
  Exploratory Data Analysis (EDA), Feature Engineering, Classification,
  Regression, Time Series Forecasting, Clustering, Recommendation Systems,
  Cross-Validation, Hyperparameter Tuning, SMOTE (class imbalance),
  BigQuery SQL Queries, Data Storytelling

Domain Knowledge:
  Supply Chain, Retail Analytics, Credit Risk, Pharmaceutical Demand Planning,
  E-commerce Analytics, Logistics

--------------------------------------------------------------------------------
ABOUT ME
--------------------------------------------------------------------------------

I work at Dow as a Data Analyst in Supply Chain Operations, where I deal
daily with demand planning, production scheduling, and operational data.
This real-world exposure drives my data projects — I don't just study
concepts, I apply them to problems I understand from the ground up.

My background gives me something most data candidates don't have: I know
what a bad forecast costs, what stockout pressure looks like, and why
delivery date accuracy matters. That business context shapes the way I
approach every analysis.

I'm actively looking for opportunities in Data Analyst, Data Scientist, or
Business Intelligence roles.

LinkedIn: https://www.linkedin.com/in/joaohenriquedecamargo
GitHub:   https://github.com/Joa1Camargo

================================================================================
