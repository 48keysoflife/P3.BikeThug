# Pedaling Against Theft: An Analysis of the Rise in Bicycle Theft in Toronto

Did you know that over 3,000 bicycles are reported stolen annually in Toronto? Cycling, a popular mode of transport and recreation, has become integral to Toronto’s urban culture. Unfortunately, the rise in cycling’s popularity has also fueled a surge in bicycle thefts.

This project dives deep into Toronto's bicycle theft data to uncover patterns, analyze hotspots, and provide actionable recommendations. By leveraging big data and analytical methods, our goal is to address this pervasive issue and make cycling safer for all.

**Overview of Files**
1. ```Bike_Theft_Filter.ipynb```: Parses Toronto Police Services Bike Theft CSV file.
2. ```budget_filter.ipynb```: Parses Toronto Police Services Budget by Command CSV file. 
3. ```Homeless_Shelters_Locations.ipnyb```: Parses City of Toronto Daily Homeless Shelter Service Occupation CSV file.
4. ```neighbourhood_boundaries.ipnyb```: Parses City of Toronto Neighbourhoods Profiles CSV files. 

**Dataset Overview**
In our exploration of bike thefts in Toronto, we sourced data from multiple reliable open data portals to gain a comprehensive understanding of the patterns and factors influencing bike theft. Our investigation was primarily driven by data provided by the Toronto Police Service and the City of Toronto's open data repositories.

1. Toronto Police Services - Bicycle Thefts Open Data
This dataset was instrumental in offering granular details of each reported bike theft. Each row represents a unique theft with the associated data, time, location, etc. Since the time of the most recent download, a total of 37,178 bicycle thefts were reported to law enforcement and each report is populated with information from 34 different columns, excluding the index.

2. Toronto Police Services - Budget by Command Data
The budget data from the Toronto Police Service details the allocation of all monetary funds throughout Toronto Police. Entries are arranged in rows and have various attributes according to the named columns. When aggregated on a macro level, the dataset provides a good comprehension of all divisions’ budgets and on-the-ground resources.

4. The City of Toronto Daily Shelter data
This dataset provides the address and usage of all different shelter programs in the city. We wanted to reaffirm if our suspicions about the homeless population and their involvement in the underground bicycle black market were true.

5. City of Toronto - Neighbourhood Profiles
The neighbourhood profiles provide a wealth of information about the demographic and socio-economic conditions across different Toronto neighbourhoods.We extracted the information we deemed necessary such as age, income, neighbourhood geometry, popular commuting methods. This dataset required significant cleaning and formatting to distill relevant information that aligns with our project goals.

**Links to Medium Articles:**



**Workflow for TPS and City of Toronto Data:** 


