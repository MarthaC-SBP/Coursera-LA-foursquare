# Coursera IBM Data Science Certificate Capstone Project


### Introduction/Business Problem
A company currently has an office in Downtown Los Angeles (Fashion District). Their lease is ending soon and they have decided to find a new office location for various reasons. They would like to stay in Downtown Los Angeles so as to not have to relocate or inconvenience any of their employees, but they are open to any district within Downtown Los Angeles. Their employees often comment about how much they love where their office is because of the venues they have close by for meals and entertainment. They want to make sure their employees continue to be happy with where the office is so they are encouraged to come in frome time to time. As such, they would like to understand which other districts in Downtown Los Angeles are most similar to the Fashion District. With this information, they will then look into available office space to explore their options. 

### Data 
Data component 1:
To create clusters of the districts in Downtown Los Angeles, a webscraping algorithm will be used to collect district names and zip codes from this site: http://www.laalmanac.com/communications/cm02_communities.php. This data will be added to a dataframe. 

Data component 2:
The districts and zip codes will then be used to locate the latitude and longitude of each district. This data will be added to the previous dataframe. 

Data component 3: 
The FourSquare API will be used to collect venue information for all districts in Downtown Los Angeles. The 'explore' endpoint will be used to pull a list of recommended venues within each district. This data will then be used to complete the clustering and identify other districts that are similar to the Fashion District. 
