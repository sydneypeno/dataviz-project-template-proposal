# Data Visualization Project - Massachusetts Car Crashes

## Viz Hub Links

### Main Visualizations: https://vizhub.com/sydneypeno/0351d1d160014b2da905f98c3a7e8edd


## Data

The data I used to visualize for my project is from a Boston Crash Dataset. This Dataset is pulled from data.boston.gov, provided as part of the Vision Zero Boston program, contains records of the date, time, location, and type of crash for incidents requiring public safety response which may involve injuries or fatalities. All records are compiled by the Department of Innovation and Technology from the City's Computer-Aided Dispatch (911) system and verified as having required a response from a public safety agency. To protect the privacy of individuals involved in these incidents, they do not indicate the severity of specific crashes or whether medical care was provided in any specific case.

For this project, I set out to understand the geographic distribution of crashes, the patterns of crashes by time of year, year-after-year. While I was learning new data viz techniques, I sought out to identify subsets of the data where crashes have a high value and crash rates for mode/vehicle type by parsing the data and adding interactivity.


## Questions & Tasks

The following tasks and questions drove the visualization and interaction decisions for this project:

 * How does the amount of crashes vary over geographic location?
 * Is there any patterns (correlation) between the number of crashes and the time of year? Does seasonality stay the same from year-to-year?
 * Do different geographic locations have varying crash rates?
 * Do different vehicle types have higher crash rates?

## Prototypes

I completed several iterations of each visualization as my knowledge and experience grew throughout the course. From learning new techniques like including color channels and interactivity, to ensuring scalability by learning how toimport and parse the data from the raw data file rather than hard coding data points in my java file directly, my visualizations evolved.

### The Evolution of the Geographic Crash Map
The first iteration of the map was merely an outline of massachusetts, as I was learning to use and understand geojson data. And iteration two was the map with test points on the map that would later represent the locations of crashes from the crash data. In iteration three, I successfully added in the real coordinate data points to plot crashes, parsing the data from the csv file.

Map Version 1: https://vizhub.com/sydneypeno/a45d6b7a43ba4b44aafbb23353237f71

Map Version 2: https://vizhub.com/sydneypeno/7ae09253c93341ae8cc9954694307b84

Map Version 3: https://vizhub.com/sydneypeno/5931cf27ea29474bb6e7f6a7980dc1ed


In the fourth iteration, I decided to use Boston geojson data as the crash data contained only Boston specific crashes. I was able to successfully plot the crash data points on the Boston map but could not import and parse the geojson data. Instead I had hardcoded the geojson data into my javascript file, making the UI really slow and ultimately not feasible. In iteration five, I added color channels by color coding the data points by crash type, but still had hardcoded geojson data.

Map Version 4: https://vizhub.com/sydneypeno/9fbaa22584fc4b5193ab9c3651a8b1d7

Map Version 5: https://vizhub.com/sydneypeno/81efeac5f6a84e9ab25932dbb4334916

In iteration six, I finally made the visualization scalable, by importing and parsing the geojson data in my javascript file, instead of having it hard coded. Viz hub now ran much quicker, and I cut down almost all of the lag time I was experiencing. In iteration 7, I added interactivity by including check boxes to filter what types of crashes the user wanted to see on the graph.

Map Version 6: https://vizhub.com/sydneypeno/28e15db445594a1eb679a83c2e6539e9

Map Version 7: https://vizhub.com/sydneypeno/21cdfe1783344b249af855efc302e835

In my eigth and final iteration, I improved the look of my visualization, including centering the map, and combining the legend and check boxes for a better user experience and improved aesthetic.

**Map Version 8: https://vizhub.com/sydneypeno/90ca12ab39044cd2b0d09f000b2093ae**

### The Evolution of the Boston Crashes Line Graph 

The first iteration of the line chart was actually a bar chart, originally showing the number of crashes each month over the past 10 years, from 2015-2025.

Graph Version 1: https://vizhub.com/sydneypeno/383ddaf8ede643ada1a3e12effbc1afc

I decided that a line chart would better represent the data as it contained time-series elements, which I was intending to illustrate. This was my second iteration.

Graph Version 2: https://vizhub.com/sydneypeno/63a64b63d6fc438aaafdcc307829fb33

The third iteration was one of my final visualizations, where I decided to add color channels in terms of seasons. I saw that the data contained some seasonality, with patterns in crash rates trending during the same time of year, each year.

**Graph Version 3: https://vizhub.com/sydneypeno/6e535fdd7bd44f0fa56ae8295d4169af**

In iteration four of the line graph, I implemented color channels and interactivity, by filtering the crashes by type of crash, with separate lines for each type,and check boxes to add or take away the lines for a given type of crash.

Graph Version 4: https://vizhub.com/sydneypeno/b5348e06fa15459eb5ec9fe27a3f1f08

By the fifth iteration, I changed the line to be one trend line, but kept the interactive element with the check boxes to filter by type.

Graph Version 5: https://vizhub.com/sydneypeno/562b8a8817a942d8a8dfe75bc0d64e3b

And in the 6th and final iteration, I made minor changes to improve the look of the check boxes by adding the full type labels (Mv--> motor vehicle). 

**Graph 6: https://vizhub.com/sydneypeno/dd6518d99fce4c3693cb45939f6c0609**

### The Final Product
In the final project file, I explain the data and embed each of the visualizations to create a comprehensive crash analysis page that outlines my progress over the course of this project. 

<img width="501" alt="Screenshot 2024-11-21 at 7 32 40 PM" src="https://github.com/user-attachments/assets/779765a0-332e-4c3a-9270-4779b2e74763">

<img width="810" alt="Screenshot 2024-11-21 at 7 34 27 PM" src="https://github.com/user-attachments/assets/bf9d6919-9b30-4354-a8ff-bf2cdc0af2a3">
<img width="812" alt="Screenshot 2024-11-21 at 7 34 38 PM" src="https://github.com/user-attachments/assets/9867311e-33ce-4a4d-beae-03ddbae7a08e">
<img width="812" alt="Screenshot 2024-11-21 at 7 39 32 PM" src="https://github.com/user-attachments/assets/d6905ce6-c7ff-418e-9538-3852a9349330">


## Milestones

12/02 - Make PPT presentation slides for final video

12/04 - Make video on final Viz


## Ideas for Future Work 
- With more time and practice, I would like to add interactivity with time. For example, on the map visualization, have a date slider bar, and have the points on the map auto-populate based on the selected time frame. 

