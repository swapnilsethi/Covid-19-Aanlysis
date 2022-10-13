# Covid-19-Analysis

## Exploratory analysis of Covid-19 data and linear regression model to predict the deaths on number of cases
 
## Introduction and Questions of Interest  

Covid-19 has affected people's lives in many ways all over the world. Today, through this analysis, we will try to understand how Covid-19 has spread over time in different countries and will analyze the spread of Covid-19 in the United Kingdom.  We will also go in depth to understand how it's spread in the different US states.  

## Data Collection  

Data was collected from John Hopkins University public GitHub repository. 

EDA:

Count of Covid-19 cases and deaths all over the world over time:

<img width="667" alt="image" src = "https://user-images.githubusercontent.com/22210769/195724470-ecb9b286-0080-41cd-bdab-36b1ce6562da.png">

Counr of Covid-19 cases and deaths in USA over time:

<img width="667" alt="image" src="https://user-images.githubusercontent.com/22210769/195724804-4ae4a907-2584-4058-b6ac-4dc27285d455.png">

Linear regression output:

<img width="667" alt="image" src="https://user-images.githubusercontent.com/22210769/195724915-653ce339-2700-4abb-ac13-c234b32d924d.png">

## Biases  

Possible Sources of biases   

#### 1. Data Collection Bias ####  
In n different ways data collection bias can occur. Some of them I am listing here:
1. people with covid not getting tested
2. possible multiple test for a person
3. Nursing house deaths not counted
4. How to count a death as a covid
5. different data from different places
6. False positive and false negative results

#### 2. Algorithm Selection Bias ####
Due to time constraints, we have linearly regressed COVID deaths with COVID cases. But the linear regression algorithm is not the best in our case.

#### 3. Result interpretation bias ####
Some doctors may analyze pneumonia as a covid or vice versa This is one example of result interpretation bias. 

## Conclusion  

There is a positive correlation between the number of cases and the number of deaths. Also, we can say that there is a positive correlation between COVID cases, deaths, and population density. As population density increases, COVID cases and deaths also increase.



