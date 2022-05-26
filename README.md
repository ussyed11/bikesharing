# bikesharing
## Overview

The purpose of Citi Bikesharing analysis is to prepare visualizations that give potential investors a look into the highly-successful NYC Citibike bike-sharing program, so that they can decide if a bike-sharing program in Des Moines is a profitable business proposal. Our visual analysis highlights key features such as :
* The length of time that bikes are rented for all riders and genders
* Show the number of bike trips for all riders and genders for each hour of each day of the week
* Show the number of bike trips for each type of user and gender for each day of the week.
.
## Resources and Results
We used the following resources to generate our visual analysis:

* Source Files: 201908-citibike-tripdata.csv, nyc_citibike_new.csv
* Software: Tableau, Python 3.7.6, Jupyter Notebook, Pandas Library

[This is an external link to our Tableau story] (https://public.tableau.com/views/NYCCitiBikeSharingAnalysis_16535281061040/NYCCitiBikeStory?:language=en-US&:display_count=n&:origin=viz_share_link) 

Our first Tableau story point shows that the bar graph shows that the August bike retal peak hours are betwen 5pm and 7pm.  We can conclude that people might be renting bikes after their work to either go back to their residences or to go to catch the public transportations.

![Screen Shot 2022-05-25 at 7 38 35 PM](https://user-images.githubusercontent.com/98566486/170386610-259517af-2fd8-48a4-86e6-0b2ca59194e5.png)

The second point in our Tableau story shows that male bike rental count is three times more than female bike rental count.  This requires further analysis to better understand the reason.

![Screen Shot 2022-05-25 at 10 01 12 PM](https://user-images.githubusercontent.com/98566486/170400077-b1708e19-46b6-489c-a94a-8f56ae90dd2d.png)


The third point has a doashboard with two worksheets.  We can say that the majority of bikes are rented for less than an hour.  Most bikes are rented for 10-15 minutes duration.  Male bike rental is dominant, however the rental duration remains same regradless of gender.

![Screen Shot 2022-05-25 at 7 41 44 PM](https://user-images.githubusercontent.com/98566486/170386871-59426e97-953a-4f21-9714-9341ce09b8a0.png)

The fourth point shows a worksheet with a heatmap and we can say that the peak rental periods are between weekdays' mornings ( 7 am - 9am ) and evening hours (5pm - 7pm except for Wednesday evenings).  Saturday and Sunday both days shows heavy rental periods between 9am-8pm.

![Screen Shot 2022-05-25 at 10 02 56 PM](https://user-images.githubusercontent.com/98566486/170400309-1c3ac7be-4e62-40a0-8c9c-f89bb855917c.png)


The fifth point concludes that bike rental timings are almost stay same regardless of gender, however male retal count is significantly higher.

![Screen Shot 2022-05-25 at 10 03 55 PM](https://user-images.githubusercontent.com/98566486/170400454-df2faa8e-fa50-4765-975f-afdc1e22c51d.png)

The sixth point shows that there are more male weekly subscribers than female subscribers.  For most customers the gender is unknown.  Subcribers rental periods are heavy during weekdays.  

![Screen Shot 2022-05-25 at 10 04 33 PM](https://user-images.githubusercontent.com/98566486/170400531-06f78348-f2c4-4408-93f3-ab594e8fcdd9.png)


## Summary
There were a total of 2,344,224 bike rides in August. From the data results we know that 1,900,359 users are Subscribers and there were 443,865 Customers riding.  Bikes rental count by males is three times more than female bike rental count.  Thursdays hold a slight preference over Fridays for highest demand of bikes. There are two peak rental times every weekday that align with traditional communting hours: 9am - 7pm.  There seems to be no correlation to gender demands for bikes during peak hours.  Citi bike sharing is a successful program in NYC, however we need few more visual analysis to confirm our findings:

1. Perform analysis on bike rental data for winter months, especially November and December
2. Bike availability during peak hours at popular rental places like Grand Central and Central Park.


