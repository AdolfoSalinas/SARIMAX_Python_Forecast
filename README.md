# SARIMAX_Python_Forecast
A demand forecast created with Python taking into account seasonality and exogenous variables.


# Step 1
Initial setup of data. Pull in truck demand data over 1.5 years
 
 ![image](https://user-images.githubusercontent.com/44706605/153674953-2bcfa6f0-38aa-4797-9c0e-3420091c8dc6.png)

 
# Step 2
Take first initial look at data
 
 ![image](https://user-images.githubusercontent.com/44706605/153674966-bee80ded-cd44-4eab-a283-2af44314c1a2.png)

 
# Step 3
Overlay holidays onto the data to determine if exogenous variables are present visually
 
 ![image](https://user-images.githubusercontent.com/44706605/153675008-3149df15-72a1-4d32-b18d-0f50585996bc.png)

 
 
# Step 4
Decompose trans to determine seasonality visually
 
 ![image](https://user-images.githubusercontent.com/44706605/153675028-0e6f8f84-cae7-404b-ba42-fcd0a4eb2c7e.png)

 
# Step 5
Setup and Train ARMIA model
 
 ![image](https://user-images.githubusercontent.com/44706605/153675052-7c698a05-4ec9-42bb-b5b5-7ce3cb30abe8.png)

 
# Step 6
Plot ARIMA versus test data
 
 
 ![image](https://user-images.githubusercontent.com/44706605/153675073-462587be-a08c-41a3-a5a5-494aa522b9f0.png)

 
# Step 7
Rerun with exogenous variables
 
 ![image](https://user-images.githubusercontent.com/44706605/153675083-74c783c4-79a6-4a2f-90a0-76bf7749ffb8.png)

 
# Step 8
Train and fit SARIMAX
 
 ![image](https://user-images.githubusercontent.com/44706605/153675099-24705d6b-7737-4624-a89d-dcd1bf933f95.png)

 
# Step 9
Plot SARIMAX versus test data
 
 ![image](https://user-images.githubusercontent.com/44706605/153675110-55a26f1f-bbca-4b8e-a198-000e814e9f71.png)

 
# Step 10
Forecast SARIMAX into the future
 

![image](https://user-images.githubusercontent.com/44706605/153675123-b8db569b-967f-449a-ab49-2be2bbe6bee9.png)
