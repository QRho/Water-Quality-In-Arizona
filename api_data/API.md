# Group 2 Water quality project API

The water sample results we discovered were collected at various sources such as reservoirs, dams, canals, water treatment plants and 
pumping stations but did not include coordinates for their location in the data set. Using the google maps API we did a lookup for each of the locations 
that could be discovered and returned the latitude and longitude of each collection site. With the location information and the data from each
sampling point we were able to generate a heat map with the gmaps API to show the relative arsenic levels mapped to each site to show where arsenic
values were the highest. The places we found to have the highest levels of arsenic were near downtown Phoenix and in Bartlett lake where they were
above the CDC recommended threshold for safe drinking water. 
