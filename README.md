World CO2 Emission![image](https://github.com/AnaTipps/Project_1/assets/131017970/922a6192-a452-4c05-90a5-3c5d73a609b0)

Introduction
Global warming is one of the biggest challenges currently being faced by humanity, although correlation complex is not likely to be a major single factor causing  global warming is well known the increased atmospheric carbon dioxide from human activities its an important contributor. 
![image](https://github.com/AnaTipps/Project_1/assets/131017970/37bd7903-7c27-4522-a858-910dd5ad4898)
In this analysis we will be using the "World Development Indicators" dataset, specifically the files "WDICountry.csv" to exploring the CO2 emissions data to answer 5 questions that can broad our understanding of the phenomena.
![image](https://github.com/AnaTipps/Project_1/assets/131017970/13f3b91e-14fe-47f9-82d4-247b7df8ddfc)
“We are running the most dangerous experiment in history right now, which is to see how much carbon dioxide the atmosphere can handle before there is an environmental catastrophe” - Elon Musk
![image](https://github.com/AnaTipps/Project_1/assets/131017970/c2f0b4f6-d62e-4f1b-b6cd-21ae3723cd44)

Slides
Data was cleaned to only select the relevant columns using a group by function.
Once the relevant data was selected, it was plotted on a graph to see the present day co2 emission status. We can see we are at the highest level since 1750 
![image](https://github.com/AnaTipps/Project_1/assets/131017970/65882a54-a278-415d-b0f6-a5d48603eb79)
Using Geopy and Folium, third party library for Python, the countries responsible for co2 emission in 2020 ware placed in a map. The figure below shows Europe is the largest region for co2 emission in 2020.
![image](https://github.com/AnaTipps/Project_1/assets/131017970/27341916-ddb1-43bb-8a29-6c58a5bbcc3e)
Next the source of CO2  was analysed . Again, cleaning and removing unnecessary columns using unique and group by, we can see Coal has surpassed oil in resent day as a source of CO2. 
![image](https://github.com/AnaTipps/Project_1/assets/131017970/83534fc1-331f-4991-a6d7-5ee4cae62538)
It was proved that GDP has a strong relationship whit CO2 emissions as shown in the regression analysis below.
![image](https://github.com/AnaTipps/Project_1/assets/131017970/7fdf2058-92e6-4de1-a3d6-25c112575ec4)
Not the same for population, more populated countries do not produce more CO2 than less populated ones. The data proved that populations has a week relationship whit CO2 emissions as shown in the regression analysis below.
![image](https://github.com/AnaTipps/Project_1/assets/131017970/56254ec2-cee3-4a58-8e17-8df8b0c12e6a)
From the global historical trends two significant drops in the CO2 emissions were identified 
![image](https://github.com/AnaTipps/Project_1/assets/131017970/7d974d72-1975-4d0e-8f2b-a78135a4f57b)
A data frame was created to analyse the contribution of each country to the CO2 production  of this period and data was sorted to find out the 5 top contributing countries.
![image](https://github.com/AnaTipps/Project_1/assets/131017970/7fe4aae8-cc44-43a4-bcb5-71cbe8633e56)
Same with the decade of the 2000s a data frame was created to analyse the contribution of each country to the CO2 production  of this period and data was sorted to find out the 5 top contributing countries and their trends.
![image](https://github.com/AnaTipps/Project_1/assets/131017970/9b48c5f6-39fb-472e-ad73-ce1fd7936076)

Conclusions![image](https://github.com/AnaTipps/Project_1/assets/131017970/1a9b5501-4738-4bcf-9912-6531f0a850eb)
From the data it can be observed that we are at the highest level since 1750.
Europe is the largest region for co2 emission in 2020.
Majority of CO2 emissions come from industries, interestedly coal has surpassed oil in resent day as a principal source of CO2
This analysis proved GDP is closely linked to CO2 but not Population 
While all countries will need to work together to overcome the climate change challenge, we can see that the great majority of emissions are concentrated to a relatively small group of countries based on their prevalent industries, mainly Oil and Coal.
