## d3 census 

## Background

This project plots the census data to identify correlation between two data variables, each measured state by state and taken from different data sources. 
The correlation with a scatter plot and embed the graphic into an .html file will veisualize the corrolation to identify meaningful observation. 

![ScatterPlot.png] (https://github.com/EmilySakata/blob/master/d3_census/ScatterPlot.png)

![bar.png](https://github.com/EmilySakata/d3_census/blob/master/ScatterPlot.png)



Following steps were taken to visualize the data.

1) Data gathering

Look for demographic information using the 2014 one-year estimates from the U.S. Census Bureau's American Community Survey. You can specify your information using the American FactFinder tool. When searching through the data, be sure to select these options in the left sidebar(http://factfinder.census.gov/faces/nav/jsf/pages/searchresults.xhtml):
Topics -> Dataset -> 2014 ACS 1-year estimates
Geographies -> Select a geographic type -> State - 040 -> All States within United States and Puerto Rico

Next, you'll search for data on health risks using 2014 survey data from the Behavioral Risk Factor Surveillance System. 
(https://chronicdata.cdc.gov/Behavioral-Risk-Factors/BRFSS-2014-Overall/5ra3-ixqq)

2) Data formatting

For the two data types chosen, grab the value columns from each and paste them into a new Excel document. Create header names that you can easily call with JavaScript (concise, lowercased, camelCased). Make sure that your rows and columns line up—You may need to delete Guam from your datasheet so that your Census and BRFSS data matches.

3) Visualization

Create a scatter plot that represents each state with circle elements. 
Scatter plot has:
  The x-values of the circles should match the demographic census data, while the y-values should represent the risk data.
  Include state abbreviations in the circles.

4) iframe-html

Embed it in index.html with an iframe to plot your d3 scatter plot. 

In order to execute the html, run the server localy by using the following command in your terminal
-m http.server <local host address>


## technology used

- d3
- csv
- html

