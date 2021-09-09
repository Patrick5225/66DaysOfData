# 66DaysOfData Round 3

**Day 1 of #66DaysOfData (July 1, 2021):**

- The company that I work at uses Power BI a lot for creating reports and I wanted to improve my overall understanding of Power BI Desktop and Service, so I decided to study for the DA-100 Microsoft exam by taking a Udemy course I found online to help prepare myself for the exam. I started off the course by learning some basic data preparation, including using the query editor and connecting to data with JSON files.

- Started watching the first video from StatQuest's 66DaysofData playlist. This video gives an intuitive explanation of what histograms are. Nothing too advanced here, but just wanted to start off this challenge lightly.

**Day 2 of #66DaysOfData (July 2, 2021):**

- I thought about starting a new project that I could work on, but I realized I had a ton of older projects that I started before but never finished.. so I'm revisiting one of my older projects. In particular, I'm going back to working on this project where I would create a Power BI dashboard that visualizes the number of steps I'm walking each day. This data is collected from my phone's Health app over the span of 3 years.

  - From what I worked on so far on my project, I learned how to create a calendar table on Power BI using the CalendarAuto() DAX function. With this function, the calendar table is automatically created with a column of dates based on the minimum and maximum date values in the data model. I also learned that with the combination of the AVERAGEX() and VALUES() DAX functions, I can calculate the average amount of steps I took per day. Pretty cool functions that I may consider using at my job one day :)

- Did some more DA-100 Exam prep by learning about how to connect to Power BI Data Source files (PBIDS) and to the Microsoft Dataverse

**Day 3 of #66DaysOfData (July 3, 2021):**

- Continued working on my Pedometer project. I read this blog post (https://insightsoftware.com/blog/working-with-weeks-in-power-bi/) on how to measure values by week number and by day of the week. I learned that I can use the WEEKDAY() DAX function that returns the day of the week as a numeric value from 1 to 7, and also the FORMAT() function  where I could convert the day number into an actual day name (Sunday, Monday, and so on). Implementing what I read and learned, I was able to create a bar chart that visualizes the number of steps I took by day of the week. From the bar chart visual, in terms of the amount of steps taken, I noticed that I was 3x more active during the weekdays than during the weekends :sweat_smile:

- DA-100 Exam Prep: Watched videos on how to connect Power BI to SQL Server Analysis Services (SSAS) and to SharePoint Online

- Watched a StatQuest video on statistical distributions

**Day 4 of #66DaysOfData (July 4, 2021):**

- More Power BI learning, including different storage modes (import, DirectQuery, and Dual), Data Source Settings, and using Parameters to change data source values dynamically in Power Query
