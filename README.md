# Coursera IBM Data Science Certificate Capstone Project


### 1. Introduction
Downtown Los Angeles (DTLA) is a diverse neighborhood in Los Angeles, broken out into 11 districts. A company currently has an office in DTLA within the Arts District. Their lease is ending soon and they have decided to find a new office location for various reasons. They would like to stay in DTLA so as to not have to relocate or inconvenience any of their employees, but they are open to any district within DTLA. Their employees often comment about how much they love where their office is located because of the venues they have close by for meals and entertainment. They want to make sure their employees continue to be happy with the office location so they are encouraged to come in frome time to time. As such, they would like to understand which other districts in DTLA are most similar to the Arts District. With this information, they will then look into available office space to explore their options. 

### 2. Data 
Geographical location data for each district, as well as data about the venues in each district, will be used to create clusters of the districts in Downtown Los Angeles (DTLA).

*Downtown Los Angeles Districts and geographical location data:*

A csv file containing DTLA district names and geographical coordinates will be used to create a Pandas dataframe including the following data points:

district: Name of district
latitude: District latitude
longitude: District longitude

*Venue data:*

The district geographical location data will be used to get local venue information, using the FourSquare API. The 'explore' endpoint will be used to pull a list of recommended venues within each district. The following data will be captured into a dataframe, along with the district data:

venue: Venue name
venue_category: Venue category
venue_lat: Venue latitude
venue_lng: Venue longitude
