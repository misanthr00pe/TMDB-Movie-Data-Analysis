# 🎬 TMDB-Movie-Data-Analysis

## 🧾 Project Overview
**This project explores and analyzes movie data from The Movie Database (TMDB) to uncover key trends and insights in the film industry. Using a combination of data analysis, visualization, and feature engineering, the goal is to answer questions such as:**

- What makes a movie successful in terms of popularity, revenue, or ratings?
- How do factors like genre, runtime, budget, and release date influence a movie’s performance?
- What are the trends in movie production over time, including top-producing countries and directors?

The project also includes data cleaning, handling missing values, and potentially building predictive models (e.g., to estimate revenue or popularity) using machine learning techniques.

## 🧩 Features
- **Time series model** - The model evaluates Profit Trend of the movies over the years and forecasts future trends for a given period of time.
- **Genre Prediction Model** - Classification model that takes the overview of a movie as input from the user and predicts the genre of the movie.
- **Revenue Prediction Model**- Regression Model that takes the budget, vote count and genre of a particular movie as input from the user and predicts estimated revenue from it.  
- **Rating prediction Model** - Classification Model that predicts rating category of a movie as "GOOD", "AVERAGE", "POOR" by taking vote average (within a range) as user input.
- **Cluster Model** - The model segments movies based on popularity and revenue into three groups i.e. "Low popularity & revenue","Moderate popularity & revenue","High popularity & revenue".


## 🧰 Tools & Technologies Used

- **Excel** – Utilized for preliminary data exploration
- **Python** – Core language for data manipulation, analysis, and modeling
- **Pandas & NumPy** – Efficient handling of structured data and numerical operations
- **Matplotlib & Seaborn** – For creating insightful and visually appealing data visuals
- **Tableau** - For creating interactive dashboards demonstrating insights for stakeholders
- **statsmodel & pmdarima** - For seasonal decomposition graph and Time series Analysis.
- **Feature Engineering** - StandardScaler, train_test_split, TfidfVectorizer, MultiLabelBinarizer
- **Data Sampling** - KFold, RepeatedStratifiedKFold, GridSearchCV
- **Classification Models** - LogisticRegression, GaussianNB, RandomForestClassifier, DecisionTreeClassifier, SVC, OneVsRestClassifier, SGDClassifier, xgboost
- **Regression Models** –  LinearRegression, RandomForestRegressor, DecisionTreeRegressor
- **KMeans clustering** - For segregating movies into optimal groups
- **Evaluation Metrics** - mean_squared_error, cross_val_score, classification_report, accuracy_score, f1_score, hamming_loss, precision_score, recall_score, 
- **PowerPoint** - A PowerPoint summary of the entire analysis, suitable for interviews or stakeholder meetings.





