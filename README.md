
# Happiness Predictor


## Table Of Contents:

1. About our Analysis
2. How this works
3. ETL Process
4. Machine Model
5. Statistics
6. Visualizations
7. What’s Next
8. Citations

## About our Analysis
● The intention of our project was to create a machine model that would be able to predict the 
happiness of countries around the world and explore different factors that impacted this 
variable. 
● To achieve this, we created and ran two different models on various datasets with different 
parameters and analyzed the performance of the model using different statistical 
techniques.
● Our dataset has various variables, including Country, Region, Subregion (Location), Life 
Ladder, Log GDP per capita, Social support, Healthy life expectancy at birth, Freedom to 
make life choices, Generosity, Perceptions of corruption, Positive affect, Negative affect, 
Various Health indicators
● From this data, we developed various visualizations using Tableau and Google Colab that 
showcase how our model works and further support our conclusion.


## How this works
![image](https://github.com/user-attachments/assets/f7a4ab49-958e-439e-accd-b61ac3da7e87)


## ETL Process

![image](https://github.com/user-attachments/assets/f49e3139-d1e0-4546-9cf3-55cf09e11086)

![image](https://github.com/user-attachments/assets/73f8285a-43c0-42d7-96f2-f4c4b468d3dd)

![image](https://github.com/user-attachments/assets/9eecd71e-1c42-4859-874d-0c33dbae4ef1)


## Machine Model

#### Random Forest vs. Gradient Boost Model

![image](https://github.com/user-attachments/assets/99adbe41-d149-4954-86af-39057df6f3b1)

![image](https://github.com/user-attachments/assets/e793f710-7671-42bd-a6f7-de144cdbae5b)

![image](https://github.com/user-attachments/assets/b061d549-5e41-42d1-a61f-1709f29a7d38)

![image](https://github.com/user-attachments/assets/31658d95-b9f3-40f9-8638-4202d875af79)


## Statistics

### Anova:

● We used an ANOVA test and were able to see that with a p-value of 0 for each feature compared to the Life Ladder, there is strong indication against the null hypothesis which suggests that each group is significantly different from our target variable. The F-statistic provided further support that there is a significant difference between the means of the groups being compared.
● Per our analysis, there is a strong statistical relationship between each feature and the Life Ladder variable. Our F-statistics showed there is a moderate to substantial difference in the Life Ladder values across different levels of each feature. The p value of 0 in each result showed there is not a difference in the Life Ladder means across different levels of values in each feature. Each feature was proven to have an impact on happiness as measured by the Life Ladder.

![image](https://github.com/user-attachments/assets/907e5040-1b79-4674-8693-75d4443f6073)

![image](https://github.com/user-attachments/assets/f8c821f1-df46-405d-83ee-70793a638a37)

#### Anova Results
![image](https://github.com/user-attachments/assets/0e2f44c3-4834-48e3-a951-418afbeb73c4)

![image](https://github.com/user-attachments/assets/18538258-59b1-4367-8671-175bb67c242a)

![image](https://github.com/user-attachments/assets/46343d8e-5061-4ce0-9e9b-a233969c8e1c)

![image](https://github.com/user-attachments/assets/4220b117-89dd-4aa8-a12c-0e1eda07bf85)

![image](https://github.com/user-attachments/assets/d98aafb5-6c48-4f2f-a78f-25f31590381a)

![image](https://github.com/user-attachments/assets/b0d5f0fe-9638-4a4d-a497-992e36fd6d7f)

![image](https://github.com/user-attachments/assets/e733b3bf-e9d4-4505-aeeb-73e7b2adf7c3)

![image](https://github.com/user-attachments/assets/fc7d6f02-26c3-4d2b-8fa3-aaf5c123e1b8)


### SQL:

● We used SQL to aggregate our data and provide further support of our conclusion that each feature impacted the life ladder/happiness values in each country. We were able to explore our data and retrieve the top happiest countries by ordering their Life Ladder in descending order, the top countries with highest GDP and the top countries with highest life expectancy.
● We wanted to see if there was a similarity in the top 10 countries and those that had the highest GDP, and life expectancy. Through our queries we were able to see there was a similarity of 1 country Switzerland. 

#### Top Happiest Countries
![image](https://github.com/user-attachments/assets/d92a1b7b-a4f2-4c87-b14e-d23634a9337d)

#### Top 10 Countries with Highest GDPs
![image](https://github.com/user-attachments/assets/ef360ea5-e540-4a68-bdff-77e4aa363beb)

#### Top 10 Countries with Highest Life Expectancy
![image](https://github.com/user-attachments/assets/4f61f432-859f-4846-a00b-1a9a750dc1e7)

● Due to this, we opened our scope to top 15 countries and joined each query to find matching countries in each query. We were able to then conclude that there was a correlation of 5 countries; Sweden, Iceland, Switzerland, Luxembourg, and the Netherlands; that had the highest happiness, GDP, and Life expectancy at birth.

![image](https://github.com/user-attachments/assets/f6387df3-b4c5-4261-a2bc-3a3528278273)

![image](https://github.com/user-attachments/assets/fad2d2a9-b680-428a-bd4b-ae1d22d77d96)




## VISUALIZATIONS


Tableau link: https://public.tableau.com/app/profile/maria.paula.ardila/viz/HappinessPredictorMLDashboard/Dashboard1

World Happiness Map:


![image](https://github.com/user-attachments/assets/252de687-db9d-4d05-9053-4ac7e0f606d7)

Top Happy Countries:


![image](https://github.com/user-attachments/assets/e5851288-1298-44fd-8a57-2d9c10db5a0e)

Feature Importance of each key variable:


![image](https://github.com/user-attachments/assets/3f42a85f-fa57-491a-91c9-38aed6451892)

## What's next:


It would be interesting to study if there is an effect of Sunshine Hours on Happiness values globally.

![image](https://github.com/user-attachments/assets/cfc86441-e9e8-4d0e-a9c2-20cdf8053f87)

## Citations

World Health data (A study health for the SDGs, Sustainable Development Goals since 2005) - https://data.who.int/
World Happiness Report (Report gathered from the Gallup World poll (GWP) 2005 - 2023) - https://worldhappiness.report/data/

