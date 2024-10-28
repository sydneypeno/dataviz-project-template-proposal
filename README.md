# Data Visualization Project - Massachusetts Car Crashes

## Viz Hub Links

Version 1: https://vizhub.com/sydneypeno/a45d6b7a43ba4b44aafbb23353237f71
Version 2: https://vizhub.com/sydneypeno/7ae09253c93341ae8cc9954694307b84

## Data

The data I propose to visualize for my project is from a Boston Crash Dataset. This Dataset is pulled from data.boston.gov, provided as part of the Vision Zero Boston program, contains records of the date, time, location, and type of crash for incidents requiring public safety response which may involve injuries or fatalities. All records are compiled by the Department of Innovation and Technology from the City's Computer-Aided Dispatch (911) system and verified as having required a response from a public safety agency. To protect the privacy of individuals involved in these incidents, we do not indicate the severity of specific crashes or whether medical care was provided in any specific case.

I want to understand the geographic distribution of crashes. I want to understand how crashes have changed of time (time of day, time of week, time of year, year-after-year, etc.) I want to identify subsets of the data where crashes have a high value. I want to identify crash rates for location types. I want to identify crash rates for mode/vehicle type.


## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 * How does the amount of crashes vary over geographic location?
 * Is there any patterns (correlation) between the number of crashes and the time of day? day of week? time of year? from year-to-year?
 * Do different locations have varying crash rates?
 * DO different vehicle types have higher crash rates?

## Sketches
<img width="639" alt="Screenshot 2024-10-07 at 10 11 06 AM" src="https://github.com/user-attachments/assets/4a15dca8-2e27-4870-933c-707197c25efa">
This sketch shows the distribution of crashes geographically, with an interactive time filter bar. The data points are different sizes to represent if more than 1 crash has happened in that same spot, and different colors to represent time of day, crash type etc. This will help answer questions about patterns. 


## Prototypes

I’ve created a proof of concept visualization of this data. It's a bar chart and it shows the number of crashes each month over the past 10 years, from 2015-2025. As you can see, there are similar patterns each year, as seen by the humps going up and down each year. 

<img width="815" alt="Screenshot 2024-10-07 at 10 23 44 AM" src="https://github.com/user-attachments/assets/521cd046-531e-450a-bde7-16e438447dac">

Link to viz hub for this visualization: https://vizhub.com/sydneypeno/383ddaf8ede643ada1a3e12effbc1afc?edit=files

I have also started creating the map that I plan to plot the crash data on, using geojson data for the state of massachusetts that I found on github. You can see the map outline loaded into the workspace in the screenshot below. 

<img width="1315" alt="Screenshot 2024-10-20 at 9 01 02 PM" src="https://github.com/user-attachments/assets/a54e705d-3294-4cc8-a11f-ddcefead219d">

## Open Questions

I really like map visualizations especially where boson is a city, and it will be interesting to see if there are certain areas that are congested with crashes compared to further outside the city. However for some of my questions, line graphs/bar graaphs etc. might be easier to identify these patterns. I will likely include multiple graphs as my final visualization project; the cloreoploth, bar chart, and a line graph, for example. 

## Milestones

10/24 - Add data to graphs
10/30 - Progress Report & Peer feedback 
11/06 - Improve Main prototype
11/13 - Add interactivity 
11/20 - Add interactivity to supplementary Vizs
12/04 - Make video on final Viz


(for each week, estimate what would be accomplised)
