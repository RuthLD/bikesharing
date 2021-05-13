# bikesharing
🚲Use data from the Citi Bike program in New York City to create visualizations in Tableau for an investor presentation. 
## Data Citation: 
📁File 201908-citibike-tripdata.csv was downloaded from the [Citi Bike System Data](https://www.citibikenyc.com/system-data) site.
## Overview of the analysis: 
The purpose of analyzing the Citi Bike data from August, 2019 was to provide an investor presentation on why a bike-sharing program in Des Moines is a solid business proposal. The data from New York City in a peak summer month is used as a model to show who would use the bike-sharing program and when the most active ridership would be.
## Results:
🔗Link to [Tableau Story](https://public.tableau.com/views/NYCCitiBikeChallenge_16208606980650/NYCCitiBikeChallenge?:language=en&:display_count=y&:origin=viz_share_link)
* The first variable evaluated was where the highest concentration of bike rentals start.
  * ![NYC CitiBike Challenge_1](https://github.com/RuthLD/bikesharing/blob/main/Resources/NYC%20CitiBike%20Challenge_1.png)
  * NYC CitiBike Challenge_1 shows the starting location of the bikes in blue. The larger the circle size and the darker the color, the higher the number of bike shares that   began in that area. The darker and larger circles are located in areas where tourism is known to be high.
  * ![NYC CitiBike Challenge_2](https://github.com/RuthLD/bikesharing/blob/main/Resources/NYC%20CitiBike%20Challenge_2.png)
  * NYC CitiBike Challenge_2 shows the duration of the bike trip in minutes. The majority of trips are under 20 minutes, and the most significant volume of trips was just 5 minutes long.
  * ![NYC CitiBike Challenge_3](https://github.com/RuthLD/bikesharing/blob/main/Resources/NYC%20CitiBike%20Challenge_3.png)
  * NYC CitiBike Challenge_3 shows the ending location of bike trips. The circles again represent the number of bikes that ended in that location by larger size and darker red color. NYC CitiBike Challenge_3 and NYC CitiBike Challenge_1 are very similar. Combined with the trip duration information from NYC CitiBike Challenge_2, it is safe to say that the users are starting and ending their trips in roughly the same area. They are most likely taking a tour to see the area rather than using the bikes for long-distance trips. 
* The second variable is when the most active ridership would take place. 
  * ![NYC CitiBike Challenge_4](https://github.com/RuthLD/bikesharing/blob/main/Resources/NYC%20CitiBike%20Challenge_4.png)
  * NYC CitiBike Challenge_4 shows the days of the week and a breakdown of the hours in the day. The image is a heat map in gold to red color scheme. The least amount of bike shares are gold; the hours with the most bike shares are red. On Sunday and Saturday, the weekend days have fairly consistent use from 9 am to around 5-6 pm of the bikes with over 10,000 rides for those hours. The weekdays, Monday, Tuesday, Thursday, and Friday, have over 30,000 rides for each hour between 4 pm and 8 pm. This level of ridership represents the end of the workday and peoples spending their free time outside in summer weather. Wednesdays are the exception with lower ridership between 4 pm and 8 pm, with under 20,000 bike shares. The weekday mornings between 7 am, and 9 am have high rider numbers as people start their day with a bike ride. 
* The other important factor for a bike-sharing program is who is using the bikes.
  * ![NYC CitiBike Challenge_5](https://github.com/RuthLD/bikesharing/blob/main/Resources/NYC%20CitiBike%20Challenge_5.png)
  * ![NYC CitiBike Challenge_6](https://github.com/RuthLD/bikesharing/blob/main/Resources/NYC%20CitiBike%20Challenge_6.png)
  * NYC CitiBike Challenge_5 shows the ride duration of users by gender, and NYC CitiBike Challenge_6 shows the ride count per hour by gender. It is clear from both images that. Males are the most common users of bikes. Users who have identified as Male make up more than two-thirds of the total users. The hours of usage for males and females follow the same trend as seen in NYC CitiBike Challenge_4.
  * ![NYC CitiBike Challenge_7](https://github.com/RuthLD/bikesharing/blob/main/Resources/NYC%20CitiBike%20Challenge_7.png)
  * NYC CitiBike Challenge_7 shows the breakdown of what user type of customer uses the bike share program on any day of the week. There two user types: subscribers and customer. Subscribers are returning users, and customers are categorized as single ride users. More users identifying as either males or females are subscribers, while most users under the customer categories are listed as gender unknown. For female subscribers, Wednesdays are the least popular day for using the bike share program. For male subscribers, Thursdays are the most popular day for the bike share program, but most days have high usage for male subscribers in general. Saturdays and Sundays are the highest bike use time for customers.
## Summary: 
* The are several takeaways from the Citi Bike Data from NYC as a model for the program.
1. Bike stations should be under 20 minutes away from each other in areas where there is already a lot of foot traffic—the starting and ending locations from NYC support this and the trip duration. 
1. A subscriber user model works well for a consistent bike share throughout the week before and after work hours. A non-subscriber option needs to be included for the customers who only use the program once as they visit the city. A higher number of bike shares will occur during the weekend for both user types. 
1. Individuals who identify as Male are likely to make up the subscriber base.
* Other visualizations that may be useful for further analysis include adding additional months to gauge a year-long business model. Additionally, more information related to the age of the user would be helpful to create a better customer profile for marketing.
