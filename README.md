# Global-Warming-using-Ridge-Lasso
Data taken from the Gapminder organisation.(https://www.gapminder.org/data/)
The organisation collects and maintains global data sets related to important macro-level socioeconomic variables, such as education, healthcare, environment change, etc. In this assignment, we will use the carbon dioxide emissions data set to predict the factors that contribute the most to global emissions. 


The data set contains various files, each representing a variable that, you suspect, can contribute to (and, thus, predict) carbon dioxide emissions. For example, the file 'cars_trucks_and_buses_per_1000_persons' contains the number of cars, trucks and buses per 1,000 persons for each country for a number of years. Similarly, the file 'industry_percent_of_gdp' contains the industrial GDP of each country as a percentage of the total GDP. You can look at the data dictionaries of all the files on the Gapminder website here(https://www.gapminder.org/data/) (Use the table at the bottom of this page). Some other important predictor variables are as follows: (Look at the website for units of measurements, etc.)

forest_coverage_percent: The percentage of land area covered by forests per country
 oil_production_per_person: Oil production per capita per country
electricity_generation_per_person: Electricity production per capita per country

TASK TO PERFORM 


In the data set, there is a file named 'co2_emissions_tonnes_per_person.csv', which contains the per capita CO2 emissions of various countries across many years. This is your target variable. Your task is to build a regression model to predict per capita CO2
emissions using all the other variables as predictors. The objective is to understand how much each predictor contributes to global  Co2 emissions. 

Note that all the files contain information across a number of years. Your task is to build a model only for the year 2014 (that's the year for which most of the data is available). Also, note that each country will be one datapoint. 
