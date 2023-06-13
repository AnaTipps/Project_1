World CO2 Emission!

Global warming is one of the biggest challenges currently being faced by humanity, although correlation complex is not likely to be a major single factor causing global warming is well known the increased atmospheric carbon dioxide from human activities it’s an important contributor. 
In this analysis we will be using the "World Development Indicators" dataset, specifically the files "WDICountry.csv" to exploring the CO2 emissions data to answer 5 questions that can broad our understanding of the phenomena.
“We are running the most dangerous experiment in history right now, which is to see how much carbon dioxide the atmosphere can handle before there is an environmental catastrophe” - Elon Musk

Data was cleaned to only select the relevant columns using a group by function.
Once the relevant data was selected, it was plotted on a graph to see the present day co2 emission status. We can see we are at the highest level since 1750 
Using Geopy and Folium, third party library for Python, the countries responsible for co2 emission in 2020 ware placed in a map. 
Next the source of CO2  was analysed . Again, cleaning and removing unnecessary columns using unique and group by, we can see Coal has surpassed oil in resent day as a source of CO2. 
It was proved that GDP has a strong relationship whit CO2 emissions as shown in the regression analysis below.
Not the same for population, more populated countries do not produce more CO2 than less populated ones. The data proved that populations has a week relationship whit CO2 emissions as shown in the regression analysis below.
From the global historical trends two significant drops in the CO2 emissions were identified 
A data frame was created to analyse the contribution of each country to the CO2 production  of this period and data was sorted to find out the 5 top contributing countries.
Same with the decade of the 2000s a data frame was created to analyse the contribution of each country to the CO2 production  of this period and data was sorted to find out the 5 top contributing countries and their trends.

From the data it can be observed that we are at the highest level since 1750.
Europe is the largest region for co2 emission in 2020.
Majority of CO2 emissions come from industries, interestedly coal has surpassed oil in resent day as a principal source of CO2
This analysis proved GDP is closely linked to CO2 but not Population 
While all countries will need to work together to overcome the climate change challenge, we can see that the great majority of emissions are concentrated to a relatively small group of countries based on their prevalent industries, mainly Oil and Coal.

### Complete notbook project code can be found on the  main.ipynb file
