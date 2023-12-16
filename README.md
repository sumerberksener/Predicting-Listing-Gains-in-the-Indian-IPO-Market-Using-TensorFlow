# Predicting-Listing-Gains-in-the-Indian-IPO-Market-Using-TensorFlow
In this project, I have built Deep Learning Classification models using the deep learning framework, Keras, in TensorFlow. I used a real-world IPO dataset and built a classifier algorithm to predict whether an IPO will list at profit or not.

I started out by cleaning and analysing the data. I created my target column Listing_Gains_Profit by using feature engineering techniques. Then I performed exploratory data analysis to discover how the columns in the dataset are related to each other. I used feature selection and the visualisations from the exploratory data analysis to decide which columns to use as the predictors for my model.

I used the holdout validation approach to divide the original data into train and test sets. Later on, I trained two different deep learning models using Sequential API. Although the first model wasn't very successful in predicting the target column `Listing_Gains_Profit`, the second model achieved an accuracy rating of 0.72 for the train data and 0.73 for the test data.
