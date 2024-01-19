# prophet-challenge
Challenge Module 08 Prophet

## About the challenge
In this challenge we used information from Google Search and MercadoLibre stock prices
- The idea was to identify a correlation between the Number of searches and the changes in stock prices by:
  1. Identifying unusual patterns in hourly Google search traffic, 
  2. Mining the search traffic data for seasonality, 
  3. Comparing patterns between Google search traffic and MercadoLibre stock price, 
  4. Creating a prediction with a Prophet model

## The tools
- The main tools used in this project where:
  1. Pandas
  2. numpy
  3. [Prophet](https://facebook.github.io/prophet/)
  4. Matplotlib

## About the data
- The Google Search data consists of 37,106 records with hourly search counts ( 2 columns datetime and count ) between June 01, 2016 and September 08,2020
- The MercadoLibre Stock data consists of 9336 records with hourly Stock Prices ( 2 columns datetime and Price ) between January 02, 2015 and July 31,2020
  
## Tasks
- Google Data
  - Slice/Isolate a month of the data
  - Plot it
  - Quantify and compare with the other months
  - Plot and Analyze Hourly Data
  - Plot and Analyze Daily Data
  - Plot and Analyze Weekly Data
- MercadoLibre Data
  - Slice/Isolate 6 months of the data
  - Plot it ( with sub plots )
  - Shift/offset data for a different comparison approach
  - Calculate the standard deviation of the closing stock price **return**
  - Visualize the last Calculation
  - Calculate the Hourly Stock Return
  - Construct a correlation table
  - Prepare the data for use with Prophet
  - **Execute the Prophet model process to calculate and plot predictions based on the data** 
