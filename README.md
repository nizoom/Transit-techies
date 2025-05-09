# Welcome to the Transit-techies heatmap workshop 🚲🗺️

#### Here's a breakdown of the notebook we'll be looking at:

In this notebook, we visualize Citibike trip data in NYC using a time-based heatmap. The dataset includes over 2 million trips taken in February. Each trip has a start and end location with timestamps. We aggregate trip counts by hour and round the latitude/longitude to generate a gridded heatmap for smoother spatial visualization.

To avoid cluttering the map with millions of individual lines or points, we bin trip start and end locations into groups and count how many trips occur in each group over time.

The result is an animated map that shows where trips start or end throughout the day across NYC.

There are more details and step-by-step processing inside the notebook.

#### Tools used in the notebook:

If you want to download this repo and go through the code yourself, here are the tools you'll need:

1. **Python**  
   &nbsp;&nbsp; The programming language used throughout the project  
   &nbsp;&nbsp; [Installation Page](https://www.python.org/downloads/)

2. **Jupyter Notebook**  
   &nbsp;&nbsp; The environment we used to write and run the code  
   &nbsp;&nbsp; [Installation Page](https://jupyter.org/install)

3. **Pandas**  
   &nbsp;&nbsp; For reading and aggregating the trip data  
   &nbsp;&nbsp; [Installation Page](https://pandas.pydata.org/docs/getting_started/install.html)

4. **Folium**  
   &nbsp;&nbsp; For generating interactive Leaflet-based maps in Python  
   &nbsp;&nbsp; [Installation Page](https://python-visualization.github.io/folium/)

5. **Folium.plugins.HeatMapWithTime**  
   &nbsp;&nbsp; For animating heatmaps over time on a map

6. \*\*Data Source: [Citibike Ridership Data](https://s3.amazonaws.com/tripdata/index.html)

---

Enjoy exploring the rhythms of NYC transportation!
