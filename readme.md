# Ford GoBike Data Analysis
## By Asmer Amen

## Introduction
- This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.
- This notebook explores the Ford GoBike's trip data for public containing bike rides from 2018. The attributes included the trip start/end time, as well as additional measurements such as user type, gender, and age.

## Project overview
1. Data Gathering
    - I choose Ford GoBike bike ride data for 2018. 
    - The data was downloaded from here https://www.fordgobike.com/system-data. 
    - The data is about bike ride trips, Each trip is anonymized and includes:
        - Trip Duration (seconds)
        - Start Time and Date
        - End Time and Date
        - Start Station ID
        - Start Station Name
        - Start Station Latitude
        - Start Station Longitude
        - End Station ID
        - End Station Name
        - End Station Latitude
        - End Station Longitude
        - Bike ID
        - User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual)

2. Data Exploring
    - I'll Explore the data and document my findings in a report. The report will briefly introduce the dataset, then systematically walk through the points of exploration that I conducted.
3. Data Explaining
    - At the end of the exploration, I'll probably have a bunch of things that I’ve discovered. So I'm going to organize my findings and select a story that I will convey to others. Then summarize my main findings and reflect on the steps I took in my data exploration in this readme document.

## Summary of Findings
1. Members tend to go for ride trip on spring, summer and fall more than winter. and on week days rather than week ends, spceially on the time to commute to and from work.
2. Most of the members are males.
3. Members with age range of 30-40 have the most records to use bikes, specially for males. However, their trip duration avrage is less than women.
4. Trip duration average varies for age ranges, where the best is 10-20 then 20-30 and 50-60.
5. Since number of subscriber user is almost 8 times customer user, they define the trend when it comes to total count of rides over the year months. However cutomer user have bigger trip duration.

## Key Insights for Presentation
- For the presentation, I focus on the influence of months, weekday, time and age group of bike trips data.
- I start by checking the monthly trend and see that members tend to go for ride trip on spring, summer and fall more than winter. 
- Then members genders and see that most of the members are males.
- For week days, wee members prefer week days to week ends, specially on the time to commute to and from work.
- For age, I split the members into bins based on their ages each has 10 years range, and we see members with age range of 30-40 have the most records to use bikes, specially for males. 
- For user type, I check the percentage of each of the 2 types Customer and Subscriber to the total data, and find that subscriber users are almost 8 times customer users. This cause the subscriber users have more bikes count and so they shape the trend specially for no. of rides per month.
- Next check Trip average duration time based on user type, gender, age, and start hour:
    - For user type: we see customers have higher average duration time, compared to subscribers who are 8 times the number of customers and supposed to be regulars.
    - For gender: females have the highest average trip duration time (~15 min.), then other genders (~14 min.), then males (~12 min.).
    - For age ranges: youngest range (10-20) have the highest average duration time, followed by the oldest range (50-60), and the range with highest number of members (30-40) has the lowest average duration time.
    - For start hour: the first 4 hours after midnight have the highest trip duration, specially 3 a.m with average of (~ 23 min.).
- Next check number of trip rides over the weed days based on user type, gender and age:
    - For user type: Since subscriber users are almost 90% of the users, they control the trend showing the same days trip count percentages as the total users. And the customer users percentage of rides are almost the same on weekdays and weekends.
    - For gender: We see no big difference from the all users graph, as for all gender the rides percentage drops almost the half on weekends. 
    - For age: Same as the gender part we see no big difference from the all users graph.
- Next check trip rides percentage for each gender based on age range:
    - We see the most rides are by male members of age range 30-40 and most of female members riders are in range 20-40.
- Moving to trip rides number for user types based on gender:
    - We see male subscriber user significantly the most number of rides.
- The most important part is the number of trips for each hour over the week days, which indicate that high number of users use bikes to commute to and from work, since the 2 high spots in the heat map are around the time to go to/leave work.


    