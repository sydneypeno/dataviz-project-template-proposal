# Data Visualization Project - Massachusetts Car Crashes

## Viz Hub Links

Map Version 1: https://vizhub.com/sydneypeno/a45d6b7a43ba4b44aafbb23353237f71

Map Version 2: https://vizhub.com/sydneypeno/7ae09253c93341ae8cc9954694307b84

Map Version 3: https://vizhub.com/sydneypeno/5931cf27ea29474bb6e7f6a7980dc1ed

Map Version 4: https://vizhub.com/sydneypeno/9fbaa22584fc4b5193ab9c3651a8b1d7

Map Version 5: https://vizhub.com/sydneypeno/81efeac5f6a84e9ab25932dbb4334916

Map Version 6: https://vizhub.com/sydneypeno/28e15db445594a1eb679a83c2e6539e9

**Map Version 7: https://vizhub.com/sydneypeno/21cdfe1783344b249af855efc302e835**

Graph Version 1: https://vizhub.com/sydneypeno/383ddaf8ede643ada1a3e12effbc1afc

Graph Version 2: https://vizhub.com/sydneypeno/63a64b63d6fc438aaafdcc307829fb33

**Graph Version 3: https://vizhub.com/sydneypeno/6e535fdd7bd44f0fa56ae8295d4169af**
**Graph Version 4: https://vizhub.com/sydneypeno/b5348e06fa15459eb5ec9fe27a3f1f08**

## Data

The data I propose to visualize for my project is from a Boston Crash Dataset. This Dataset is pulled from data.boston.gov, provided as part of the Vision Zero Boston program, contains records of the date, time, location, and type of crash for incidents requiring public safety response which may involve injuries or fatalities. All records are compiled by the Department of Innovation and Technology from the City's Computer-Aided Dispatch (911) system and verified as having required a response from a public safety agency. To protect the privacy of individuals involved in these incidents, we do not indicate the severity of specific crashes or whether medical care was provided in any specific case.

I want to understand the geographic distribution of crashes. I want to understand how crashes have changed of time (time of day, time of week, time of year, year-after-year, etc.) I want to identify subsets of the data where crashes have a high value. I want to identify crash rates for location types. I want to identify crash rates for mode/vehicle type.


## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 * How does the amount of crashes vary over geographic location?
 * Is there any patterns (correlation) between the number of crashes and the time of day? day of week? time of year? from year-to-year?
 * Do different locations have varying crash rates?
 * DO different vehicle types have higher crash rates?

## Prototypes

You can observe each iteration of my visualization by checking out the links to each version above. From the a proof of concept visualization of this data, to the fourth iterations, you can see how my project has evolved. The map visualization started out as a basic map of massachusetts and sample dataa points, and has since evolved to a map of boston and every crash that has been reported in the past 8 years. It is also now color coded by the type of crash (motor vehicle, pedistrian, or bike). I have since, made the project scalable by importing the data from a separate file rather than hardcoding the boston map geo json data into my index file. I have also added an interactive element by including check boxes to see the different types of crashes. Users can select any combination of the 3, all, or none of the types and the map will automatically update with the crashes for that type. 

The graph visualization started as a bar chart showing the number of crashes each month over the past 10 years, from 2015-2025. Since then I have changed the graph to a line graph to better represent the continuous nature of the data. As you can see, there are similar patterns each year, as seen by the humps going up and down each year. In version 3, I implemented color coding to represent the season of the crash, so that we can observe seasonal patterns within the crashes. In version 4, I implemented check boxes to filter the type of crash.

<img width="553" alt="Screenshot 2024-11-14 at 3 12 51 PM" src="https://github.com/user-attachments/assets/c41f2be9-39d1-4b08-b77c-bb65384ec8b4">
<img width="556" alt="Screenshot 2024-11-14 at 3 11 59 PM" src="https://github.com/user-attachments/assets/d01ee256-756c-4289-aefd-12ecbca9e99f">
<img width="549" alt="Screenshot 2024-11-14 at 3 11 45 PM" src="https://github.com/user-attachments/assets/af316804-7175-48f6-92d5-d891e2b87c15">


<img width="714" alt="Screenshot 2024-11-17 at 5 41 39 PM" src="https://github.com/user-attachments/assets/e24d43df-3281-407b-8e9e-1eb2d8e4fdb2">



## Open Questions

I really like map visualizations especially where boson is a city, and it will be interesting to see if there are certain areas that are congested with crashes compared to further outside the city. However for some of my questions, line graphs/bar graaphs etc. might be easier to identify these patterns. I will likely include multiple graphs as my final visualization project; the cloreoploth, bar chart, and a line graph, for example. 

## Milestones

11/06 - Improve Main prototype
11/13 - Add interactivity 
11/20 - Add interactivity to supplementary Vizs
12/04 - Make video on final Viz


(for each week, estimate what would be accomplised)
