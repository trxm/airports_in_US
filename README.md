# Airports in the U.S.
### Completed 2/12/2021
### By Tram-Anh Nguyen

![map of all airports in the united states](/img/airport_map.png)

## Project Description
In this project, we were given data about airports in the United States and states in the United States. With these data, we are to create a map on all of the airports in the United States: how many airports are in each states and which airports have air traffic control towers. First, a white base map was added. Then we added markers of airports, which are then categorized into whether they have air traffic controls or now via colors. Next, we created a chloropleth map to show how dense states are in regards to airport counts. Finally, we added a legend to assist the readers understand the map.

## Functions
We created many functions that assists the stylize the map. We have functions that set and categorize data by using color palettes from color brewer. There are functions that added the legend for better map readability.

## Credit and Acknowledgements
Two geoJSON files were utilized as data sources: airports.geojson and us-states.geojson.

airports.geojson contains data about all the aiports in the United States. The data can be found on [Data.gov](https://catalog.data.gov/dataset/usgs-small-scale-dataset-airports-of-the-united-states-201207-shapefile). According to the website: Data.gov was launched in 2009 and is managed and hosted by the U.S. General Services Administration, Technology Transformation Service.

us-states.geojson provided states boundary that allowed us to create the chloropleth map. The data was created by [Mike Bostock](https://bost.ocks.org/mike/) of [D3](https://d3js.org/).
