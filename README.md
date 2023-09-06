# Overview

Congratulations on your new job! As the new lead analyst for the New York Citi BikeLinks to an external site. program, you are now responsible for overseeing the largest bike-sharing program in the United States. In your new role, you will be expected to generate regular reports for city officials looking to publicize and improve the city program.

Since 2013, the Citi Bike program has implemented a robust infrastructure for collecting data on the program's utilization. Each month, bike data is collected, organized, and made public on the Citi Bike DataLinks to an external site. webpage.

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have questions about the program, so your first task on the job is to build a set of data reports to provide the answers.

A link to my Citibike Tableau is here:



![](https://github.com/TraceyGeneau/citibike/blob/main/images/1200px-Citi_Bike_logo.jpg)

# Citibike

As a result of a busy year, the Citibike program for New York City requested an analysis of data from its bike stations in various areas. I was tasked with focusing on the New Jersey and Hoboken stations from March to July 2023. Unfortunately, data for August 2023 was not available at the time of the analysis. However, we can update the visualizations once that data becomes available. For now, our analysis will remain focused on the period from March 2023 to July 2023.  It is also important to note that all riders were counted by ride ID and therefore all originated from New Jersey & Hoboken regardless of their destination.
The main areas of focus were:</br>
1)	A visual of the stations used by riders to start and end their journeys.
2)	A breakdown of the use of the stations by riders.
3)	The distance and duration of each of the rides based on riders and mode of transportation.
4)	The changes observed monthly.</br>

Since the focus of the starting stations were those in New Jersey and Hoboken, the bulk of the starting station markers are found obviously in those areas.  The interesting thing to note is that there are many end locations that occurred in New York city.  Meaning riders are going the distance on their bikes!  All the starting and ending stations can be found on the interactive Stations Dashboard.</br>

![](https://github.com/TraceyGeneau/citibike/blob/main/images/Stations.png)

The three main start stations included in descending order:</br>
1)	The Grove Street Path (21 639 riders)
2)	Hoboken Terminal – River St & Hudson Place (19 045)
3)	South Waterfront Walkway – Sinatra Dr & 1st St (15 954)</br>

Coincidentally, the same three stations were the most popular destinations of the riders from New Jersey and Hoboken.</br>   

1)	The Grove Street Path (21 185 riders)
2)	Hoboken Terminal – River St & Hudson Place (18 758)
3)	South Waterfront Walkway – Sinatra Dr & 1st St (15 945)</br>

The detailed Top 10 Bubble Charts for starting stations and ending stations can be found on the Destinations Dashboard.  A complete listing of the start stations and ridership per station can also be found there.  Since our focus is on the New Jersey and Hoboken stations, the end station results were not listed individually as they contain New York City as well.  All riders are also covered under the start station as they are classified by their ride ID number.

A chart representing the Top 20 Starting and Ending points is also presented on the dashboard to indicate which paths were frequented most often.  For example, riders that embarked at Hoboken Terminal – Hudson Street and Hudson place and ended their journey at Hoboken Ave and Monmouth Street were the highest frequented path with 2356 Riders. 

![](https://github.com/TraceyGeneau/citibike/blob/main/images/Destinations.png)

On average, members, and non-members, regardless of bike type seemed to prefer to remain under 2km for a trip distance.  Where the average duration for members was on average half that of casual (non member) riders.  
Interestingly the Maximum distance that members rode was 14-16km depending on the bike style (classic or electric), whereas casual members rode between 18-20km depending on the bike style.  The max duration for both casual and member riders was approximately 1500 minutes or 25 hours. 

When comparing the time and distance the riders took, there was no strong correlation observed on classic bikes or electric bikes.  However, there was a slight increase in duration for both as the distance increased.  This observation appeared to be more so for the classic bike than electric bike. 

As a fun visual, the paths taken by riders that were over 5KM has been included on the Distance & Duration dashboard.

![](https://github.com/TraceyGeneau/citibike/blob/main/images/Distance%20%26%20Duration.png)

On a monthly basis, steady increase in riders occurred month from March to July 2023.  Overall, there were more member rides logged than casual members for both Electric and Classic bikes.  Classic bikes were used more often.  Although the steady increase in riders monthly was observed with the causal riders, there was a slight decrease in member riders from May to June 2023.  The use of classic bikes increased monthly with the overall rider trend, but the use of electric bikes decreased monthly after April.  

For the riders by day of the week the following was observed:

![](https://github.com/TraceyGeneau/citibike/blob/main/images/high%20low%20table.png)

Based on the data, Thursday tends to be one of the most popular days whereas Saturday and Monday tend to be the days with less riders.

![](https://github.com/TraceyGeneau/citibike/blob/main/images/Monthly%20Riding.png)

In conclusion, there are many riders taking part in the CitiBikes in New Jersey and Hoboken.  Of these riders, most stay in the area but some travel as far as New York City.  Although they are taking many different paths there are still some favorites taken by many riders.  Classic bikes tend to be used more often than electric bikes.  The use of classic bikes increase as the summer goes on whereas the use of electric bikes decreases.  The casual members tend to keep the bikes longer than the members do but the average distance traveled by both casual and members is approximately the same.  There was a steady increase in bike use from March to July overall.  Classic bikes were use more than electric bikes as the summer progressed as there was a decrease in the use of electric bikes.  As for days of the week, the most dominant use seems to occur on Thursdays, with the exception of the odd Wednesday or Tuesday and the days that riders liked the least were Monday and Saturday.  
