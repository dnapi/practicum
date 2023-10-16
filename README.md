# Projects from "Data Science" course at Yandex

The following is the list of the projects I have completed during my studies in [Yandex.Practicum](https://practicum.yandex.com/data-scientist/).
For this moment I have completed 9 our 14 projects.


| Project name  | Description | Libraries |
| :------------- | :------------- |:-------------|
| [1. Music preferences](01_yandex_music)  | We compare muisc preferences of Yandex.Music users from Moscow and St. Petersburg. Data preparation, cleaning, exploratory analysis. | *pandas* |
| [2. Сredit analysis](02_credit_scoring) | Effect of family status, number of children and income on credit repayment are considered. Data preparation, cleaning, exploratory analysis, variable categorization. | *pandas*|
| [3. Real estate analysis](03_real_estate_prices)| Predicting the market price of real estate in St. Petersburg region for detecting anomalies and fraud.. Defining features.  Data preparation, feature engineering, exploratory analysis, correlation between the real estate price and different parameters. | *pandas*, *matplotlib.pyplot* |
| [4. Profinability of tariffs for a telecom](04_telecom_tariff) | User behavior analysis for tariff profitability determination. Data preparation, cleaning, feature engineering, statistical analysis, hypothesis testing. | *pandas*, *matplotlib.pyplot*, *numpy*, *scipy.stats* |
| [5. Video games polularity](05_games)|  Analysis of historical data on games issued till 2016. Popularity prediction depending on platform, genre and market. Exploratory data analysis, user portrait analysis, hypothesis testing.| *pandas*, *matplotlib.pyplot*, *numpy*, *scipy.stats* |
| [6. Tariff recommendation](06_users_classification)| Application of Machine learning models (DecisionTreeClassifier, RandomForestClassifier, LogisticRegression) for classification of users. Adjusting of hyperparameter is perform.  The training data are historical data on user behavior.  The model can be used as recommender of suitable tariff to users. | *pandas*, *sklearn*, *numpy* |
| [7. Bank customer churn modeling](07_bank_customer_churn_modeling) | Building a machine learning model that predict customer churn using historical data on customer behavior.| *pandas*, *sklearn*, *numpy*, *matplotlib.pyplot*, *GridSearchCV* |
| [8. New oil well location](08_oil_extraction_location) | Creating a model that analyzes data from three locations for the choising the region for new oil wells that will maximize profits while minimizing risk. Profits and risk were predicted using Bootstrap technique. Linear Regression was used as a model. | *pandas*, *sklearn*, *numpy*, *scipy.stats*, *seaborn*, *matplotlib.pyplot* |
| [9. Gold recovery coefficient](09_gold_recovery) | Developing ML model that predict the efficiency of gold extracted from raw matherial. Three models have been tested: LinearRegression, DecisionTreeRegressor, RandomForestRegressor. Hyperparameters search where performed with cross-validation using  GridSearchCV. | *pandas*, *sklearn*, *numpy*, *seaborn*, *matplotlib.pyplot* , *GridSearchCV*|
| [10. Customers' personal data encryption](10_customer_data_encryption) | Data encrypting using multiplication of features by an invertible matrix. The method has been proved to be correct analytically and demonstrated numerically. The quality of linear regression is not effected by ensciption. | *pandas*, *sklearn*, *numpy* |
| [11. Car prices prediction](11_car_prices_boosting) | Building a machine learning model for car prices prediction based on historical data. Preprocessing data, Encoding categorical features with OrdinalEncoder. Models: Gradient Boosting (CatBoost,LightGBM), Random Forest, Linear model, Desicion tree. GridSearchCV was used for optimal hyperparameters search. | *pandas*, *sklearn*, *numpy*, *seaborn*, *matplotlib*, *lightgbm* |
| [12. Number of taxi orders forecast](12_time_series) | Time-series forecasting for taxi orders involved resampling data, analyzing trends and seasonality, and incorporating new features like calendar attributes, lag values, and rolling mean values. Models utilized include Linear Regression, Decision Tree, Random Forest. | *statsmodels.tsa.seasonal*, *pandas*, *sklearn*, *numpy*, *matplotlib* |
| [13. Sentiment analysis](13_nlp) | Performed text tonality analysis with initial text preprocessing and lemmatization using Spacy. The classification task utilized two distinct models: CatBoost and Logistic Regression. Tokenization was performed using both BERT and TF-IDF.| *torch*, *transformers*, *nltk*, *tqdm*,  *re*, *nltk* |
| [14. Analytics of airline customers' preferences](14_sql) | To be done |  |
















