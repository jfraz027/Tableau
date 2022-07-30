# Tableau

## Background

[Citi-Bikes](Images/citi-bike-station-bikes.jpg)

Congratulations on your new job! As the new lead analyst for the [New York Citi Bike](https://en.wikipedia.org/wiki/Citi_Bike) Program, you are now responsible for overseeing the largest bike-sharing program in the United States. In your new role, you will be expected to generate regular reports for city officials looking to publicize and improve the city program.

Since 2013, the Citi Bike Program has implemented a robust infrastructure for collecting data on the program's utilization. Each month, bike data is collected, organized, and made public on the [Citi Bike Data](https://www.citibikenyc.com/system-data) webpage.

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have questions about the program, so your first task on the job is to build a set of data reports to provide the answers.

## Tasks

Analyze the data in the Citi Bike Trip History Logs and find two unexpected phenomena.

1. Design 2–5 visualizations for each discovered phenomenon (4–10 total). You may work with a timespan of your choosing. Optionally, you can also merge multiple datasets from different periods.

The following are questions you may wish to answer. Do not limit yourself to these questions; they are suggestions for a starting point. Be creative!

* Today, what are the top 10 stations in the city for starting a journey? Based on data, why do you hypothesize these are the top locations?
![image](https://user-images.githubusercontent.com/99145651/181997293-fe2af308-13ac-48f9-948f-685e9af464e9.png)

* Today, what are the top 10 stations in the city for ending a journey? Based on data, why?
![image](https://user-images.githubusercontent.com/99145651/181997508-5ddb5f87-21a4-4e8b-81bd-f0a2af586d6f.png)

* What are the station most used during the summer and winter months?
![image](https://user-images.githubusercontent.com/99145651/181996635-4ae5fc04-c8ce-4578-8e62-a155b47c7902.png)

* Today, what are the bottom 10 stations in the city for starting a journey? Based on data, why?
![image](https://user-images.githubusercontent.com/99145651/181999033-630ea85b-c24e-47f1-9e8f-a934fb96dc9c.png)

* Today, what are the bottom 10 stations in the city for ending a journey? Based on data, why?
![image](https://user-images.githubusercontent.com/99145651/182001655-671072b7-d0b4-4906-aea3-5082eaea092c.png)

* Which bikes (by ID) are most likely due for repair or inspection in the timespan?
![image](https://user-images.githubusercontent.com/99145651/181996672-3d6640b2-c5d7-4a95-b652-05c714e0ec8a.png)

2. Use your visualizations (not necessarily all of them) to design a dashboard for each phenomenon. The dashboards should be accompanied by an analysis explaining why the phenomenon may be occurring. 

3. Create one of the following visualizations for city officials:

* **Basic:** A static map that plots all bike stations with a visual indication of the most popular locations to start and end a journey, with zip code data overlaid on top.
![image](https://user-images.githubusercontent.com/99145651/181996714-7af3cf5b-7732-4029-b73f-127f1e093d7f.png)

* **Advanced:** A dynamic map that shows how each station's popularity changes over time (by month and year). Again, with zip code data overlaid on the map.

* The map you choose should also be accompanied by a write-up describing any trends that were noticed during your analysis.

4. Create your final presentation.

    * Create a Tableau story that brings together the visualizations, requested maps, and dashboards.

    * Ensure your presentation is professional, logical, and visually appealing. 

## Considerations

Remember, the people reading your analysis will NOT be data analysts. Your audience will be city officials, public administrators, and heads of New York City municipal departments. Your data and analysis need to be presented in a way that is focused, concise, easy to understand, and visually compelling. Your visualizations should be colorful enough to be included in press releases, and your analysis should be thoughtful enough to inform programmatic changes. 

## Submission 

Your final submission should include:

* A link to your Tableau Public workbook that includes the following:
  * 4–10 total "phenomenon" visualizations 
  * 2 dashboards
  * 1 city official map
  * 1 story 
  * A text or markdown file with your analysis of the phenomena you uncovered in the data.

## Sharing Your Work

To share your work, we are asking that you save your workbook as a `.twb`x file so your TAs can grade them.

To save your workbook as a .twbx file, select "Save As..." from the "File" drop-down. Then, select the .twbx option.

## Assessment

Your final product will be assessed on the following metrics:

* Analytic Rigor

* Readability

* Visual Appeal


## Hints

* You may need to get creative with how you combine each of the CSV files. Don't just assume Tableau is the right tool for the job. At this point, you have a wealth of technical skills and research abilities. Dig for an approach that works, and go with it.

* Don't assume that the CSV format hasn't changed since 2013. Subtle changes to the formats in any of your columns can interfere with your analysis. Ensure that your data is consistent and clean throughout your analysis. (Hint: Start and End Time change at some point in the history logs).

* Consider building your visualizations with small extracts of the data (like single files) before attempting to import the whole thing. What you will find is that importing all 20+ million records of data will create performance issues quickly. Welcome to "Big Data."

* While utilizing all of the data may seem like a nice power play, consider the time course in making your analysis. Is data from 2013 the most relevant for making bike replacement decisions today? Probably not. Don't let overwhelming data fool you. Ground your analysis in common sense.

* Remember, data alone doesn't answer anything. You will need to accompany your data visualizations with clear and directed answers and analysis.

* As is often the case, your clients are asking for a LOT of answers. Be considerate about their “need to know” and the importance of not "cramming in everything.” Of course, answer each question, but do so in a way that is organized and presentable.

* Since this is a project for the city, spend the appropriate time thinking through decisions on color schemes, fonts, and visual storytelling. The Citi Bike program has a clear visual style. As a suggestion, look for ways to have your data visualizations match their aesthetic.

* Pay attention to labels. What exactly is "time duration?” What's the value of "age of birth?” You will almost certainly need calculated fields to get what you need.

* Look for obvious outliers or false data. Not everyone who signs up for the program is answering honestly.

* In answering the question of "why" a phenomenon is occurring, consider adding other pieces of information, like socioeconomic or geographic data. Tableau has a map "layer" feature that you may find helpful.

* Don't be afraid to manipulate your data and play with settings in Tableau. Tableau is meant to be explored. We haven't covered everything that you’ll need &mdash; so keep an eye out for new tricks!
