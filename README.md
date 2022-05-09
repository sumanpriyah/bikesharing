# Bikesharing

## Overview of the Bike sharing analysis:
In this module we worked with Tableau analysis and Visualization tool. We imported data into Tableau and created worksheets , dashboard and stories to present business proposal for a bike sharing company to set up similar business model
in Des Moines. For this project data is extracted from a New York Citi Bike and created stories to visualize how actually bike business works in NY city. The data is picked from August as during summer months there is more traffic.

## Deliverables

1 Change Trip Duration to a Datetime Format

2 Create Visualizations for the Trip Analysis

3 Create a Story and Report for the Final Presentation

## Results:

### Checkout Times for Users
 
 ![](https://github.com/sumanpriyah/bikesharing/blob/main/Images/Checkout%20Times%20for%20Users.png)
As time duration is increasing the bike counts going down, In first 5 mins the max number of bikes count is there i.e 146,752. After 5 mins as trip duration increases the number of bikes start going down. Most of the population  
at that time of duration taking small distance trip. 

### Checkout Times by Gender
 ![](https://github.com/sumanpriyah/bikesharing/blob/main/Images/Checkout%20Times%20by%20Gender.png)
Looking at graph, it’s very clear that Male users checked out more bikes than Female users i.e in 5 mins 108,087 males checked out the bikes and 34,151 females checked out bikes during same time frame and only 5,624 unknown (not revealed Gender) checked out the bikes. 

### Trips by Weekday per Hour
![](https://github.com/sumanpriyah/bikesharing/blob/main/Images/Trips%20by%20Weekday%20per%20Hour.png)
During week day at 7 to 8 am and 5-7 pm more bikes get checked out than the same time during weekends. It indicates office time people might be using bikes to commute to office in morning (7-9am) and coming back home after office hours (5-7pm). 
During weekend people are using bikes mostly during the day time. 8 am and 5 pm are the busiest times when people commute to and from office. On weekends 10 am onwards is busy till 7 pm. Saturday is busier than Sunday. 

### Trips by Gender (Weekday per Hour)
![](https://github.com/sumanpriyah/bikesharing/blob/main/Images/Trips%20by%20Gender%20(Weekday%20per%20Hour).png)
As per graph males are using more bikes per hour than Female and unknowns to commute on week days and weekends. Males are using Bikes for office commute more than other two Gender categories. 
if we compare Thursday @ 8am which seems busiest time and day of week, Bikes rested out by females-9740, Males-25,694, Unknown-1080 and @5pm Females-10511, Males- 30,561 and Unknown- 2,910. 

### User Trips by Gender by Weekday
![](https://github.com/sumanpriyah/bikesharing/blob/main/Images/User%20Trips%20by%20Gender%20by%20Weekday.png)
This graph is showing that Subscribers tends to use more bikes during week days for Male and Female. Unknown as customers are using more bikes than as a subscriber during weekdays. Seems like unknown are the tourists or visitors
coming from other places to visit NYC. Subscribers (mostly yearly membership) are mostly locals and use bikes for local everyday commute. Subscription make it lot easier to use as user does not have to pay every time. 

### Top Ending Locations

![](https://github.com/sumanpriyah/bikesharing/blob/main/Images/Top%20Ending%20Locations.png)
The top ending location with high number of bikes are Union Square, Flatiron District, New York Penn Station, Grand Central Terminal, Battery Park city, Rockefeller Park, NY University, Columbus Circle. Grand Central Terminal have the maximum number of bikes 16,455.
These are the areas with parks, railway stations and places to hang out with bikes. 

### Bike Repairs
![](https://github.com/sumanpriyah/bikesharing/blob/main/Images/Bike%20Repairs.png)
The above graph gives us the status of bikes and maintenance needed. The bikes had more rides will get maintenance first. Per bike trips are calculated using bike id and total number of trips per bike. for example, Bike id - 38124 
had maximum trips 479. It displays on the top left side of graph where color range is dark and size of the block is bigger, shows per Bike id count is higher. On right side with color is lighter and 
blocks getting small the number of trips per bikes are less. From graph its easy to find which bikes need maintenance by looking number of trips per bike id. 


## Summary

City bike is NYC's official bike share program, designed to give residents and visitors as fun, affordable and convenient ride to visit and commute in NYC city.
City Bike in NYC is designed with convenience in mind for quick trips, Citi Bike is a fun and affordable way to get around the town.
The bikes and bike stations are across Manhattan, Brooklyn, Queens, the Bronx, Jersey City and Hoboken.
The two additional Visualization which can be important for Des Moines are number of bikes rented per hour during the week and by Gender and age group.

### Bike Rental per hour per week
![](https://github.com/sumanpriyah/bikesharing/blob/main/Images/bikes%20per%20week%20and%20per%20hour.png)
Maximum Bike renting for the week and hours 
Sunday and Saturday - Between 10 am to 7 pm
Monday, Tuesday, Wednesday, Thursday, Friday - 8 am and 5-6 pm 
Mostly people rent bikes on Thursday compare to other days of the week. Thursday 8 am 36515 and 5-6 pm - approx. 44,911 users rent the bikes.
Also, from the graph its clear Subscriber tends to rent bikes more than the customers. For Des Moines project it’s important to add more bikes in area close to offices so that 
people can commute within 5-10 mins instead of taking public transport. The subscription should be cost effective then every day pass or monthly pass that 
more people can subscribe and tend to use bikes for everyday commute. More bikes should be added around office hours in morning and evening near office locations.
Over the weekends more bikes should be provided for other busiest and popular location. Bike maintenance should be done on off hours when people tend to rent less bikes. 

### Bike Rental Gender and Birth year 
![](https://github.com/sumanpriyah/bikesharing/blob/main/Images/City%20Ride%20Gender_BirthYear.png)

Another graph gives us idea about people with certain age and Gender tends to rent more bikes. Where the average Male location is more with certain age group 
e.g people born from 1979 to 1996 tend to rent more bikes than other age group. Males rent more bikes than females and unknown.More bikes should be provided 
for certain age and male population who rents more bikes than other age and gender group.

Tableau Public link 

[link to dashboard](https://public.tableau.com/app/profile/suman.priya/viz/ABike-SharingAnalysisinNYCforDesMoinesProject/NYCCitiBikeDashboard?publish=yes)
