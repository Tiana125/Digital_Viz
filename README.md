This branch contains the necessary info to build the 'rail.html' in the final output website. 

- folder named "FOI 1760 2021" is the data source, available [here](https://www.whatdotheyknow.com/request/station_usage_figures#incoming-1697263). 
- folder named 'initial ideas(abandoned)' was the initial idea of plotting the rail network of GB, but we finalised the idea to be just in London, considering this is a city transformation project.
- "tfl_stations/json" is a file containing the locations of stations and lines, available [here](https://github.com/oobrien/vis/blob/master/tube/data/tfl_stations.json). 
- "ld1.ipynb" is the data preprocessing file and it generated "footfall.json", which were then uploaded on Mapbox Studio. This python notebook mainly used pandas, and one useful link is [here](https://stackoverflow.com/a/63366556). 
- "rail.html" is the code behind the rail visualisation, partially based on workshop 2 example 9 of CASA 0003 Group Mini Project, by D Smith. Some useful links used in this website are: [Swipe between maps, Mapbox GL JS](https://docs.mapbox.com/mapbox-gl-js/example/mapbox-gl-compare/) and [Make a choropleth map, Mapbox GL JS part 2: add interactivity](https://docs.mapbox.com/help/tutorials/choropleth-studio-gl-pt-2/). They are also cited in the report. 
