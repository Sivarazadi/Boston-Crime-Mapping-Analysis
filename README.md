# Boston-Crime-Mapping-Analysis

This project is a technical analysis of crime data in Boston, Massachusetts using various data science techniques.

I went about building this notebook to gain more experience with the analysis of geospatial data, developing interactive maps, and due to a general interest in crime statistics. The datasets used for this project were from the [Crime Incident Reports in Boston](https://www.kaggle.com/datasets/jinbonnie/crime-incident-reports-in-boston) and [Boston Police Districts](https://www.kaggle.com/datasets/christotk/boston-police-districts) datasets on Kaggle.

The project begins by reading in the crime data from a CSV file using pandas and cleaning the data by dropping rows with missing latitude and longitude values. The project then uses folium to create an interactive heat map of the crime data on a map of Boston.

Next, the project reads in police district shape data using geopandas and plots this data on a map. The project performs an analysis of crime occurrences in each district by mapping the number of crimes in each district and creating a choropleth map using folium.

The project also includes some additional analysis of the crime data, including examining the data types of each column and exploring trends in the data over time using matplotlib and seaborn.

The following shows a gif of the interactive map of Boston crime geospatial data:

![interactive map gif](https://github.com/Sivarazadi/Boston-Crime-Mapping-Analysis/blob/main/images/m_1_gif.gif)

Overall, this project provides a technical analysis of crime data in Boston, utilizing data science techniques to gain experience with geospatial data analysis and interactive map creation.
