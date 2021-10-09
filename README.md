# Worldbank_GDP
We will be using the "government expenditure on education" dataset as used in the intro. We will be deleting useless columns and analyze the data and evaluate how reshaping the dataset will help change and make analysis easier. We use the dataset found here: https://databank.worldbank.org/source/education-statistics-%5e-all-indicators and look at GDP % spending by country, verbatim to the instructions to avoid confusion. We will discuss how we tidy the data and reshape it throughout to make the dataset easier and better fot analysis as we progress.  import os import requests  import pandas as pd import numpy as np
he World Bank is an excellent place to get comparative data sets. Choose a data set from there to work with: Go to https://data.worldbank.org/ Under the "World Bank Open Data" header, choose "Browse by Indicator" At this point you will see literally hundreds of economic indicators to choose from. Feel free to choose anything that looks interesting. I chose "Government Expenditure on Education, total (% of GDP)" as an example. On the right hand side, choose "Databank". On the left side you will see the Variables tab chosen by default. My recommendation is to open the "Country" section and limit the countries in some manner. Ex: South America, Africa, etc. (the funnel icon will help filter by region). When you are satisfied with the region/countries, find the Download link in the upper-right corner and download a CSV file. Load the dataset into a dataframe. Delete the useless columns like "Series Name", "Country Code", etc. Look at your data: Are there any NaNs? Are missing values represented any other way? Is it easier to deal with missing data now or after the reshaping? If you think it is easier now, do so. Use the melt function to reshape the data into long format. Deal with missing values now if you didn't earlier Perform some minimal analysis of the data using, descriptive statistics, the groupby function, aggregation functions, etc."

dataset description
We will be using the "government expenditure on education" dataset as used in the intro. We will be deleting useless columns and analyze the data and evaluate how reshaping the dataset will help change and make analysis easier. We use the dataset found here: https://databank.worldbank.org/source/education-statistics-%5e-all-indicators and look at GDP % spending by country, verbatim to the instructions to avoid confusion. We will discuss how we tidy the data and reshape it throughout to make the dataset easier and better fot analysis as we progress.
