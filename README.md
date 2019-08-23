# Forecasting using Facebook Prophet

Prophet is a procedure for forecasting time series data based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects. 

It works best with time series that have strong seasonal effects and several seasons of historical data.

Link: https://facebook.github.io/prophet/

# Dataset Used

This data was downloaded from the Hass Avocado Board website in May of 2018 & compiled into a single CSV. 

Here's how the Hass Avocado Board describes the data on their website: https://hassavocadoboard.com/

Some relevant columns in the dataset:

- Date - The date of the observation
- AveragePrice - the average price of a single avocado
- type - conventional or organic
- year - the year
- Region - the city or region of the observation
- Total Volume - Total number of avocados sold
- 4046 - Total number of avocados with PLU 4046 sold
- 4225 - Total number of avocados with PLU 4225 sold
- 4770 - Total number of avocados with PLU 4770 sold
