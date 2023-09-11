## Tableau_Dashboard_Project

> [**Link to dashboard**](https://public.tableau.com/app/profile/siddharth.mohanty7677/viz/LondonBikesDashboard_16940264234300/Dashboard1)

#### 💡 Play with the moving average duration and moving average period values to see how the graph and heatmap change
![dashboard_tools_image](./Dashboard_tools_image.jpg)

> 👀**You can download the london_merged.csv and london_bikes.ipynb to follow the steps mentioned below**

## Question you can answer using the dashboard

### Steps to ceate the dashboard
---
#### Downloaded the dataset on london bike sharing (london_merged.csv) from kaggle
#### Created a python notebook for data cleaning and transformation
#### Saved the final dataframe to a excel file (london_bikes) for visualization

### Created a total of 5 visualizations 
---
#### First visualization is the moving average graph that plots number of bike rides against time. It also contaims 3 floating filters to select duration, period(day,week,month) and the range for which you want to plot the graph
#### Second tile contains the number of total bike rides between a period, it changes based on the portion of the graph you select.
#### Then we have a heatmap that of temperature vs windspeed, it shows in which temperature and wind speed have the highest number of bike rides
#### There are two tooltip visualizations as well (Hover over heatmap or graph to view visuals)
##### First tooltip visualization contains a bargraph that shows distribution of number of bike rides in different weather conditions, this can be used to find which type of weather is prefered by people for taking a bike ride
##### The second tooltip contains the bar graph to show the distribution of ride durations, I created a calculated field to find duration from start and end time of rides, this can be used to find the most common duration of rides on busy or any specific day
