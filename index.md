# Data Science Portfolio

Here are some of my Data Science Projects. I have explored various machine-learning algorithms for different datasets. Feel free to contact me to learn more about my experience working with these projects.

***

**Click here to see project** [Predict Youtube Video Likes](https://github.com/alesandrsokirka/youtube_predictions_Kaggle/blob/main/youtube_project.ipynb)

<img src="images/youtube.jpg?raw=true"/>

**Skills used:** Python, Matplotlib, Linear regression, XGBRegressor 

**Project Objective:** The task of this project is to predict the like to view_count ratio of youtube videos based on the title, description, thumbnail and additional metadata.

**Quantifiable result:** We could use regression, which helps us to predict the like to view_count ratio of youtube videos. Got [**87%** accuracy](https://github.com/alesandrsokirka/youtube_predictions_Kaggle/blob/main/youtube_project.ipynb).

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

[World happiness report Analysis](https://github.com/alesandrsokirka/world_happiness_report_Kaggle/blob/main/World_Happiness_Report.ipynb)

<img src="images/happy.jpg?raw=true"/>

**Skills used:** Python, Matplotlib, Random Forest, XGBRegressor, Linear regression 

**Project Objective:** The taks of this project to visualize how each aspect affects the overall idea of happiness and predict raiting Score.

**Quantifiable result:** We could use regression and classification which helps us to predict the Score. Got [**79%** accuracy](https://github.com/alesandrsokirka/world_happiness_report_Kaggle/blob/main/World_Happiness_Report.ipynb).

- Used Random ForestXGBRegressor and Linear regression to predict the Score of happiness
- The data had quite a few categorical variables which were encoded for use in the model
- Encoded categorical variables to numeric using Sklearn due to the presence of many string columns
- Data Source: https://www.kaggle.com/unsdsn/world-happiness


***


[Amazon Fine Food Analysis Using NLP](https://github.com/alesandrsokirka/amazon_nlp/blob/main/amazon.ipynb)

<img src="images/amazon.jpeg?raw=true"/>

**Skills used:** Python, Pandas, SKlearn, TfidVectorizer 

**Project Objective:** Given a review, determine whether the review is positive or negative based on Amazon foods.

**Quantifiable result:** We could use the Score/Rating. A rating of 4 or 5 could be cosnidered a positive review. A review of 1 or 2 could be considered negative. A review of 3 is neutral and ignored. This is an approximate and proxy way of determining the polarity (positivity/negativity).

- Given a review, it is determined whether the review is positive or negative.
- Used NLP for this approach.
- A review of 1 or 2 could be considered negative. A review of 3 is nuetral and ignored.
- Data Source: https://www.kaggle.com/snap/amazon-fine-food-reviews
