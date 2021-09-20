# AIDL-Recruitment
The goal of this data analysis to predict the number of followers gained in the past year, by using the given data. The data is about Twitch Streamers; their total streams, views, followers, etc.
## Data Analysis Model
I used two different data analysis models, linear regression and random forest regression to predict the number of followers gained.

### 1. Linear Regression
Linear regression model seemed to be the most common method to predict the followers gained. I used multiple linear regression model by using all data columns  - except channel names - to predict.
### 2. Random Forest Regression
Random Forest Regression is a supervised learning algorithm that uses ensemble learning method for regression. A Random Forest operates by constructing several decision trees during training time and outputting the mean of the classes as the prediction of all the trees.

## Conclusion
By comparing the accuracy of two methods, random forest regression came out to be more accurate than linear regression method. Therefore, I saved the predicition of random forest regression model to 'sample submission3.csv' and submitted to the kaggle.
