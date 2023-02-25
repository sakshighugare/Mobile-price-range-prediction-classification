# Mobile-price-range-prediction-classification
![image](https://user-images.githubusercontent.com/115976515/221350766-2f095c7a-6e73-409f-b2ba-97379c5adc59.png)



# Project summery
In the competitive mobile phone market companies want to understand sales data of mobile phones and factors which drive the prices. The objective is to find out some relation between features of a mobile phone(eg:- RAM, Internal Memory, etc) and its selling price. In this problem, we do not have to predict the actual price but a price range indicating how high the price is.

we have first started with the step knowing your data which includes loading dataset, null/missing value count etc then the next step was to know the variables , after this cleaning the data or data wrangling was done. After this we have done EDA for the project.After we have done hypothesis testing followed by Data preprocessing and then MAchine learning model implementation . We have used Logistic regression,Random forest and XG Boost.

Half of the mobile phones have Bluetooth, and half don’t have bluetooth. There is a gradual increase in battery power as the price range increases.

Ram has continuous increase with price range while moving from Low cost to Very high cost. Costly phones are lighter.

RAM, battery power, pixels plays more significant role in deciding the price range of mobile phone.

Logistic regression and XG Boost shows approx accuracy of 90% and the Random forest shows approx 87% accuracy, which shows that the data were properly classified.
Logistic Regression and XG Boost performs better than Random Forest.

# Problem Statement 
In the competitive mobile phone market companies want to understand sales data of mobile phones and factors which drive the prices. The objective is to find out some relation between features of a mobile phone(eg:- RAM, Internal Memory, etc) and its selling price. In this problem, we do not have to predict the actual price but a price range indicating how high the price is.

# Model applied and Observations:
For Test Set
|Model                   |Accuracy |  Recall  | 	Precision |	F1_score  |
|:--------------------:  |:-------:|:-------: |:----------:|:---------:|
|0.Logistic Regression   |	0.905   | 0.9050   |	0.904787  | 0.904481  |
|1. Random Forest	       |0.8625    | 0.8625   |	0.863721  |	0.862879  |
|2. Random Forest(Tuned) |	0.8800  |	0.8800   |	0.881557  |	0.880374  |
|3. XG Boost             |	0.9025	| 0.9025	 |  0.905158	| 0.902868  |
|4. XG Boost(Tuned)      |	0.9025	| 0.9025   |	0.905158	| 0.902868  |




# Conclusion


## From EDA:

we can see that, there are 4 different ranges of mobile phones. The number of elements is almost similar.

Half of the mobile phones have Bluetooth, and half don’t have bluetooth.

There is a gradual increase in battery power as the price range increases.

Ram has continuous increase with price range while moving from Low cost to Very high cost.

Costly phones are lighter.

RAM, battery power, pixels plays more significant role in deciding the price range of mobile phone.

## From ML implementation:

I have implemented 3 classification models and achieved a fairly good result for all the algorithms.

Logistic Regression

Random Forest with and without hyperparameter tuning.

XG Boost with and without hyperparameter tuning.

Logistic regression and XG Boost shows approx accuracy of 90% and the Random forest shows approx 88% accuracy, which shows that the data were properly classified.

Logistic Regression and XG Boost performs better than Random Forest.
