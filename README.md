# The 4th_1 team project. Data-Analysis-Car-Purchase
Objective 

Build a model which will make a estimate a car purchase amount. To achieve this objective we wanted to do an Exploratory Data Analysis on our dataset to understand the relationship between study variables and how they can predict the car purchase amount. Our data contains 500 unique values and 9 features. 

Dataset information

The data set has the following columns: 
 0   Customer Name        
 1   Customer e-mail      
 2   Country             
 3   Gender              
 4   Age                 
 5   Annual Salary       
 6   Credit Card Debt    
 7   Net Worth           
 8   Car Purchase Amount  

Goals
1. Identify the trends between dependent and independent variables.

2. Correlation between independent variables and dependent variable.

3. Prediction of a purchase amount based on the Machine Learning Algorithms 

Conclution

I 

Our goal with the machine learning phase was that we wanted to train a model which will predict car purchase amount based on certain factors that include 'Customer Name', 'Customer email', 'Country', 'Gender', 'Age', 'Annual Salary', 'Credit Card Debt' and 'Net Worth'. After the data analysis part we removed redundant variables such as 'Customer Name', 'Customer email and 'Country'. Prior to model training parts we checked how data would change if we use different imputation, scaling and discretization methods.

II 

We trained eight models, one RandomForestRegressor, one KNeighborsRegressor, one LinearRegression, one SVR, one XGBRegressor, one AdaBoostRegressor, one GradientBoostingRegressor and one DecisionTreeRegressor. We also implied Pipeline and used Grid Search to find the best hyperparameters and evaluated results with the following regression metrics such as mean absolute error, mean squared error and  r2 score.

III 

Among ML models that we have built for this study SVR and LinearRegression showed the most stable and accurate results in both trained and test versions whereas RandomForestRegressor performed the worst among other ML models.

IV 

We were somewhat successful in giving a general idea but because of limitations of time and data set we still have a long way to go. Looking forward, we would like to acquire more data for accurate prediction of price so that if someone wants to buy a used car they have an idea of what it would cost them beforehand and not end up paying more than the car’s worth.
