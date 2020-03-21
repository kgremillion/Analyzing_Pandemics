# Analyzing Attributes of Global Outbreak
## An Analysis by: Kati Gremillion, Jorge Rueda, & Saheed Obitayo

### Exploring the Factor of Global Outbreak
In wake of the COVID-19 global pandemic, our team asked the question "What are the characteristics of a pandemic?" We concluded the best way to find this answer was by looking at the last major pandemic, which was AH1N1. We took it a step further and also looked at AH1 to see a bigger picture. 

We brought up three topics that could characterize a pandemic:
* Outbreak cycle trends
* Outbreak relation to population density & region proximity 
* Outbreak relation to the weather

**Main Data Source: http://apps.who.int/flumart/Default?ReportNo=12**

The data set downloaded from the WHO - World Health Organization had the following cleaning and classification process. 
The data requested is based on The Region of the Americas and takes into consideration the following years 2008-2009-2010. Our team considered those 3 years with the intention of only analyzing the initial patterns and impacts of the H1 and H1N1 influenza on the region of North America - Central and South America.

For the purpose of this data analysis, we only took into consideration H1 and H1N1 cases reported from the type A - influenza, not taking into consideration H3 - H5 - Not Subtype D.The H1 and H1N1 categories represent 66% of the total cases reported under type A - influenza for 2008 to 2010.

With the intention of covering the majority of countries in the region, we included as part of our data set those countries that sum 99% of the cases of H1 and H1N1 during the period of time we have determining. In other words from the 42 countries originally in our database 27 countries did not consider as part of the analysis due to the low number of cases reported along the period of time and also countries that didn't register data during the period of time were not included. 
The list of countries not included were: 
Bolivia, French Guiana, Guadeloupe, Jamaica, Guatemala, Martinique, Panama, Nicaragua, Turks and Caicos Is., Saint Lucia, Guyana, Haiti, Suriname, Cayman Islands, Dominica, Anguilla, Saint Kitts and Nevis, Aruba, Saint Vincent and the Grenadines, Barbados, Trinidad and Tobago, Dominican Republic, Antigua and Barbuda, Bahamas, Venezuela,Belize, Bermuda 


The remaining 15 countries represent 99% of the cases reported of H1 and H1N1 during the period of the analysis. 


### Weather Analysis 

One question we asked as we began to analyze the spread of H1N1 is "does the weather contribute to the spread of an outbreak?"

To analyze this, we broke up the data into three different sets: North America, Central America, and South America. The data was collected by finding the latitude and longitude boundaries per each region then generating a list of random cities within these boundaries and pulling the weather data from these cities.

We analyzed three parts of the weather: humidity, temperature, & wind speed. After analyzing weather data, we will cross reference the trends for the H1N1 pandemic outbreak and observe if there are correlations between the outbreak and weather patterns.

The weather data we collected was pulled from 2020 because the free API would only allow that. However, we analyzed ![another data base](https://www.climate.gov/maps-data/data-snapshots/averagetemp-monthly-cmb-2009-08-00?theme=Temperature) that showed no significant change in weather between 2008 and 2020 so we concluded the data would be a valid reflection for the time period we are studying. 

To pull this weather data, we used https://openweathermap.org/api

Supplimental Data:
* https://www.cdc.gov/flu/weekly/#VirusCharacterization
* https://gis.cdc.gov/grasp/fluview/Novel_Influenza.html
* https://www.climate.gov/maps-data/data-snapshots/averagetemp-monthly-cmb-2009-08-00?theme=Temperature
* https://data.worldbank.org/indicator/EN.POP.DNST



