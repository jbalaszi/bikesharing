# bikesharing
Analysis over Citi bike sharing program in New York City to develop a similar bike program in Des Moines.

## Overview
Two businesswomen wanted an analysis over the New York City CitiBike sharing program to determine if a similar bike sharing program would be successful in Des Moines, Iowa. The NYC data was analyzed to give potenial investors a snapshot of the program's performance during August 2019. The data revealved trends for times of the day, days of the week, gender, peak hours in August, and starting location. This anaylsis required the use of Pandas in order to convert the 'tripduration' column from an integer to a datetime datatype. We are able to utilize the converted datatype to create visualizations showing the length of time the bikes are checked out for all riders and genders, the number of bike trips for each type of user and gender for each day of the week, peak bike usage by hour, and top starting locations.

### Resources
- Python; Pandas
- 201908-citibike-tripdata.csv
- Tablaeu Public

## Results of NYC CitiBike for August 2019

### Link to Tableau Dashboard
NYC_CitiBike_Challenge: https://public.tableau.com/profile/joey.balaszi#!/vizhome/NYC_CitiBike_Challenge_16211151414750/NYCCitiBikeStory?publish=yes

### Peak Hours in August
Peak bike usage occurs at 5pm and then 6pm.

### Top Starting Locations
The most popular places for CitiBike customers in New York City are:
1. Pershing Square
2. Broadway
3. Tribecca Bridge

### Checkout Times for Users
Peak usage for NYC CitiBikes occurs at 5 minutes with 146,752 bikes being checked out in August 2019.

### Checkout Times by Gender
Males are the primary users of CitiBikes in August 2019. Female users at their peak are 68.4% less than male riders.

### Trips by Weekday
CitiBikes have the least usage between 12am to 5am on Saturdays and Sundays. This would be an optimal timeframe to perform maintenance on bikes.

### Trips by Gender (Weekday per Hour)
Citibikes are popular among both males and females. During the weekday, there is a large number of female and male riders at 8am, 5pm, and 6pm. On Satudays, trips occur the most between the hours of 9am and 7pm. On Sundays, male and female riders use Citibikes the most between 11am and 5pm.

### User Trips by Gender by Weekday
In August 2019 for NYC, Thursdays were the most popular day of the week for male and female subscribers to take CitiBike trips. Male and female customers take the most trips on Saturdays.

## Summary 
Overall, males were the primary users for CitiBikes in NYC during August 2019. The most usage occurred on Thursdays during late afternoon. Additional analysis is required to determine if the CitiBike Sharing Program would be a good fit in Des Moines, Iowa. 

In order to determine if CitiBikes will be profitable in Des Moines, Iowa, we must perform an anlaysis to compare both cities' population totals and growth rate. Publically available census data could be used to determine if Des Moines has a population total close to or high than New York City-giving insight on whether or not Citibikes would be a goof fit in Des Moines.

An additional visualization over Citibikes could provide investors further insight to determine if the bike sharing program would thrive in Iowa. An analysis comparing the two cities' weather data to see if there is any correlations between the NYC's and Des Moines' weather patterns. If temperatures and weather patterns are similar between the two, this could provide an even stronger case for investors to create a bike sharing program in Des Moines, Iowa.
