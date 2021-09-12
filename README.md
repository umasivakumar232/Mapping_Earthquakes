# Mapping_Earthquakes

In this module, we used **Leaflet.js** which is a leading open-source JavaScript library for mobile-friendly interactive maps and a **Mapbox web services API** that allowed us to programmatically access Mapbox tools and services to populate a geographical map with **GeoJSON earthquake data from a URL**. 

* Each earthquake was represented as a circle on the map, the color and the size of the circle were adjusted to reflect the magnitude of the earthquakes - darker colored and larger circles indicated a higher magnitude earthquake, lighter and smaller circles indicated lower magnitude earthquakes.

* We used the **onEachFeature function** to add a popup for each of the earthquakes. When a circle is clicked it displays the magnitude and location of the earthquake 

* A **legend** was added to te map for easy understanding on the what the colors indicated

* The users were given a choice to select to view the earthquake data on **3 different map styles** based on available templates from Mapbox

* We added various layers to our maps as **overlays** 
* The first layer was for **all earthquakes** in the last 7 days
* The next was of the earthquake data in relation to the **tectonic plates** location on the earth,  
* A final layer for **major earthquakes** with the magnitude of over 4.5 was added   


<img width="644" alt="Earthquakes" src="https://user-images.githubusercontent.com/85518330/132977335-def60734-2e16-4d80-a422-1cbf0a96e295.png">


