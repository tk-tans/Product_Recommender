# Introduction
An e-commerce company wants to recommend products to its users. The company has collected only transaction data in the past. The training dataset has only 3 columns - user_id, Product bought and Order value of the product. Using this dataset, the task is to predict for all the users in the training dataset, the top 3 categories that the user might buy from.

# Data
"user_id": id associated with a user 
"product bought": the category of the product bought by the user
"order value": the money spent on the product 

# Dependencies
- numpy
- pandas
- seaborn
- matplotlib
- sklearn
- pandas_profiling

# Installation
  ```
  pip install numpy
  pip install pandas
  pip install seaborn
  pip install matplotlib
  pip install scikit-learn
  pip install pandas-profiling
  ```

# Model
The model involves finding appropriate threshold for each category of product and applying a XGB classifier to predict the overall top 3 product category.
Also, the data is resampled to alleviate the class imbalance

# Results
The trained model managed to achieve a top 3 accuracy of approximately 0.82.
