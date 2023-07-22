# Spatial-Data-Analysis-And-Visualization
This is a series of processing cases and analyses based on spatial data files. 
For the body of the notebook, see document: A consolidated multifactor analysis of the severity of accidents and transport casualties.ipynb

## I. Datasource
The data used in this project was sourced from [STAT19 R PACKAGE](https://CRAN.R-project.org/package=stats19)
The types of data being processed include ***vector data*** (such as SHP, Geopackage, etc.) and a large amount of tabular data (which includes time information and coordinates).

## II. Introduction
This project was initiated as part of the Spatial Data Science for Social Sciences that I elected as part of my Urban Planning and Design studies at the University of Sheffield. 

This project utilizes key Python libraries for data analysis and visualization. 
**Pandas** is used for data manipulation and analysis, ***matplotlib*** and ***seaborn*** for data visualization, ***numpy*** for mathematical operations, and the ***Google Maps API*** for handling geographical data and mapping functionalities.

The primary objective of this project is to explore the causes of traffic accidents and identify factors related to their severity. By analyzing the intricate relationship between various factors such as location, time, environmental conditions, and the nature of accidents, the study aims to provide valuable insights into accident causation and severity.

The findings from this multifactor analysis can serve as a valuable reference for future urban construction and planning. By understanding the variables that contribute to the severity of accidents, we can design and plan our cities in a way that minimizes potential risks and creates safer travel conditions for all citizens. Moreover, it could provide useful information for daily commuters, helping them understand the factors that contribute to accidents and thus make safer travel decisions.

In essence, this project embodies the intersection of Spatial Data Science and Urban Planning, using the tools of the former to inform decisions in the latter, for a safer, more efficient urban environment.

## III. Limitation
Some of conclusions are missing some nuance, for example, we don't know the relative traffic volumes at different times of the day (or year).

The joyplot visualisation approach may not be best used for this data; because it gives the impression of a oscillating variable, where in reality it is simply discrete data points at 1, 2 etc.
