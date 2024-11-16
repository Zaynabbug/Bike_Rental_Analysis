# Bike Rental Analysis

## Project Overview
This project analyzes bike rental data to provide insights into demand, revenue, and rider demographics. 
SQL Server was used for data preparation and Power BI for dashboard visualization.

## Datasets description
- `bike_share_yr_0.csv`: Bike rental data for Year 0 (2021).

   ### **Columns**:
- **`dteday`**: Date (`DD/MM/YYYY`).  
- **`season`**: Season of the year (`1`: Winter, `2`: Spring, `3`: Summer, `4`: Autumn).  
- **`yr`**: Year (`0`: 2020, `1`: 2021).  
- **`mnth`**: Month (`1`: January, ..., `12`: December).  
- **`hr`**: Hour of the day (`0`–`23`).  
- **`holiday`**: `1` if holiday, else `0`.  
- **`workingday`**: `1` if a working day, else `0`.  
- **`weathersit`**: Weather condition (`1`: Clear, `2`: Mist, `3`: Light rain/snow, `4`: Heavy rain/snow).  
- **`temp`**: Normalized temperature (`0` to `1`).  
- **`atemp`**: Normalized "feels-like" temperature (`0` to `1`).  
- **`hum`**: Normalized humidity (`0` to `1`).  
- **`windspeed`**: Normalized wind speed (`0` to `1`).  
- **`rider_type`**: Rider classification (`casual`, `registered`).  
- **`riders`**: Count of riders for that hour.

- `bike_share_yr_1.csv`: Bike rental data for Year 1 (2022).
      Same structure as `bike_share_yr_0.csv`, but for Year 2022.

- `cost_table.csv`: Cost and COGS for each year.

     ### **Columns**:
  - `yr`: Year of data (0 or 1).
  - `price`: Average price of bike rentals.
  - `COGS`: Cost of Goods Sold for rentals.

## Methods
- **SQL Queries**: Combined and transformed data from multiple datasets to calculate revenue and profit.
- **Power BI**: Created an interactive dashboard showcasing key metrics and insights.

## Key Insights
- 64% increase in demand despite a 25% price hike.
- External factors may be driving increased demand.
- The majority of riders are registered users.

## Visualizations
![Dashboard Screenshot](visualizations/dashboard.png)