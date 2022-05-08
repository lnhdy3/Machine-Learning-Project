# Machine-Learning-Project

## Intro
This dataset examines CO2 Emissions data for various car features. There are 7385 rows and 13 columns in this dataset. 
Using this dataset I attempt to further examine how various car features affect CO2 Emissions to better make
marketing predictions for a growingly eco-concious market. 

## Analysis
![plot 10](https://user-images.githubusercontent.com/103288613/165675663-f850c939-973b-460e-bc84-e9e8bdd7b45e.png)

CO2 Emissions for each brand of car featured in this dataset

![plot 0](https://user-images.githubusercontent.com/103288613/165675875-03cb4d0c-c301-414b-84b7-6f0d87fd11f2.png)

Boxplot showing vehicle make against CO2 Emissions.
Findings: There are no obvious trends in this plot but there are some outliers. Generally car brands have relatively
similar CO2 Emissions. With the majority being in the 200-300 g/km range. 

![plot 2](https://user-images.githubusercontent.com/103288613/165676080-0d86da16-4b22-4220-a5a8-b3b4a65b2eae.png)

Findings: Demonstrates a general trend that as combined miles per/gallon(city/highway) increases, CO2 Emissions decreases. 

![download](https://user-images.githubusercontent.com/103288613/165676357-c2d94168-f62a-43bc-bbbe-f4446601c60d.png)
Heatmap

## Cylinders
![plot 4](https://user-images.githubusercontent.com/103288613/165676410-9332633f-f7e2-46f5-b5e9-3e2c2cdcd422.png)
Barplot showing cylinders versus CO2 Emissions. This barplot highlights that as the number of cylinders increases, so too does CO2 Emissions. 

## Fuel Type
![plot 5](https://user-images.githubusercontent.com/103288613/165676520-430e03eb-7019-4669-95f1-e0218f796c90.png)
Barplot of fuel type versus CO2 Emissions. Fuel type N has the lowest CO2 Emissions and fuel type E has the highest CO2 Emissions. 

## Plan for Prediction
Through my work with this dataset, I found that the number of cylinders has a great impact on predicting CO2 Emissions. It was also found that 
combined miles per/gallon of a vehicle was an indicator of CO2 Emissions. With lower mpg indicating higher CO2 Emissions and higher mpg indicating 
lower CO2 Emissions. To better predict CO2 Emissions for marketing purposes (vehicles with lower emissions for growing market) I would want
to further analyze the Cylinders, Fuel Consumption, and CO2 Emissions columns. 

# Machine Learning Project Part 2
## Data Preparation
### Link to kaggle dataset used: https://www.kaggle.com/datasets/prathamtripathi/co2-emissions-by-cars-in-canada
##### Plot the distribution of target values in dataset
![final4](https://user-images.githubusercontent.com/103288613/167292913-f0c21af1-4ef2-4341-870d-b356f5ef8006.png)


##### Look for NA or missing values
I found no missing values

##### Label encoded vs one-hot encoded 
One-hot encoded column Fuel Type resulting in:
![final5](https://user-images.githubusercontent.com/103288613/167293502-5f5df1d9-2b81-4c29-8208-dd6f5f0bbd68.JPG)

#### Steps 3 & 4
Kept columns which I found important for mapping CO2 Emissions. Agrregated CO2 Emissions with mean and standard deviation.
one-hot encoded fuel type and label encoded make, vehicle class. 

###### Two plots I did 
![final3](https://user-images.githubusercontent.com/103288613/167069062-dcb46314-79d8-423d-8097-3ef7a9e0feeb.JPG)

![final4](https://user-images.githubusercontent.com/103288613/167069091-520b941f-b8bf-4405-a57c-65ad1d19edd1.JPG)



