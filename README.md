# Mapping Earthquakes

## Project Overview of the Earthquake Tracker
#### The goal of this project was to create an interactive map using HTML, JavaScript, Leaflet and Mapbox that allows users to view recent earthquake data.

#### Resources
- Data Sources: 
Tectonic plate data `https://github.com/fraxen/tectonicplates/blob/master/GeoJSON/PB2002_boundaries.json`

Last 7-days of earthquake data from USGS.gov `https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson`

Last 7-days of earthquake data over 4.5 magnitude from USGS.gov `https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson`

- Software:  Microsoft Visual Studio Code
- Languages:  JavaScript, HTML
- Add-ons:  Mapbox, Leaflet

## Results of the Webpage
By following the steps listed below a user can enter the search criteria for UFO sightings.  

1.  The search parameters must be typed according to the examples in the placeholder fields of the `Filter Search` box.

![Slide_1.PNG](https://github.com/frostbrosracing/UFOs/blob/main/README.md_images/Slide1.PNG)

2.  Begin by typing in the date according to the example.  The date of `1/1/2010` was used in the example.  Because all the sightings in the `data.js` file are located in the United States, "us" was also entered as the default search country.

![Slide_2.PNG](https://github.com/frostbrosracing/UFOs/blob/main/README.md_images/Slide2.PNG)

3.  Next, type in the state according to the example.  California was used in the example by typing in `ca`.

![Slide_3.PNG](https://github.com/frostbrosracing/UFOs/blob/main/README.md_images/Slide3.PNG)

4.  Once you type in the city, you can see the results further filtered as shown below.  The city of `el cajon` was used in this example.

![Slide_4.PNG](https://github.com/frostbrosracing/UFOs/blob/main/README.md_images/Slide4.PNG)

5.  Finally, by typing in the shape `formation`, you can see that a single sighting is the result of all five filters.

![Slide_5.PNG](https://github.com/frostbrosracing/UFOs/blob/main/README.md_images/Slide5.PNG)

## Summary
By creating multiple filter options for the search, the data set can be quickly searched according to the user's desired parameters.  One drawback to the webpage is that the search criteria must be typed exactly as it is captured in the `data.js` file that is being filtered.  Because of this, results will not be included if the search isn't conducted according to the examples shown in the placeholder fields in the Filter Box. Two additional recommendations for further development that would enhance the user experience on the webpage are listed below:

1.  Expand the dataset to include a wider range of sightings from around the world and for a more comprehensive period of time.
2.  Create a user form which would allow submissions from webpage visitors to be included in the dataset.
