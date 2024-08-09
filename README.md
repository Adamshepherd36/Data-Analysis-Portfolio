# Adam Shepherd - Data Analyst Portfolio

## About
Hi, I'm Adam! I have an analytical background in Accounting and Finance and currently. I have developed a strong foundation in the world of data and have a passion for using data to uncover meaningful insights. I am excited to bring my technical and analytical skills to the field of data science as an entry-level data specialist. 

During my studies, I honed my ability to work with complex data and developed a keen eye for identifying patterns and trends. I also gained experience in laboratory techniques, data management, and statistical analysis, which I believe will be valuable assets in my role as a data specialist.

In my free time, I enjoy exploring new data analysis tools and techniques, and I am always looking for opportunities to expand my knowledge and skills. Whether working on a team or independently, I am driven by the thrill of discovering new insights and the satisfaction of using data to solve complex problems.

My [Website](https://adamshepherd36.github.io/)
contains a simple website project designed to showcase my skills in HTML and to provide an online portfolio of my other projects.
My CV can be found [here](https://github.com/Adamshepherd36/Adamshepherd36.github.io/blob/main/CV%20-%20Adam%20Shepherd.pdf).

This is a repository to showcase skills, share projects and track my progress in Data Analytics / Data Science related topics.

## Table of Contents
- [About](https://github.com/Adamshepherd36/Data-Analysis-Portfolio#about)
- [Portfolio Projects](https://github.com/Adamshepherd36/Data-Analysis-Portfolio#portfolio-projects)
  - Python
    - [Analysis of Major Bank Stocks Performance from 2006 to 2016](https://github.com/Adamshepherd36/Data-Analysis-Portfolio#Analysis-of-Major-Bank-Stocks-Performance-from-2006-to-2016)
    - [Correlation Analysis of Movie Dataset](https://github.com/Adamshepherd36/Data-Analysis-Portfolio#Correlation-Analysis-of-Movie-Dataset)
    - [Predicting Loan Repayment for Lending Club Data](https://github.com/Adamshepherd36/Data-Analysis-Portfolio#Predicting-Loan-Repayment-for-Lending-Club-Data)  
    - [Sentiment Analysis on Yelp Reviews](https://github.com/Adamshepherd36/Data-Analysis-Portfolio#Sentiment-Analysis-on-Yelp-Reviews)  
    - [Linear Regression Analysis on E-commerce Customer Data](https://github.com/Adamshepherd36/Data-Analysis-Portfolio#Linear-Regression-Analysis-on-E-commerce-Customer-Data)  
    - [K-Means Clustering on College Data](https://github.com/Adamshepherd36/Data-Analysis-Portfolio#K-Means-Clustering-on-College-Data) 
    - [K-Nearest Neighbors Classification on Customer Data](https://github.com/Adamshepherd36/Data-Analysis-Portfolio#K-Nearest-Neighbors-Classification-on-Customer-Data)   
  - SQL
    - [SQL Data Analysis on COVID-19 Data](https://github.com/Adamshepherd36/Data-Analysis-Portfolio#SQL-Data-Analysis-on-COVID-19-Data)
  - Tableau
    - [COVID-19](https://github.com/Adamshepherd36/Projects/blob/main/AirBnB%20Project/README.md)
  - Power BI
  - Excel
    - [Bike Sales Analysis Dashboard](https://github.com/Adamshepherd36/Data-Analysis-Portfolio#Bike-Sales-Analysis-Dashboard)
    - [Financial Performance and Balance Sheet Analysis](https://github.com/Adamshepherd36/Data-Analysis-Portfolio#Financial-Performance-and-Balance-Sheet-Analysis)
  

- [Education](https://github.com/Adamshepherd36/Data-Analysis-Portfolio#education)  
- [Certificates](https://github.com/Adamshepherd36/Data-Analysis-Portfolio#certificates)
- [Contact](https://github.com/Adamshepherd36/Data-Analysis-Portfolio#contacts)



## Portfolio Projects
In this section I will list data analytics projects briefly describing the technology stack used to solve cases.



## Python

### Analysis of Major Bank Stocks Performance from 2006 to 2016
**Code:** [`Financial_Project.ipynb`](https://github.com/Adamshepherd36/Projects/blob/main/Financial_Project.ipynb)

**Goal:** To analyze and compare the stock performance of major banks from 2006 to 2016, identifying trends, correlations, and significant events affecting the stock performance.

**Description:** This project involved analyzing the stock data of six major banks: Bank of America, Citigroup, Goldman Sachs, JPMorgan Chase, Morgan Stanley, and Wells Fargo. The analysis included loading and cleaning the data, calculating daily returns, performing exploratory data analysis (EDA), and visualizing the data using various plots and statistical measures. The analysis aimed to identify trends, correlations, and significant events affecting the stock performance over the specified period.

**Skills:** Data cleaning, data analysis, financial analysis, data visualization, time series analysis, statistical analysis.

**Technology:** Python, Pandas, NumPy, Seaborn, Matplotlib, Plotly, Cufflinks.

**Results:** The analysis revealed key insights into the volatility and performance of the bank stocks. Significant findings include the identification of the most and least volatile stocks, the highest and lowest returns, and the impact of major financial events. Correlation matrices and heatmaps were used to illustrate the relationships between the different bank stocks.

### Correlation Analysis of Movie Dataset

**Goal:** To identify the factors that contribute the most to a movie's financial success, focusing on the relationship between budget and gross earnings.

**Code:** [`Movie Correlation Project.ipynb`](https://github.com/Adamshepherd36/Projects/blob/main/Movie%20Correlation%20Project.ipynb)

**Description:** The project focused on analyzing a dataset of movies released between 1980 and 2022. The dataset included movie titles, ratings, genres, release dates, budgets, gross earnings, and other relevant information. The project involved loading the data, cleaning and preprocessing it, performing exploratory data analysis (EDA), analyzing the correlation between budget and gross earnings, and implementing Pearson’s correlation statistical analysis.

**Skills:** Data cleaning, data analysis, correlation matrices, hypothesis testing, data visualization.

**Technology:** Python, Pandas, NumPy, Seaborn, Matplotlib.

**Results:** Using Python functions, the analysis revealed that votes and budget have the highest correlation with gross earnings, while the company has no significant correlation. The correlation matrices and heatmaps provided visual evidence of these relationships, highlighting the importance of budget in predicting a movie's financial success.

### Predicting Loan Repayment for Lending Club Data

**Goal:** To predict the likelihood of loan repayment for Lending Club loans using machine learning models.

**Code:** [`Predicting Repayment_Project.ipynb`](https://github.com/Adamshepherd36/Projects/blob/main/Predicting%20Repayment_Project.ipynb)

**Description:** This project involved analyzing a dataset from Lending Club containing loan information such as loan amount, loan status, grade, sub-grade, interest rate, and other relevant features. The analysis included data cleaning, handling missing values, exploratory data analysis (EDA), visualizing feature correlations, and feature engineering. The core of the project was building and training a neural network model using TensorFlow to predict loan repayment. The model's performance was evaluated using classification metrics and confusion matrices.

**Skills:** Data cleaning, data analysis, feature engineering, data visualization, machine learning, neural networks, model evaluation.

**Technology:** Python, Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn, TensorFlow, Keras.

**Results:** The neural network model achieved good predictive performance, with the classification report and confusion matrix providing detailed insights into the model's accuracy, precision, recall, and F1-score. The analysis highlighted key features influencing loan repayment and demonstrated the model's capability to predict the likelihood of repayment effectively.

## Sentiment Analysis on Yelp Reviews

**Goal:** To classify Yelp reviews as either positive (5 stars) or negative (1 star) using natural language processing and machine learning techniques.

**Code:** [`Yelp Project.ipynb`](https://github.com/Adamshepherd36/Projects/blob/main/Yelp%20Project.ipynb)

**Description:** This project involved analyzing a dataset of Yelp reviews, including features such as review text, star ratings, and other relevant information. The analysis included data cleaning, calculating text lengths, performing exploratory data analysis (EDA), and visualizing correlations between features. The core of the project was building and evaluating a machine learning model to classify reviews as positive or negative. The model utilized CountVectorizer and TfidfTransformer for text processing and a Naive Bayes classifier for prediction.

**Skills:** Data cleaning, data analysis, text processing, feature extraction, natural language processing, machine learning, model evaluation.

**Technology:** Python, Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn.

**Results:** The Naive Bayes classifier achieved good predictive performance, with confusion matrices and classification reports providing detailed insights into the model's accuracy, precision, recall, and F1-score. The analysis demonstrated the model's capability to effectively distinguish between positive and negative Yelp reviews based on text data.

## Linear Regression Analysis on E-commerce Customer Data

**Goal:** To predict the yearly amount spent by customers based on their behavior and characteristics using linear regression.

**Code:** [`Linear Regression Project.ipynb`](https://github.com/Adamshepherd36/Projects/blob/main/Linear%20Regression%20Project.ipynb)

**Description:** This project involved analyzing a dataset of e-commerce customers, including features like average session length, time on app, time on website, length of membership, and yearly amount spent. The analysis included data cleaning, performing exploratory data analysis (EDA) with visualizations, and building a linear regression model. The core of the project was to identify the key factors affecting yearly spending and to predict the spending based on these factors. The model's performance was evaluated using various regression metrics.

**Skills:** Data cleaning, data analysis, exploratory data analysis (EDA), linear regression, model evaluation, data visualization.

**Technology:** Python, Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn.

**Results:** The linear regression model successfully identified the significant factors affecting yearly spending. The model's performance was evaluated with metrics such as mean absolute error (MAE), mean squared error (MSE), root mean squared error (RMSE), and explained variance score. The analysis highlighted that length of membership and time on app were strong predictors of yearly amount spent by customers.

## K-Means Clustering on College Data

**Goal:** To classify universities into clusters based on various features using K-Means clustering.

**Code:** [`K-Means Clustering Project.ipynb`](https://github.com/Adamshepherd36/Projects/blob/main/K-Means%20Clustering%20Project.ipynb)

**Description:** This project involved analyzing a dataset of universities with features including room and board costs, graduation rate, number of undergraduates, and out-of-state tuition. The analysis included data cleaning, exploratory data analysis (EDA) with visualizations, and applying the K-Means clustering algorithm. The project aimed to cluster universities into two groups and evaluate the clustering performance using confusion matrix and classification report.

**Skills:** Data cleaning, data analysis, exploratory data analysis (EDA), clustering, model evaluation, data visualization.

**Technology:** Python, Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn.

**Results:** The K-Means clustering algorithm successfully classified the universities into two clusters. The model's performance was evaluated using a confusion matrix and classification report, which provided insights into the accuracy and effectiveness of the clustering. The analysis highlighted the differences between the clusters in terms of the various features, demonstrating the algorithm's ability to group similar universities together.

## K-Nearest Neighbors Classification on Customer Data

**Goal:** To classify customers into target classes using the K-Nearest Neighbors (KNN) algorithm.

**Code:** [`K Nearest Neighbors Project.ipynb`](https://github.com/Adamshepherd36/Projects/blob/main/K%20Nearest%20Neighbors%20Project.ipynb)

**Description:** This project involved analyzing a dataset containing customer information with various features and a target class. The analysis included data cleaning, scaling the features using StandardScaler, performing exploratory data analysis (EDA) with visualizations, and applying the K-Nearest Neighbors algorithm. The project aimed to classify customers into target classes and to evaluate the model's performance using confusion matrix, classification report, and error rate plots to determine the optimal value of K.

**Skills:** Data cleaning, data analysis, feature scaling, exploratory data analysis (EDA), classification, model evaluation, data visualization.

**Technology:** Python, Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn.

**Results:** The K-Nearest Neighbors classifier successfully classified the customers into target classes. The model's performance was evaluated using a confusion matrix and classification report, providing insights into accuracy, precision, recall, and F1-score. An error rate plot was used to determine the optimal number of neighbors (K), and the final model was retrained using this optimal value, resulting in improved classification performance.



## SQL

### SQL Data Analysis on COVID-19 Data
**Code:** [`Covid Project.sql`](https://github.com/Adamshepherd36/Projects/tree/main/Covid%20Projects)

**Description:** This project involved a series of SQL tasks to manage and analyze COVID-19 data. The tasks included selecting specific data for high-income locations, updating tables to handle null values, and creating views to calculate total cases, deaths, and vaccination percentages. Key queries were designed to calculate death rates, infection rates, and identify regions with the highest infection and death counts. Additionally, a common table expression (CTE) and temporary tables were used to facilitate complex data aggregation and analysis.

**Skills:** SQL query writing, data cleaning, data manipulation, data aggregation, creating views, handling null values, working with CTEs and temporary tables.

**Technology:** SQL, Microsoft SQL Server (or similar RDBMS).



## Excel

#### Sales Analysis Dashboard
**Code:** [`Bike Sales - Project.xlsx`](https://github.com/Adamshepherd36/Projects/blob/main/Bike%20Sales%20-%20Project.xlsx)

**Description:** This project involved analyzing bike sales data using Excel to provide insights into customer behavior, sales trends, and other key metrics. The primary objectives were to clean and prepare the data, perform data analysis, and create visualizations and dashboards to present the findings effectively. The analysis included:

- Data Import and Preparation: Imported data from multiple sheets (bike_buyers, Working Sheet, Pivot Table, and Dashboard). Cleaned and transformed the data to ensure consistency and accuracy, handling missing values and correcting data types where necessary.
- Data Analysis: Performed exploratory data analysis (EDA) to understand the distribution and relationships within the data. Analyzed key metrics such as customer demographics, purchase behavior, and sales performance.
- Data Visualization: Created various charts and graphs, including bar charts, pie charts, and line graphs. Used PivotTables to summarize and aggregate data.
- Dashboard Creation: Designed an interactive dashboard with slicers and filters to display key metrics and visualizations.

**Skills:** Data cleaning, data analysis, data visualization, dashboard creation.

**Technology:** Microsoft Excel.

#### Financial Performance and Balance Sheet Analysis
**Code:** [`Financial P&L, BS Project.xlsx`](https://github.com/Adamshepherd36/Projects/blob/main/Financial%20P%26L%2C%20BS%20Project.xlsx)

**Description:** This project involved analyzing financial data using Excel to provide insights into the company's performance and financial position. The primary objectives were to clean and prepare the data, perform financial analysis, and create visualizations and dashboards to present the findings effectively. The analysis included:

- Data Import and Preparation: Imported data from multiple sheets, including data source, balance sheets (2014-2016), P&L, fixed asset roll forward, financial liabilities, equity schedule, and cash flow. Cleaned and transformed the data to ensure consistency and accuracy.
- Financial Analysis: Performed detailed financial analysis, including calculating key metrics such as revenue, cost of goods sold, gross profit, operating expenses, EBITDA, and net income. Analyzed the components of the balance sheet, including assets, liabilities, and equity.
- Data Visualization: Created various charts and graphs to visualize the financial data, including line charts, bar charts, and tables. Used Excel formulas and functions to calculate variances and forecast future performance.
- Dashboard Creation: Designed interactive dashboards to display key financial metrics and visualizations. Included slicers and filters to allow users to customize their view of the data, enhancing interactivity and usability.

**Skills:** Data cleaning, financial analysis, data visualization, dashboard creation, forecasting.

**Technology:** Microsoft Excel.




## Education
Swansea University, UK  
Bachelor's of Science - BSc, Accouting and Finance, 2:1

Teign School Academy, UK
A & AS Level Modules:
- Math, Geography, Photography, Physics and Chemistry 



## Certificates
- [Advanced Google Analytics](https://analytics.google.com/analytics/academy/course/7) (Aug 2024) (LinkedIn - Google)
- [70-461, 761: Querying Microsoft SQL Server with Transact-SQL](https://www.udemy.com/course/70-461-session-2-querying-microsoft-sql-server-2012/) (July 2024) (Phillip Burton - Udemy)
- [Python for Data Science and Machine Learning Bootcamp](https://www.udemy.com/course/python-for-data-science-and-machine-learning-bootcamphtml) (July 2024) (Jose Portilla - Udemy)
- [Automate the Boring Stuff with Python Programming](https://www.udemy.com/course/automate/) (July 2024) (Al Sweigart - Udemy)
- [Building Interactive Dashboards with Tableau](https://www.udemy.com/course/building-interactive-dashboards-with-tableau/) (July 2024) (Packt Publishing - Udemy)
- [Power BI A-Z: Hands-On Power BI Training For Data Science!](https://www.udemy.com/course/mspowerbi/?kw=Power+BI+A-Z%3A+Hands-On+Power+BI+Training+For+Data+Science%21&src=sac) (July 2024) (Kirill Eremenko - Udemy)
- [Statistics for Data Science and Business Analysis](https://www.udemy.com/course/statistics-for-data-science-and-business-analysis/?kw=Statistics+for+Data+Science+and+Business+Analysis&src=sac) (June 2024) (365 Careers - Udemy)
- [SQL - MySQL for Data Analytics and Business Intelligence](https://www.udemy.com/course/sql-mysql-for-data-analytics-and-business-intelligence/?kw=SQL+-+MySQL+for+Data+Analytics+and+Business+Intelligence&src=sac&couponCode=ST10MT8624) (June 2024) (365 Careers - Udemy)


## Contacts
- LinkedIn: [@AdamShepherd](https://www.linkedin.com/in/adam-shepherd-710700203/)
- Email: adam.shepherd2016@outlook.com
