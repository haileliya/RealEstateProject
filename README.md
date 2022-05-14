# Title: Effect of Fresh Frozen Food on Housing Prices in California 

# RealEstateProject
The purpose of the project is to understand the impact between having an influx of organic grocery stores vs. food desserts on house and rent prices in California in 2015 and 2019. 

# Motivation
The motivation of this project is to identify when and where to buy/rent a home in the United States based food access.

1. This is how grocery chains affect a home’s value
https://www.housingwire.com/articles/49767-this-is-how-grocery-chains-affect-a-homes-value/

2. Does the New Whole Foods in Your Neighborhood Increase Your Home Value?
https://realestate.usnews.com/real-estate/articles/does-the-new-whole-foods-in-your-neighborhood-increase-your-home-value


# Questions we want to answer
- What is the trend of housing prices over the last 20 years in the United States between communities with organic grocery stores versus fast-food restaurants?? 

- What is the difference appraisal value among these two groups?

- What is the difference listing value among these two groups?

- What is the difference selling value among these two groups?
 
- What is the difference in demographics among the two groups?

- Who owns more homes in areas with more organic grocery stores vs fast-food restaurants?

# Machine Learning Questions:
- Can the model accurately predict the housing prices and rent prices in locations where there is an influx of organic grocery stores vs fast-food restaurants? 
    - What will be the predicted housing interest rate?
    - When is the best time to buy a house in these two groups?

# Tools/Modules to use
- Python
- Pandas
- Matplotlib
- NumPy
- SciPy
- Postgres
- Tableau


# DATA SETS
Zillow : Mortgage Rates Current mortgage rates from Zillow Mortgage Marketplace broken down by state and loan type (30 year fixed, 15 year fixed, 5/1 ARM).
API calls of interest
GetRateSummary API: http://www.zillow.com/howto/api/GetRateSummary.htm
GetMonthlyPayments API: http://www.zillow.com/howto/api/GetRateSummary.htm
https://www.zillow.com/howto/api/APIOverview.htm

Zillow: Home Valuations
Search results list, Zestimate®, Rent Zestimate®, home valuations, home valuation charts, comparable houses, and market trend charts.
API calls of interest:
GetSearchResults API: http://www.zillow.com/howto/api/GetSearchResults.htm
GetZestimate API: http://www.zillow.com/howto/api/GetZestimate.htm
GetChart API: http://www.zillow.com/howto/api/GetChart.htm
GetComps API: http://www.zillow.com/howto/api/GetComps.htm

Whole Foods Location Dataset

Dataset includes lat and long of locations, city, state, county
https://www.scrapehero.com/store/product/whole-foods-market-store-locations-in-the-usa/
Number of locations available for download in this dataset are 509.
This data set was last updated on May 09, 2022.
$85 to purchase this dataset

Food Dessert Data 

https://www.ers.usda.gov/data-products/food-access-research-atlas/

# Action Items for 05/14/21: 12pm PST/3pm
1. everyone needs to commit to their github before saturday
2. set up API for our data via zillow
3. research the best database to use for this project (relational database)
4. finalize project write-up

# Action Items for TBD
1. Play with the data, become familiar with the data. 
2. Draft a data dictionary
3. Draft a schema for the data
4. Draft code for cleaning the data in jupyter notebook


