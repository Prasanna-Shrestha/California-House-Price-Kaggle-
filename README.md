This repo has a dataset from kaggle, where the project aims at building a model of housing prices to predict median house values in California using the provided dataset. The model should learn from the data and be able to predict the median housing price.

Domain: Finance and Housing

Analysis Tasks:
1) Build a model of housing prices to predict median house values in California using the provided dataset.
2) Train the model to learn from the data to predict the median housing price in any district, given all the other metrics.
3) Predict housing prices based on median_income and plot the regression chart for it.

Dataset Description:
-> longitude (signed numeric - float) : Longitude value for the block in California, USA
-> latitude (numeric - float ) : Latitude value for the block in California, USA
-> housing_median_age (numeric - int ) : Median age of the house in the block
-> total_rooms (numeric - int ) : Count of the total number of rooms (excluding bedrooms) in all houses in the block
-> total_bedrooms (numeric - float ) : Count of the total number of bedrooms in all houses in the block
-> population (numeric - int ) : Count of the total number of population in the block
-> households (numeric - int ) : Count of the total number of households in the block
-> median_income (numeric - float ) : Median of the total household income of all the houses in the block
-> ocean_proximity (numeric - categorical ) : Type of the landscape of the block [ Unique Values : 'NEAR BAY', '<1H OCEAN', 'INLAND', 'NEAR OCEAN', 'ISLAND' ]
-> median_house_value (numeric - int ) : Median of the household prices of all the houses in the block
