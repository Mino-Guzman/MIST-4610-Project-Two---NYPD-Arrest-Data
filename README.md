# MIST-4610-Project-Two---NYPD-Arrest-Data
## Team Members
1) Mino Guzman
2) Casey Whichard - https://github.com/caseywhichard/Project-2---NYPD-Arrest-Data 
3) Ally McVay https://github.com/allymcvay/NYP-Arrest-Data 
4) Sydney Pratt -  https://github.com/scp31975/Project-2-NYPD-Arrest-Data-Year-to-Date

## Dataset Description
The NYPD Arrest Data Set was published by the City of New York on Data.gov with the provided metadata being modified most recently on 02/09/26. The dataset contains 19 clearly defined fields (columns) and a total of 278,953 rows. The columns within the dataset include ARREST_KEY, ARREST_DATE, PD_CD, PD_DESC, KY_CD, OFNS_DESC, LAW_CODE, LAW_CAT_CD, ARREST_BORO, ARREST_PRECINCT, JURISDICTION_CODE, AGE_GROUP, PERP_RACE, X_COORD_CD, Y_COORD_CD, Latitude, Longitude, Location. These columns help capture the key aspects of each arrest, including the type of offense committed, the legal classifications of the crime, the geographic location of the arrest, and the demographic characteristics of the suspect such as their age group, race, and sex. The data represented within the set includes a mix of data types such as integers, floats (decimal numbers), and text values. This combination of structured data allows users to easily understand patterns in police enforcement activity, for example when and where arrests occur and what types of crime are most common.


## Necessary Dataset Manipulations
There were no manipulations or calculations applied to the NYPD Arrest Dataset prior to inputting the information into Tableau. We chose to use the NYPD Arrest Dataset as it was already comprehensive, well-organized, and appropriately formatted for our analysis. Before uploading the dataset into Tableau to begin creating our visuals we, as a group, reviewed it in order to ensure that there were no missing values, inconsistencies, or formatting issues that would negatively impact our results. Therefore, since the dataset met our standards, we were able to continue without further manipulation.

## Question 1 What is the crime rate for each of the 5 boroughs?
![Question 1](Question1.png)

## Importance
Our client is the NYPD, this question is important for them to better understand, in general, where the most crimes are committed in the city. This information can help determine where its efforts and funding should be primarily spent, as the police stations in boroughs with higher crime may need more resources than stations in low crime areas. This funding could include more training for officers and advancements on weapons or state vehicles. This data relates to the dataset since each arrest listed contains the borough/location where the arrest took place, so we can therefore find the total count of crimes within each borough.

## Analysis and Results
Question 1 - What is the crime rate for each of the 5 boroughs?
 For this question, we chose to use a dashboard in Tableau showing a heat map of New York City alongside a bar chart showing total arrest count for the five boroughs. With the heat map, we were able to see that arrest activity is more concentrated in the northern and central regions, those being Manhattan and Brooklyn. The bar chart confirms this Brooklyn being the region with the highest arrest count, followed by Manhattan.

The difference between the five boroughs is likely due to many factors such as population size, density, and wealth disparities. The data visualization allowed us to see concentration and the distribution between the boroughs, which is why we wanted to drill down into the causes in question two. 

