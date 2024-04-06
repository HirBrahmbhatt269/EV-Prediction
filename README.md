-: Project Goal :- 
Using electric vehicle (EV) registration information and demographic survey data, we will examine patterns and predictors of EV adoption in the state of Texas. 
We may also incorporate an analysis of EV charging station locations at a local level to determine if the patterns of EV adoption align with the distribution of EV charging stations in Austin.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
-: Data :-
Our primary data sources will be the State EV Registration Database from EV Hub and the American Community Survey (ACS). We will limit the scope of our analysis to the state of Texas.
The State EV Registration Database comprises 1,048,575 observations for the state of Texas.

For each observation, it provides the zip code to which the vehicle is registered, registration date, vehicle make, vehicle model, model year, drivetrain type, GVWR class, vehicle class, DMV snapshot ID, DMV snapshot ID date, and latest DMV snapshot flag.
We anticipate that the most relevant variables for our work will be zip code and registration date, but we will also investigate any potential clusters of vehicle types by location around the state.
(State EV registration database: https://www.atlasevhub.com/materials/state-ev-registration-data/#data)

The American Community Survey Database is an ongoing survey conducted by the U.S. Census Bureau. It provides information on various demographic, social, economic, and housing characteristics by sampling a small percentage of the population every year.
In our project, we may explore variables such as Social Characteristics, Economic Characteristics, Area housing data, and Race and ethnicity-related data with selected years and regions.
Data from ACS portal :- 

(1) Selected Social Characteristics in the United State : https://data.census.gov/table?q=DP02 
This dataset provides information on the social characteristics of the population, comprising 18 different parameters.

(2) Selected Economic Characteristics : https://data.census.gov/table?q=DP03
This dataset offers economic information about the population, utilizing 8 parameters.

(3) Area-wise Housing Data - can be superimposed on the EV-vehicle data that we obtained : https://data.census.gov/table?q=DP04
This dataset provides information about the housing profile of the region. We aim to ascertain if there is any relation between the two.

(4) Race and Ethnicity Related Data : https://data.census.gov/table?q=DP05
This dataset offers information about the race of the population, utilizing more than 25 parameters.

(5) For the pattern recognition of EV Charging stations in Austin, we will use Texas Utilities and City Services’ data of EV Charging stations provided by Austin Energy.
This dataset consists of geographical information about the locations of these stations, such as address lines and postal codes.
Additionally, there is a column ‘Usage Access’ which records data about the accessibility of each station, allowing us to observe whether a charging station is exclusive to a workplace, an educational facility, or accessible to all. The dataset comprises 682 rows for 17 columns, with each row representing a station situated in Austin. 
EV Charging Stations Dataset: https://data.austintexas.gov/Utilities-and-City-Services/Plug-In-EVerywhere-Charging-Station-Network/k5hp-eece/about_data

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

