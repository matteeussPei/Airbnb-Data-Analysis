## Airbnb

The [Airbnb](https://www.airbnb.com.br/) is already considered to be the biggest hotel company today. Oh, and it doesn't own any hotels!

Connecting people who want to travel (and stay) with hosts who want to rent out their properties in a practical way, Airbnb provides an innovative platform to make this accommodation alternative.

By the end of 2018, the startup founded 10 years ago had already hosted more than 300 million people around the world, challenging traditional hotel chains.

It's possible to acquire and analyze data from Airbnb, made available by them at Inside Airbnb. It's a great source of data to be used in Data Science projects.

<center><img alt="Analisando Airbnb" width="15%" src="https://www.area360.com.au/wp-content/uploads/2017/09/airbnb-logo.jpg"></center>

## Objective

In this notebook, we'll analyze the data on [London](http://data.insideairbnb.com/united-kingdom/england/london/2023-12-10/visualisations/listings.csv), collected September 6, 2023, and see what insights we can get from it.

## Data Analysis Conclusions

* City of London is not the most expensive neighborhood.
* Kensington and Chelsea is the most expensive neighborhood.
* The further you go into the city center, the more expensive it gets.
* The average minimum number of nights that you need to stay to get the London City listing is 2.6 nights.
* Entire house/apartment in London City, this is still the most common listing for the city.
* The average price for an Airbnb in London City is US$ 117.28 per night.
* An entire house/apartment in the City of London increases in price, while private rooms decrease in price.
* An entire house/apartment in the City of London increases in minimum nights, while private rooms decrease in minimum_nights.

### Language

``Python``

### Libraries

``pandas`` - data analysis and manipulation tool

``matplotlib`` - library for creating static, animated, and interactive visualizations

``seaborn`` - data visualization library based on matplotlib

``warnings`` - used to remove all the warnings

``pywaffle`` - package for plotting waffle charts

``folium`` - plot map with latitude and longitude marks
