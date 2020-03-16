# Project 1
## Collaborative Data Analysis 

# Establishing the Correlation between the Global.....
In this self made project, we were tasked with gathering the economic indicators and establishing the effetcs on the World GDP per capita growth annual percentage. For this we obtained the 
ITC calcualtions based on the UN COMTRADE and ITC International trade center
API from the WOrld Health Organization showing the global pandemic over the years.

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

To pull this weather data, we used https://openweathermap.org/api

Supplimental Data:
* https://www.cdc.gov/flu/weekly/#VirusCharacterization
* https://gis.cdc.gov/grasp/fluview/Novel_Influenza.html



