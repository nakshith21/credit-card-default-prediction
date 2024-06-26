# credit-card-default-prediction.
![image](https://user-images.githubusercontent.com/102281845/190619688-2c2f44a5-7594-42e1-8869-02f151c9b7d0.png)

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

# Introduction

This project is aimed at predicting the case of customers default payments in Taiwan. From the perspective of risk management, the result of predictive accuracy of the estimated probability of default will be more valuable than the binary result of classification - credible or not credible clients.
Credit risk has traditionally been the greatest risk among all the risks that the banking and credit card industry are facing, and it is usually the one requiring the most capital. This can be proven by industry business reports and statistical data. So,
assessing,detecting and managing default risk is the key factor in generating revenue and reducing loss for the banking and credit card industry.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

# Data Pre-Processing and EDA

Here we have performed an in-depth analysis with respect to the features which are present in our dataset. Feature engineering has been done where we have performed data mining, handled the null values, and checked for correlation. Using excellent visualizations we have found that Percentage of Defaulters are smaller than the 
Non Defaulters in the given dataset and by considering sex feature we can see that Female count is higher compared to men also females have overall less default payments with respect to males and Non-Defaults have a higher proportion of Females. 
If we consider marriage feature then the most number of credit holders are single
and people who have marital status single have less default payment with respect to married people, And the age group of married around 40 years old have high defaults compared to single people, If we consider education feature then more number of credit holders are university students followed by Graduates and then High school students, Graduate and university students of age around 35 years have defaults but high school graduates of age 40 has more default compared to all. But people who are university students have less default payment with respect to graduates and high school people. 

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

# Modelling 

After brief analysis, the model building using logistic regression model, random forest regressor model and XGboost model has been built and model comparison has been done using the confusion matrix, the roc - auc curve and the precision_recall curve for all three models. The main results obtained using a Logistic Regression classifier is that we can predict with 81.4% accuracy, whether a customer is likely to default next month, by using a random forest classifier we can predict with 81.5% accuracy, whether a customer is likely to default next month and also by using a XG_boost classifier we can predict with 81.9% accuracy, whether a customer is likely to default next month.


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

# Conclusion

The exploratory data analysis and modelling for Credit card default prediction dataset has been successfully done and the above inferences have been made from the obtained visualisations and the predictions from the dataset.
![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

