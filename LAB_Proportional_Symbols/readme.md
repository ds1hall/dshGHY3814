
# Proportional Symbol Mapping with Leaflet
by Douglas S. Hall
## Objective

This lab demonstrates how to establish a marker with its size based on a particular value in a data file.
## The "MAP"
Data for this exercise is provided in an Excel .csv format. An on-line geoJSON converter is used to
produce the **data.geojson** file found in the project **assets** folder.  This data contains the *state name, Latitude and Longitude for the center of the state, and the estimated population* provided
by the US Census Bureau for 2019.

Heading **h1** style is redefined to provide a nice, clean Title for the map.  Circles are used as markers
JS code is included to vary the size of each CircleMarker based on extimated population.

After building the JS from snippets provided in the lab instructions, I determined that a Radius of 8
was too large.  The CircleMarkers covered too much area on the map at minimum zoom.
Changing the radius to 4 greatly improved the appearance.

Once the basic map is constructed and the CircleMarker color change worked, I worked on Popups for the CircleMarkers.  When a CircleMarker is selected by moving the cursor over the marker, clicking the CircleMarker will bring up a Popup with the *state name* and *estimated population*.  Moving the cursor off the marker will close the popup.
