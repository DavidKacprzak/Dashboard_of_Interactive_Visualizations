# Dashboard_of_Interactive_Visualizations
### Rental analysis and interactive dashboard using the Panel library, Plotly Express, and Mapbox

## Rental Analysis
1. Import necessary libraries
2. Retrieve API from dotenv
3. Import the census data CSV to a Pandas DataFrame
4. Calculate the average number of housing units per year
5. Plot the average number of housing units per year as a bar chart
6. Calculate the average gross rent and average sale price per square foot
7. Plot the average gross rent as a line chart
8. Plot the average sale price per year as a line chart
9. Reset the DataFrame
10. Group by year and neighborhood and calculate the mean sale price per year
11. Create hvplot of average sale price per square foot
12. Reset the DataFrame and group by neighborhood and use nlargest to retreive the 10 most expensive neighborhoods by average sale price per square foot
13. Plot the 10 most expensive neighborhoods as a bar chart
14. Create a parallel coordinates plot of the 10 most expensive neighborhoods
15. Create a parallel category plot of the 10 most expensive neighborhoods
16. Import the location data CSV to a Pandas DataFrame
17. Calculate the average values for each neighborhood 
18. Concatenate the average values for each neighborhood with location data
19. Set the mapbox token using Plotly Express
20. Plot a scatter of the neighborhood data mapbox and Plotly Express

## Dashboard
1. Import necessary libraries
2. Retrieve API from dotenv
3. Import the CSVs to Pandas DataFrames
4. Insert charts from rental_analysis.ipynb into functions that return the chart output (Note: this has been done in individual cells for each chart to show charts are working)
5. Combine charts to a single dashboard view using Panel library.
6. Create tabs for the dashboard and add the panel of charts to respective dashboard tabs
7. Append .servable() to the dashboard to turn the notebook into a deployable app

