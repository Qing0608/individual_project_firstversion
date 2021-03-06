# individual_project_reversedversion

## Data source
Chicago data portal: https://data.cityofchicago.org/Transportation/Speed-Camera-Violations/hhkd-xvj4

**Data description**
Chicago experiences roughly 3,000 crashes annually between motor vehicles and pedestrians, about 800 of which involve children.
So 162 camera was placed in children's safety zone to monitor speed violations.The data reflects violations that occurred from 
July 1, 2014 until present.The reported violations are those that have been collected by the camera and radar system and reviewed 
by two separate City contractors. This dataset contains all violations regardless of whether a citation was issued, which 
provides an accurate view into the Automated Speed Enforcement Program violations taking place in Children's Safety Zones. The 
whole dataset includes 9 columns and 184K rows, had address, camera ID, violation date, violations, X-coordinate, Y-coordinate,
latitude, longitude, location. 

## Visulization Charts
https://public.tableau.com/profile/qing.zhang#!/vizhome/ChicagoViolationinsight-reversedversion/Dashboard1?publish=yes

### Chart explanation
#### First finding:
   First, I calculated the total Violations in each day of the week from 2014-2019. It seems like there were more Violations during 
   weekdays than weekends. Then on the second chart, I calculated the average Violation each day of the week on the same year 
   period. The result is totally different. The average Violations is obviously higher in weekends than weekday. Same as the 
   third chart(conbine 2014-2019 in total). Which means, Violations in weekends is more concentrated in certain area, while it 
   is more spread in weekdays. Aware of the cameras were placed in Children's dangerous zone, it can be explained that during 
   weekend, there are less car driving around school area, so the Violations decreased. Use lines charts is because it makes the trends more clearly. As to the mayor, I may suggest to set 
   different speed limit between weekdays and weekends. Since there are not many students would go to school during weekends, 
   increase the speed limit is reasonable.
   
   **Compare to first version, I reorganized the lay out of 3 charts in dashboard1, so the difference between total violations and average 
   violations during weekend and weekdays is more clearly.**
   
#### Second finding:
   In the first chart, I sorted top 10 address that had most largest amount of Violations. The first one is quite 'impressive'.
   Then I chose top 3 to do the further analysis. As you can see in the second chart, it is pretty interesting that top 3 is 
   allocated in north, middle, and south of the city. Then I did further analysis, the chart 3 showed the total amount of 
   Violations on the trend of top 3 address throughout each year, same as the result of my first chart from last week, most of 
   the location had highest Violations on 2015, and lowest on 2019(it is because 2019 is not a whole year data, but still the 
   trend was decreasing after 2015). Also I did the predict, it is kind of interesting as well, the top 1 address which located
   in the north, seems will increase a little bit from 2019 to 2010, compare to the whole trend which is decreasing, this is 
   not a good sign. The second one which located in the south will have a almost equal amount of Violations 2019 and 2010. The 
   third one which located in the middle seems will have the best performance, the trend is decreasing. From these chart, I 
   would suggest the mayor to pay more attention to the north part, it will have more Violations pressure than other places, 
   maybe come out more methods, like not turn on red, etc to help with it.
   
#### Third finding:
   I downloaded the new data, there is a new column name 'community area', as my understanding, it might be the difference area
   zone with in the space that cameras can reach. I used it to do the analysis. In the first chart, the amount of Violations 
   was quite different betweet each community area, 30 is obviously the highest one, there are some peaks between 13-15, 49-57, 
   61-65. Then I made the 2nd chart, seemed each year followed the same trend. Since 2019 only had first quarter, I used Q1 to 
   do the third chart, again it followed the same pattern. Seems community area 30 had the highest amount of Violations in every
   year, it is a dangerous area, so as other peak points. So I would suggest the mayor to focus on those spots put more efforts 
   to explore the reason and hopefully come out solutions. It will siganificantly help to reduce the total Violations.
   
   **Compare to the first version, I sized the volumn of violations in different community, and 3 charts lay out one by one
   can easily see the same pattern in each community over years. Those heavy sized columns need to pay more attention to.**
