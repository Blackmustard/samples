**Fresh Veggies** v1.0.0 - 2016-09-16  

This is a Web App to help people find fresh and cheap vegetables in Chicago.  

The App uses Google Map API combined with open datasets to display freshness and price of a kind of vegetable in all food stores.
Besides, the app also shows the hictorical price of this veggie, price comperison between stores and whether it is a food in season.

**Description**  
* Datasets  
	* Climate Data Online (https://gis.ncdc.noaa.gov/geoportal/catalog/search/resource/details.page?id=gov.noaa.ncdc:C00861)  
	  Normals Daily Data for Chicago within 4 years
	  Columns may be used: Precipitation, Winds, Daily total sunshine, Maximum temperature, Minimum temperature, Snowfall  
	* Nearby Cook County Grocery Store Chains (https://catalog.data.gov/dataset/nearby-cook-county-grocery-store-chains-cc102)  
	  A list of grocery stores which are part of a multi-store chain and are located at or within 1 mile of Chicago's city limits
	  Columns may be used: name, location, kinds of vegetable offered  
	* Nearby Independent Cook County Grocery Stores (https://catalog.data.gov/dataset/nearby-independent-cook-county-grocery-stores-180c9)  
	  A list of independently owned- and operated grocery stores which are located at or within 1 mile of Chicago's city limits
	  Columns may be used: name, location, kinds of vegetable offered  
Datasets used are from noaa.gov and data.gov  
	
* How this app looks like
	* The screen will be devided into 2 side: one side for map; one side for historical data and price comparison.
	* user should choose one vegetable first to see the map
	* On the map, there will be small circle on the spot of stores, the color of the circle stands for the freshness. 
	* On the other side of the app, a bar chart will show the historical price of this vegetable and a table to compare local stores' price and distance

**Content**  
* README.txt  --This file.  
* index.html  --Web page for the App  
* style.css  --CSS style file with template from Bootstrap  
* js  --A directory contains all the javescript files  
* image  --A directory contains all images used in the website  
  
**Build up information**  
At this point the project only uses HTML/CSS/Javascript. However, other dependencies might be used in the future. An updated readme file will then be submitted along with later submissions.

**Test**  
The complete version of this App is exptected to be tested on the following broswers: Chrome, Firefox and Safari
