# House-Sale-in-King-CountyRead Me

#### Data Sources:https://www.kaggle.com/harlfoxem/housesalesprediction
#### Data Set Information:
- The description for the 20 features is given below:
- id : It is the unique numeric number assigned to each house being sold.
- date : It is the date on which the house was sold out.
- price: It is the price of house which we have to predict so this is our target variable and apart from it are our features.
- bedrooms : It determines number of bedrooms in a house.
- bathrooms : It determines number of bathrooms in a bedroom of a house.
- sqft_living : It is the measurement variable which determines the measurement of house in square foot.
- sqft_lot : It is also the measurement variable which determines square foot of the lot.
- floors: It determines total floors means levels of house.
- waterfront : This feature determines whether a house has a view to waterfront 0 means no 1 means yes.
- view : This feature determines whether a house has been viewed or not 0 means no 1 means yes.
- condition : It determines the overall condition of a house on a scale of 1 to 5.
- grade : It determines the overall grade given to the housing unit, based on King County grading system on a scale of 1 to 11.
- sqft_above : It determines square footage of house apart from basement.
- sqft_basement : It determines square footage of the basement of the house.
- yr_built : It determines the date of building of the house.
- yr_renovated : It determines year of renovation of house.
- zipcode : It determines the zipcode of the location of the house.
- lat : It determines the latitude of the location of the house.
- long : It determines the longitude of the location of the house.
- sqft_living15 : Living room area in 2015(implies-- some renovations)
- sqft_lot15 : lotSize area in 2015(implies-- some renovations)

# Project 1

I use regression to analyze the data.

## Dataset Exploration
## Scaling Data
## Regression
- KNN Regressor
- Linear regression using the Normal Equation
- Polynomial regression
- Ridge Model (L2 regularization)
- Lasso Model (L1 regularization)
- SVM simple regressor
- SVM with kernel regressor: rbf, poly, linear
## Conclusion
Conclusion: Best regression model is the KNN Regressor with k = 6  which has accuracy of 0.806.


# Project 2

I use Bagging, Pasting, Adaboost,  Gradient Boosting and Deep Learning and PCA to run the regression.

## Dataset Exploration
## Scaling Data
## Regression
- Bagging 
- Pasting
- Adaboost
- Gradient Boosting 
- Deep Learning 
- PCA
## Conclusion
Conclusion: Using data from PCA does not help in getting better regression result either training or testing process.
The best model for house price prediction in project 2 is GradientBoostingClassifier model with laerning_rate in 0.25, max_depth in 3 and n_estimators in 500,which have 0.9602 in train score and 0.8958 in test score but it might have the risk of overfitting.

