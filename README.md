# Data-Analyst-3
This repository contains the following projects:

1. "project11.ipynb"

2. "project13.ipynb"

🛠️**Libraries used**: Pandas, NumPy, Matplotlib, SciPy, Seaborn, Scikit-learn.

## 1. "Project 11"
This repository presents a sales funnel analysis of a company. The results of the A/A and A/B tests are analyzed using the **proportions test** and the **Mann-Whitney U test**. The dataset contains the user activity (date of logging, visits in the main web page, products added to the cart, payments, etc.). Visualizations and hypotheses tests are performed.

**Objective:** To clean data and create data (from the cleaned one) to determine whether there is a statistically significant difference between the samples and their proportions, considering outliers and non-normal distributions to make decisive decisions.

### Steps
First, the exploratory data analysis (EDA) is performed to show the data in the non-cleaned datasets. Second, the data preprocessing is made, which consist of filling null values, dropping duplicates, verifying if data format is correct and processing the outliers. Third, to create data from the previously cleaned one. Fourth, the formal Mann-Whitney U and the proportion tests are performed to determine if:

• There is a statistically significant difference between the samples and their proportions in the A/A test (to verify if A/A test was performed correctly).

• There is a statistically significant difference between the samples and their proportions in the A/B test.

Finally, some decisive conclusions are given.


## 2. "Project 13"
This project analyzes the information of users in a gym (gender, location, group visits, age, lifetime, average additional charges, average class frecuency, etc.) to train machine learning models to make some predictions and clustering.

**Objective:** To predict if users will cancel their subscription next month and to group customers with similar characteristics to design personalized strategies for each customer type.

### Steps
First, the exploratory data analysis (EDA) is performed to show the data in the non-cleaned datasets. Second, the data preprocessing is made, which consist of filling null values, dropping duplicates, verifying if data format is correct and processing the outliers. Third, to create data from the previously cleaned one. Fourth, to determine whether there is multiple collinearity in the data and any outliers that could pertur the training of the machine learning (ML) algorithms. Three different models will be built: **LogisticRegression** and **RandomForestClassifier** to predict if users will cancel their subscription next month; for clustering, **KMeans** to group customers with similar characteristics to design personalized strategies for each customer type. The performance of the first two algorithms is evaluated using the metrics 'accuracy', 'precision', 'recall' and using the 'silhouette value' for the 'K-means' algorithm.

Finally, conclusions are presented.
