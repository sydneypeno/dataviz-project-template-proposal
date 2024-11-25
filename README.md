# Data Visualization Project - Massachusetts Car Crashes

## Viz Hub Links

### Main Visualizations: https://vizhub.com/sydneypeno/0351d1d160014b2da905f98c3a7e8edd

Map Version 1: https://vizhub.com/sydneypeno/a45d6b7a43ba4b44aafbb23353237f71

Map Version 2: https://vizhub.com/sydneypeno/7ae09253c93341ae8cc9954694307b84

Map Version 3: https://vizhub.com/sydneypeno/5931cf27ea29474bb6e7f6a7980dc1ed

Map Version 4: https://vizhub.com/sydneypeno/9fbaa22584fc4b5193ab9c3651a8b1d7

Map Version 5: https://vizhub.com/sydneypeno/81efeac5f6a84e9ab25932dbb4334916

Map Version 6: https://vizhub.com/sydneypeno/28e15db445594a1eb679a83c2e6539e9

Map Version 7: https://vizhub.com/sydneypeno/21cdfe1783344b249af855efc302e835

**Map Version 8: https://vizhub.com/sydneypeno/90ca12ab39044cd2b0d09f000b2093ae**

Graph Version 1: https://vizhub.com/sydneypeno/383ddaf8ede643ada1a3e12effbc1afc

Graph Version 2: https://vizhub.com/sydneypeno/63a64b63d6fc438aaafdcc307829fb33

**Graph Version 3: https://vizhub.com/sydneypeno/6e535fdd7bd44f0fa56ae8295d4169af**

Graph Version 4: https://vizhub.com/sydneypeno/b5348e06fa15459eb5ec9fe27a3f1f08

**Graph Version 5: https://vizhub.com/sydneypeno/562b8a8817a942d8a8dfe75bc0d64e3b**

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

You can observe each iteration of my visualization by checking out the links to each version above. From the a proof of concept visualization of this data, to the fourth iterations, you can see how my project has evolved. The map visualization started out as a basic map of massachusetts and sample dataa points, and has since evolved to a map of boston and every crash that has been reported in the past 8 years. It is also now color coded by the type of crash (motor vehicle, pedistrian, or bike). I have since, made the project scalable by importing the data from a separate file rather than hardcoding the boston map geo json data into my index file. I have also added an interactive element by including check boxes to see the different types of crashes. Users can select any combination of the 3, all, or none of the types and the map will automatically update with the crashes for that type. And in the final, 8th iteration, I improved the legend and check boxes by combining them, added a title and changed the scaling so the map fit in the embed size. 

The graph visualization started as a bar chart showing the number of crashes each month over the past 10 years, from 2015-2025. Since then I have changed the graph to a line graph to better represent the continuous nature of the data. As you can see, there are similar patterns each year, as seen by the humps going up and down each year. In version 3, I implemented color coding to represent the season of the crash, so that we can observe seasonal patterns within the crashes. In version 4, I implemented check boxes to filter the type of crash.

In the final project file, I explain the data and embed each of the visualizations to create a comprehensive crash analysis page. 

<img width="501" alt="Screenshot 2024-11-21 at 7 32 40 PM" src="https://github.com/user-attachments/assets/779765a0-332e-4c3a-9270-4779b2e74763">

<img width="810" alt="Screenshot 2024-11-21 at 7 34 27 PM" src="https://github.com/user-attachments/assets/bf9d6919-9b30-4354-a8ff-bf2cdc0af2a3">
<img width="812" alt="Screenshot 2024-11-21 at 7 34 38 PM" src="https://github.com/user-attachments/assets/9867311e-33ce-4a4d-beae-03ddbae7a08e">
<img width="812" alt="Screenshot 2024-11-21 at 7 39 32 PM" src="https://github.com/user-attachments/assets/d6905ce6-c7ff-418e-9538-3852a9349330">



## Milestones

11/25 - Finishing touches anad improvements 

11/27 - Record first draft of presentation 

12/02 - Make PPT presentation slides for final video

12/04 - Make video on final Viz


## Ideas for Future Work 
- With more time and practice, I would like to add interactivity with time. For example, on the map visualization, have a date slider bar, and have the points on the map auto-populate based on the selected time frame. 

