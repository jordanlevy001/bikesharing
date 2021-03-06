# August 2019 New York City (NYC) Citi Bike Analysis

## Project Overview
The purpose of this project was to analyze the NYC Citi Bike data from August 2019; then utilize these key findings/trends to write a business proposal for a similar program in another city: Des Moines, Iowa.

To access the NYC Citi Bike Analysis story: https://public.tableau.com/app/profile/jordan.levy7208/viz/NYCCitiBikeChallenge_16371713967990/NYCCitiBikeAnalysis?publish=yes

## Results

1. NYC Citi Bike General Info

<img width="665" alt="Gen Info" src="https://user-images.githubusercontent.com/88804543/142289074-3d7efc72-4e35-4bfa-89a1-ef7f89f85f34.png">

This first story point shows the total number of rides taken in August 2019 in NYC, the gender breakdown and usertype breakdown of the riders. It is helpful to have an understanding of how many people are using the Citi Bikes. Furthermore, the gender breakdown is critical for this analysis, so this first storypoint provides the numbers of male/female/unknown(gender) users. There are about 3 times more male users than female users. It also important to note that there are about 4 times more annual subscribers than short term customers. These numbers will help contextualize the content in the rest of the story.


2. August Peak Hours

<img width="973" alt="August Peak Hours" src="https://user-images.githubusercontent.com/88804543/142275612-b2cb6609-98a7-488a-bf54-0fe39305a278.png">

This bar graph shows the number of bikes in use at each hour of the day. Peak usage occurs around 5pm to 7pm. This graph also provides insight for the ideal time for bike maintenance, the time when the usage is lowest. The ideal time for bike maintenance is around 2am to 4am.


3. Common Trip Duration

<img width="1000" alt="Common Trip Duration" src="https://user-images.githubusercontent.com/88804543/142283995-a74fd88c-4b3a-4554-a2a9-cf12c09c2488.png">

This chart displays the trip duration of every ride in minutes. You can filter this chart by the hour of the day. Most rides are under 30 minutes long.


4. Common Trip Duration by Gender

<img width="1002" alt="Trip Duration by Gender" src="https://user-images.githubusercontent.com/88804543/142285923-ad9b5644-3c38-4497-9e11-4f58e20c1a14.png">

This chart is similar to the previous one, but it filters the trip duration data by gender: male, female, unknown. As we saw from the first story point, there are about 3 times more men using Citi Bikes. Although there are more men riding the Citi Bikes, most trip durations regardless of gender are still less than 30 minutes. You can filter this chart by gender and/or hour of the day.


5. Common Riding Times by Weekday

<img width="1000" alt="Common Riding Times by Weekday" src="https://user-images.githubusercontent.com/88804543/142284938-cb9eb5c9-470d-47bd-8276-c3b4103f6cb6.png">

This heat map shows the start times of all of the rides on each day of the week: Sunday to Saturday. There are spikes in rides occuring from 7am - 9am, which is a typical time people to commute to work. There is another spike from 5pm -7pm, which is a common time people leave work. On Saturdays and Sundays, most people don't work and are free during the day, which is likely why there are more people riding in the middle of the day on the weekends.


6. Common Riding Times by Weekday and Gender

<img width="1000" alt="Times by Weekday by Gender Female" src="https://user-images.githubusercontent.com/88804543/142286516-648bd22f-716c-4d78-81cd-dc94f223d8e5.png">

<img width="1000" alt="Times by Weekday by Gender Male" src="https://user-images.githubusercontent.com/88804543/142286526-15c96656-b512-4e81-ae75-37371a935d81.png">

<img width="995" alt="Times by Weekday by Gender Unknown" src="https://user-images.githubusercontent.com/88804543/142286534-81c37fcf-b694-4134-8e2d-1bedd5d226b7.png">

This heat map is similar to the previous one (#5). It shows the riding times of all the rides on each day of the week, split up by gender (female, male, unknown). A very similar trend is observed between female and male riders: there are spikes in rides around the time people typically commute to and from work. But for the unknown gender data, rides typically occur in the middle of the day on Saturday and Sunday.


7. Common Riding Days by Gender and Usertype

<img width="988" alt="Common Weekdays by Gender Usertype" src="https://user-images.githubusercontent.com/88804543/142287362-680413c8-1000-4662-b33f-97fd13112df0.png">

This heat map shows the common weekdays rides occur filtered by gender (female, male, unknown) and usertype (customer, subscriber). A customer is a short term user and a subscriber has an annual subscription. There are more rides taken by subscribers than customers, which is consistent with the first story point, which showed there are 4 times more subscribers than customers. Males utilize bikesharing on all days of the week, especially on Thursday and Friday. Females utilize bikesharing during the week (Monday - Friday). 


8. Popular Starting Stations

<img width="1003" alt="Popular Starting Stations" src="https://user-images.githubusercontent.com/88804543/142287880-4154205b-fbee-420f-b3c8-479032987e00.png">

This chart shows the locations of the starting points of all of the rides. The size of each bubble is relative to the total number of rides. The darker the green each bubble is is relative to the total number of rides.


9. Popular Ending Stations

<img width="1006" alt="Popular Ending Stations" src="https://user-images.githubusercontent.com/88804543/142288388-b8792231-2665-4a8a-b2c6-9f51d1da9d36.png">

This chart shows the location of ending points of all of the rides. The size of each bubble is relative to the total number of rides. The darker the orange each bubble is is relative to the total number of rides.

## Summary

This analysis of the Citi Bike data from August 2019 in NYC provided key insights that will aid in writing a business proposal for a bikesharing business in Des Moines. Significantly more men utilize bikesharing, roughly 3 times more men than women are users. Most people tend to select an annual subscription, about 4 times more people are annual subscribers as compared to short term customers. Both males and females utilize bikesharing to commute to and from work during the week (Monday to Friday). Additionally, most trips taken on the bikes are under 30 minutes. People also use bikesharing around midday on weekends.

In the future, some additional visualizations might be helpful. First, it would be helpful to look at all of the months within 2019 to examine larger trends. It would be interesting to analyze if the peak usage hours change throughout the year. This would require us to look at all of the bikesharing records and the ride starting time hour. Second, we could look at trip duration and individual bicycles to determine how many miles have been ridden on each bike. This would help us determine which bikes require preventative maintenance or repairs.

