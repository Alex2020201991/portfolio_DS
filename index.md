# Data Science Portfolio

Here are some of my Data Science Projects. I have explored various machine-learning algorithms for different datasets. Feel free to contact me to learn more about my experience working with these projects.

***

**Click here to see project** [Predict Youtube Video Likes](https://github.com/alesandrsokirka/youtube_predictions_Kaggle/blob/main/youtube_project.ipynb)

<img src="images/youtube.jpg?raw=true"/>

**Skills used:** Python, Matplotlib, Linear regression, XGBRegressor 

**Project Objective:** The task of this project is to predict the like to view count ratio of youtube videos based on the title, description, thumbnail and additional metadata.

**Quantifiable result:** We could use regression, which helps us to predict the like to view_count ratio of youtube videos. Result [**87%** accuracy](https://github.com/alesandrsokirka/youtube_predictions_Kaggle/blob/main/youtube_project.ipynb)

- Used Linear regression and XGBRegressor to predict the like to view_count ratio
- The data had quite a few categorical variables which were encoded for use in the model
- Encoded categorical variables to numeric using Sklearn due to the presence of many string columns
- Data Source: https://www.kaggle.com/c/kaggle-pog-series-s01e01

***

**Click here to see project** [Examining the effect of environmental factors and weather on demand of Bike rentals](https://github.com/alesandrsokirka/linear_regr_seoul_bikes/blob/main/final_linear_regr_seoul_bikes.ipynb) 

<img src="images/bike.jpg?raw=true"/>

**Skills used:** Python, Pandas, SKlearn, Matplotlib

**Project Objective:** Predicting Bike rental demand on basis of weather and seasonal factors in advance to take appropiate measures which finally will result in bike utilization.

**Quantifiable result:** We could predict the Bike rental demand resulting in [**76%** accuracy](https://github.com/alesandrsokirka/linear_regr_seoul_bikes/blob/main/final_linear_regr_seoul_bikes.ipynb).

- Used Random Forest Regressor to predict the number of bikes rented in the city of Seoul
- The data had quite a few categorical variables which were encoded for use in the model
- Encoded categorical variables to numeric using Sklearn due to the presence of many string columns
- Cross Validation for validating the training data and model fit.
- Fit a Random Forest Regressor with high prediction accuracy through iteration

***

**Click here to see project** [Customer Personality Analysis](https://github.com/alesandrsokirka/Customer_Personality_Analysis_Kaggle/blob/main/Customer_personality.ipynb)

<img src="images/customer.jpg?raw=true"/>

**Skills used:** Python, Matplotlib, PCA, Elbow Method

**Project Objective:** Customer Personality Analysis is a detailed analysis of a company’s ideal customers. It helps a business to better understand its customers and makes it easier for them to modify products according to the specific needs, behaviors and concerns of different types of customers.

**Quantifiable result:** We could use clustering, which helps in understanding the natural grouping in a dataset.

- Initiating PCA to reduce dimentions aka features
- Elbow Method to determine the number of clusters to be formed
- Initiating the Agglomerative Clustering model
- Data Source: https://www.kaggle.com/imakash3011/customer-personality-analysis


***

**Click here to see project** [World happiness report Analysis](https://github.com/alesandrsokirka/world_happiness_report_Kaggle/blob/main/World_Happiness_Report.ipynb)

<img src="images/happy.jpg?raw=true"/>

**Skills used:** Python, Matplotlib, Random Forest, XGBRegressor, Linear regression 

**Project Objective:** The taks of this project to visualize how each aspect affects the overall idea of happiness and predict raiting Score.

**Quantifiable result:** We could use regression and classification which helps us to predict the Score. Result [**79%** accuracy](https://github.com/alesandrsokirka/world_happiness_report_Kaggle/blob/main/World_Happiness_Report.ipynb)

- Used Random ForestXGBRegressor and Linear regression to predict the Score of happiness
- The data had quite a few categorical variables which were encoded for use in the model
- Encoded categorical variables to numeric using Sklearn due to the presence of many string columns
- Data Source: https://www.kaggle.com/unsdsn/world-happiness


***


**Click here to see project** [Amazon Fine Food Analysis Using NLP](https://github.com/alesandrsokirka/amazon_nlp/blob/main/amazon.ipynb)

<img src="images/amazon.jpeg?raw=true"/>

**Skills used:** Python, Pandas, SKlearn, TfidVectorizer 

**Project Objective:** Given a review, determine whether the review is positive or negative based on Amazon foods.

**Quantifiable result:** We could use the Score/Rating. A rating of 4 or 5 could be cosnidered a positive review. A review of 1 or 2 could be considered negative. A review of 3 is neutral and ignored. This is an approximate and proxy way of determining the polarity (positivity/negativity).

- Given a review, it is determined whether the review is positive or negative.
- Used NLP for this approach.
- A review of 1 or 2 could be considered negative. A review of 3 is nuetral and ignored.
- Data Source: https://www.kaggle.com/snap/amazon-fine-food-reviews


***


**Click here to see project** [Prediction of User Interest Using Bank Data](https://github.com/alesandrsokirka/Logistic_Regression_project_bank/blob/main/logistic__bank_portug.ipynb)

<img src="images/bank.jpg?raw=true"/>

**Skills used:** Python, Pandas, SKlearn, Matplotlib 

**Project Objective:** In this project you will be provided with real world data which is related with direct marketing campaigns (phone calls) of a Portuguese banking institution. The classification goal is to predict if the client will subscribe a term deposit (variable y).

**Quantifiable result:** We could Classify the type of tumor resulting in 86% accuracy using Logistic Regression and SMOTE. Result [**79%** accuracy](https://github.com/alesandrsokirka/Logistic_Regression_project_bank/blob/main/logistic__bank_portug.ipynb)

- In this project we are given real world data which is related with direct marketing campaigns (phone calls) of a Portuguese banking institution.
- The classification goal is to predict if the client will subscribe a term deposit (variable y).


***


**Click here to see project** [Predicting Employee Attrition](https://github.com/alesandrsokirka/employee_attrition_prediction/blob/main/employee.ipynb)

<img src="images/employee.jpg?raw=true"/>

**Skills used:** Python, Pandas, Label Encoder, Quantile, NearMiss, Random Forest, Confusion Matirx

**Project Objective:** Our goal is to predict whether the employees leave the company or not.

**Quantifiable result:** We could Classify the type of tumor using Logistic Regression and SMOTE. Result [**76%** accuracy](https://github.com/alesandrsokirka/employee_attrition_prediction/blob/main/employee.ipynb)

- LabelEncoder to handle categorical variables,
- Quantile to normalize data by divide dataset into groups,
- NearMiss to handle imbalanced data,
- Machine learning part (Data validation, Random Forest classification algorithm, Confusion matrix.
- Data Source: https://www.kaggle.com/pavan9065/predicting-employee-attrition


***


**Click here to see project** [Identifying Symptoms of Orthopedic Patients as Normal or Abnormal](https://github.com/alesandrsokirka/employee_attrition_prediction/blob/main/employee.ipynb)

<img src="images/orthopedic.jpg?raw=true"/>

**Skills used:** Python, Pandas, SKlearn, Matplotlib, KNN, NB

**Project Objective:** In this project we are provided with multiple instances of orthopedic parameters and we are also provided with their classification as Normal or Abnormal. We have to implement K Nearest Neighbor, the algorithm is used to classify points according to class of their K nearest neighbor points.

**Quantifiable result:** We could Classify the orthopedic parameters as Normal or Abnormal. Result [**82%** accuracy](https://github.com/alesandrsokirka/orthopedic_project_KNN_NB/blob/main/project__.ipynb) 

- Used the K Nearest Neighbours algorithm to classify a patient’s condition as normal or abnormal based on various orthopedic parameters
- Compared predictive performance by fitting a Naive Bayes model to the data
- Selected best model based on train and test performance


***


**Click here to see project** [Suicide Rates](https://github.com/alesandrsokirka/suicide_rate_Kaggle/blob/main/Suicide_Rates.ipynb)

<img src="images/suicide.jpg?raw=true"/>

**Skills used:** Python, Pandas, Seaborn, Matplotlib, Linear Regression, XGBooster, Random Forest

**Project Objective:**  In this project we are going to find signals correlated to increased suicide rates among different cohorts globally, across the socio-economic spectrum.

**Quantifiable result:** We could use regression, which helps us to see factors and predict suicide rate . Result [**94%** accuracy](https://github.com/alesandrsokirka/suicide_rate_Kaggle/blob/main/Suicide_Rates.ipynb) 

- Data visualization to see correlation factors 
- Machine learning: Linear regression Random forest, XGBooster.
- Selected best model based on train and test performance


***


**Click here to see project** [Identifying fraudulent transactions](https://github.com/alesandrsokirka/tree_ensemble_fraud_detection/blob/main/fraud_detection.ipynb)

<img src="images/fraud.jpg?raw=true"/>

**Skills used:** Python, Pandas, Matplotlib, Random Forest, GradientBoost Classifier, Bagging Classifier Algorithm

**Project Objective:**  In this project we are going to solve chinese bank problem of identifying fraudulent transactions in their customer's account.

**Quantifiable result:** We could Clissify, which helps to resist being frauded . Result [**92%** accuracy](https://github.com/alesandrsokirka/tree_ensemble_fraud_detection/blob/main/fraud_detection.ipynb) 

- Data visualization to see correlation factors 
- Machine learning: Random Forest, GradientBoost Classifier, Bagging Classifier Algorithm

