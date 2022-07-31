# Tableau

## Background

![image](https://user-images.githubusercontent.com/99145651/182004040-ed8c2ad0-57f1-41d7-a51c-78d503eac635.png)

Congratulations on your new job! As the new lead analyst for the [New York Citi Bike](https://en.wikipedia.org/wiki/Citi_Bike) Program, you are now responsible for overseeing the largest bike-sharing program in the United States. In your new role, you will be expected to generate regular reports for city officials looking to publicize and improve the city program.

Since 2013, the Citi Bike Program has implemented a robust infrastructure for collecting data on the program's utilization. Each month, bike data is collected, organized, and made public on the [Citi Bike Data](https://www.citibikenyc.com/system-data) webpage.

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have questions about the program, so your first task on the job is to build a set of data reports to provide the answers.

## Primary Tasks

Analyze the data in the Citi Bike Trip History Logs and find two unexpected phenomena.

1. Low amount of customer users. With the success in New York and a city of tourism, it was surprising that there wasn't a higher number of casual customers.

![image](https://user-images.githubusercontent.com/99145651/182004378-63da59f1-83eb-4ee4-8353-7bae88303071.png)

Perhaps implenting a customized pricing rate will encourage people to use the bikes. Many people are working remotely but the hybrid work from home model is prevealnt in today's society. It can beneficail to offer a lower rate for shorter trips to attract the individual that doesn’t commute daily. That may increase the usage and possibly generate increased profit.

2. Disparity between male and female users during the summer. The breakdown by gender and age reveals that riders are predominantly male. With usually more increased consciousness when it comes to the environement and health this was a surprise. 

![image](https://user-images.githubusercontent.com/99145651/182004611-c9394c78-f60a-47cf-984e-8256e20f49f0.png)

Some efforts should probably be taken in analyzing the need to accommodate females or those with varying physical ability. Men took a considerable higher amount of cycling trips as women. Females are the key to getting more people on to bikes. With Citi Bike offering bikes in just one size and despite having adjustable seat height, the bike is still too high for some users and challenging to operate, raising safety concerns. This may contribute the fewer female usage that may not be able to ride with kids for leisure or exercise. CitiBike should consider adding bikes in a smaller size to tap close this gap.

## Additional Studies

1. Design 2–5 visualizations for each discovered phenomenon (4–10 total). You may work with a timespan of your choosing. Optionally, you can also merge multiple datasets from different periods.

The following are questions you may wish to answer. Do not limit yourself to these questions; they are suggestions for a starting point. Be creative!

* Today, what are the top 10 stations in the city for starting a journey? Based on data, why do you hypothesize these are the top locations?
![image](https://user-images.githubusercontent.com/99145651/181997293-fe2af308-13ac-48f9-948f-685e9af464e9.png)

* Today, what are the top 10 stations in the city for ending a journey? Based on data, why?
![image](https://user-images.githubusercontent.com/99145651/181997508-5ddb5f87-21a4-4e8b-81bd-f0a2af586d6f.png)

### The most active bike stations are located Downtown. Topping the list is the Grove Street PATH bike station, located now on Columbus Drive and Grove Street: 40931 trips originated there and 50623 trips ended there. Exchange Place and Hamilton Park are the next most popular stations, followed by Sip Avenue (near the Journal Square PATH station), then Newport PATH station. These have a high subscriber base and many of the users are more than likely commuting to and from work.


* What are the station most used during the summer and winter months?
![image](https://user-images.githubusercontent.com/99145651/181996635-4ae5fc04-c8ce-4578-8e62-a155b47c7902.png)

* Today, what are the bottom 10 stations in the city for starting a journey? Based on data, why?
![image](https://user-images.githubusercontent.com/99145651/181999033-630ea85b-c24e-47f1-9e8f-a934fb96dc9c.png)

* Today, what are the bottom 10 stations in the city for ending a journey? Based on data, why?
![image](https://user-images.githubusercontent.com/99145651/182001655-671072b7-d0b4-4906-aea3-5082eaea092c.png)

### The locations of the bike kiosks become less dense the farther away they are from the city's PATH stations, leading to some grumbling that the system doesn't work as well for cyclists who live outside of Downtown. Customers that live further from a Citi Bike station probably choose to utilize it when there isn't a bike kiosk near their home. The question and reality for these individuals is that it's not viable to pick up the bike at a light rail stop to ride, then , to another light rail stop? 

Which bikes (by ID) are most likely due for repair or inspection in the timespan?
![image](https://user-images.githubusercontent.com/99145651/181996672-3d6640b2-c5d7-4a95-b652-05c714e0ec8a.png)

2. Use your visualizations (not necessarily all of them) to design a dashboard for each phenomenon. The dashboards should be accompanied by an analysis explaining why the phenomenon may be occurring. 
 
![image](https://user-images.githubusercontent.com/99145651/182002687-b03f0d8d-74d6-4555-954d-4d5beddc14b5.png)

3. Create one of the following visualizations for city officials:

* **Basic:** A static map that plots all bike stations with a visual indication of the most popular locations to start and end a journey, with zip code data overlaid on top.

![image](https://user-images.githubusercontent.com/99145651/181996714-7af3cf5b-7732-4029-b73f-127f1e093d7f.png)

The Jersey City CitBike project was launched back in 2015. Jersey City was to have at least one Citi Bike station as part of an effort to allow every resident in the city to participate. Citi Bike is the nation’s biggest bike share system and reached the milestone of 100 millionth trip in 2020. Study has shown that bike in the New Jersey system is used 2.2 times, and each station is used 22 times on average each day. Compared to NYC’s bikes which get more use at an average of 4.4 times per bike and 65 times per station, there's potential still yet to grow.
 
![image](https://user-images.githubusercontent.com/99145651/182003105-034483f2-28a5-4286-ad43-4ec194c1f65e.png)
 
## Data 
The data analysis was by joining CSV files through Pandas.
 
## Analysis

From this dataset, the opportunities to grow users and membership were identiied in the customer usertype and female users. Most of the activity occurred within the downtown area which is a product of the proximity to local train stations and other public transit. A few items to consider are as follows:

1. Promotional advertisements, campaigns and pricing to bring in people that may potential increase usage or membership after an CitiBike anexperience. 
2. Additional bikes that are smaller and user friendly to female customers and those with varying physical capabilities.
3. Continued decommission of the least active stations. 
4. Reassignment of equipment from these stations to the more active stations.




