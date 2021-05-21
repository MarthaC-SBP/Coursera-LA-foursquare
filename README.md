# Coursera IBM Data Science Certificate Capstone Project


### 1. Introduction
Downtown Los Angeles is a diverse neighborhood in Los Angeles, broken out into 11 districts. 

### 2. Business Problem
A company currently has an office in Downtown Los Angeles (Fashion District). Their lease is ending soon and they have decided to find a new office location for various reasons. They would like to stay in Downtown Los Angeles so as to not have to relocate or inconvenience any of their employees, but they are open to any district within Downtown Los Angeles. Their employees often comment about how much they love where their office is because of the venues they have close by for meals and entertainment. They want to make sure their employees continue to be happy with where the office is so they are encouraged to come in frome time to time. As such, they would like to understand which other districts in Downtown Los Angeles are most similar to the Fashion District. With this information, they will then look into available office space to explore their options. 

### 3. Data 
To create clusters of the districts in Downtown Los Angeles, I will use geographical location data for each district, as well as data about the venues in each district. 

#### Downtown Los Angeles Districts and zip codes:
To create clusters of the districts in Downtown Los Angeles, I will webscrape this site: http://www.laalmanac.com/communications/cm02_communities.php. The following data will be captured into a dataframe:

* district: Name of district
* zip_code: Zip code of district

#### Geographical location data:
Using the zip codes for each district, I will collect the geographical location data for each district, adding the following columns to the dataframe: 
* latitude: District latitude
* longitude: District longitude

#### Venue data:
Finally, I will use the district geographical location data to get local venue information, using the FourSquare API. The 'explore' endpoint will be used to pull a list of recommended venues within each district. I will capture the following data into a dataframe, along with the district data: 

* venue: Venue name
* venue_category: Venue category
* venue_lat: Venue latitude
* venue_lng: Venue longitude

These data components will then be used to complete the clustering and identify other districts that are similar to the Fashion District. 
