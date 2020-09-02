# Regression Model Vehicle price analysis
 
  Exploratory analysis and model creation to predict the value of various vehicles according to characteristics
 
 # [Project  : Regression Model Vehicle price analysis ](https://github.com/bezerraluis/Modelo-de-Regressao-Analise-de-preco-de-veiculos/blob/master/Project_Cars_price.ipynb)

![cars](https://github.com/bezerraluis/-Main-projects/blob/master/images/cars_price.jpg)



# Problem Statement

A Chinese automobile company Geely Auto aspires to enter the US market by setting up their manufacturing unit there and producing cars locally to give competition to their US and European counterparts.

They have contracted an automobile consulting company to understand the factors on which the pricing of cars depends. Specifically, they want to understand the factors affecting the pricing of cars in the American market, since those may be very different from the Chinese market. The company wants to know:

Which variables are significant in predicting the price of a car
How well those variables describe the price of a car
Based on various market surveys, the consulting firm has gathered a large data set of different types of cars across the America market.

# Business Goal

We are required to model the price of cars with the available independent variables. It will be used by the management to understand how exactly the prices vary with the independent variables. They can accordingly manipulate the design of the cars, the business strategy etc. to meet certain price levels. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


# Data Dictionary - carprices

	Car_ID	-		Unique id of each observation (Interger)		
Symboling 	-		Its assigned insurance risk rating, A value of +3 indicates that the auto is risky, -3 that it is probably pretty safe.(Categorical) 		
carCompany	-		Name of car company (Categorical)		
fueltype	-		Car fuel type i.e gas or diesel (Categorical)		
aspiration	-		Aspiration used in a car (Categorical)		
doornumber	-		Number of doors in a car (Categorical)		
carbody	-		body of car (Categorical)		
drivewheel	-		type of drive wheel (Categorical)		
enginelocation		-	Location of car engine (Categorical)		
wheelbase	-		Weelbase of car (Numeric)		
carlength		-	Length of car (Numeric)		
carwidth	-		Width of car (Numeric)		
carheight	-		height of car (Numeric)		
curbweight	-		The weight of a car without occupants or baggage. (Numeric)		
enginetype		-	Type of engine. (Categorical)		
cylindernumber	-		cylinder placed in the car (Categorical)		
enginesize	-		Size of car (Numeric)		
fuelsystem-			Fuel system of car (Categorical)		
boreratio		-	Boreratio of car (Numeric)		
stroke	-		Stroke or volume inside the engine (Numeric)		
compressionratio	-		compression ratio of car (Numeric)		
horsepower	-		Horsepower (Numeric)		





1.The database was extracted from this Kaggle competition: https://www.kaggle.com/hellbuoy/car-price-prediction. 

2. Perform data processing

3. Conduct exploratory analysis

4. Perform creation of new variables

5. baseline creation

6. Perform Cross Validation

7.Tuning hyper parameters

8. Choosing the best model with the optimized parameters
