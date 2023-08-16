# UMADS-Capstone
UMADS Capstone 2023 - Analyzing real estate market trends over time

## Data
The team leverages Zillow Research Housing Data to create an ARIMA model to forecast home appreciation.
The Zillow_data.zip folder contains the following datasets:
- home_value.csv: This index reflects the typical home value across the metropolitan areas, states, counties, and zip codes of the United States. 
- forecasts.csv: A month-ahead, quarter-ahead, and year-ahead forecast of the Zillow Home Value Index (ZHVI). These forecasted values are used to compare against the model’s predicted results.
- for_sale_inventory.csv: The count of unique listings of homes for sale.
- new_listings.csv: The number of properties that have been newly listed for sale within a specific time frame. 
- median_sale_to_list.csv: The ratio of final sale price to the original listing price.
- homes_sold_above.csv: Percentage of home sales where the sale price is higher than the original listing price. 
- mean_days_to_close.csv: The average number of days it takes for a property or home to transition from being listed for sale to being sold and closed.
- price_cut.csv: Displays the percentage of properties with a list price lower than the original listing price.
- mortgage_rates.csv: 30-Year mortgage rates over time

## Home appreciation predictive model
The team created an ARIMA predictive model using the data above. The model can be run by downloading the attached Jupyer notebook (Metro Data Preprocessing&Prediction.ipync) and running it on an IDE such as Visual Studio.

## Tableau home market trends dashboard
The team created an interactive Tableau dashboard to visualize the housing market trends of the past 5 years (2018-2023).

[Tableau Dashboard](https://public.tableau.com/app/profile/ayrton.trujillo/viz/CapstoneRealEstateMarketDashboard/RealEstateMarketTrends)

