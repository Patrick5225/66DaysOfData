# 66DaysOfData Round 3

**Day 1 of #66DaysOfData (July 1, 2021):**

- The company that I work at uses Power BI a lot for creating reports and I wanted to improve my overall understanding of Power BI Desktop and Service, so I decided to study for the DA-100 Microsoft exam by taking a Udemy course I found online to help prepare myself for the exam. I started off the course by learning some basic data preparation, including using the query editor and connecting to data with JSON files.

- Started watching the first video from StatQuest's 66DaysofData playlist. This video gives an intuitive explanation of what histograms are. Nothing too advanced here, but just wanted to start off this challenge lightly.

---

**Day 2 of #66DaysOfData (July 2, 2021):**

- I thought about starting a new project that I could work on, but I realized I had a ton of older projects that I started before but never finished.. so I'm revisiting one of my older projects. In particular, I'm going back to working on this project where I would create a Power BI dashboard that visualizes the number of steps I'm walking each day. This data is collected from my phone's Health app over the span of 3 years.

  - From what I worked on so far on my project, I learned how to create a calendar table on Power BI using the CalendarAuto() DAX function. With this function, the calendar table is automatically created with a column of dates based on the minimum and maximum date values in the data model. I also learned that with the combination of the AVERAGEX() and VALUES() DAX functions, I can calculate the average amount of steps I took per day. Pretty cool functions that I may consider using at my job one day :)

- Did some more DA-100 Exam prep by learning about how to connect to Power BI Data Source files (PBIDS) and to the Microsoft Dataverse

---

**Day 3 of #66DaysOfData (July 3, 2021):**

- Continued working on my Pedometer project. I read this blog post (https://insightsoftware.com/blog/working-with-weeks-in-power-bi/) on how to measure values by week number and by day of the week. I learned that I can use the WEEKDAY() DAX function that returns the day of the week as a numeric value from 1 to 7, and also the FORMAT() function  where I could convert the day number into an actual day name (Sunday, Monday, and so on). Implementing what I read and learned, I was able to create a bar chart that visualizes the number of steps I took by day of the week. From the bar chart visual, in terms of the amount of steps taken, I noticed that I was 3x more active during the weekdays than during the weekends :sweat_smile:

- DA-100 Exam Prep: Watched videos on how to connect Power BI to SQL Server Analysis Services (SSAS) and to SharePoint Online

- Watched a StatQuest video on statistical distributions

---

**Day 4 of #66DaysOfData (July 4, 2021):**

- More Power BI learning, including different storage modes (import, DirectQuery, and Dual), Data Source Settings, and using Parameters to change data source values dynamically in Power Query

---

**Day 5 of #66DaysOfData (July 5, 2021):**

- Learned about Power BI's data profiling tools such as column quality, column distribution, and column profile

- Solved SQL problems from Stratascratch

---

**Day 6 of #66DaysOfData (July 6, 2021):**

- Reviewed and learned about Power BI's basic table transformations within Power Query, including how to add index columns, conditional columns, and columns from example

- Watched a StatQuest video on Hypothesis Testing and the Null Hypothesis

---

**Day 7 of #66DaysOfData (July 7, 2021):**

- Reviewed more tools within the Power Query Editor in Power BI, including grouping and aggregation, pivoting/unpivoting, and merging/appending/modifying queries.

- Learned about the basics of M code within Power Query and how it is used to edit applied steps, including the common M function categories, M code syntax, and using the advanced editor to view the M code that makes up a query

- Thinking about redoing Jose Portilla's Udemy Course on Python for Machine Learning (only finished about 40% of the course) starting tomorrow, so I went ahead and installed Anaconda on my computer

- Continued working on pedometer project, adding new measures and columns using DAX

---

**Day 8 of #66DaysOfData (July 8, 2021):**

- Reviewed Data Modeling concepts within Power BI, such as the difference between Data Tables and Lookup Tables, creating table relationships, filter flows, snowflake vs. star schemas, automatic date tables, and optimizing data models

- Had a tough time during work today trying to split datetime fields into multiple records with SQL. Still, after Googling many times, I got a chance to learn about using UNION ALL and common table expressions

- Reviewed basics of Python including data types, variables, lists, dictionaries, tuples, and sets

---

**Day 9 of #66DaysOfData (July 9, 2021):**

- Was messing around more with M code within Power BI and figured out how to replace multiple values that are in the same column with just one applied step. M code was intimidating to me at first, but with more practice that I did today, it's not as bad anymore

- Read this blog post on (https://alluringbi.com/2020/08/06/consolidating-report-elements-for-improved-performance/) about some useful tips to decrease the number of visuals in a report, which helps increase performance of reports by reducing page loading times. Some tips that were shown included using a single matrix instead of a bunch of individual cards, and using a background instead of placing text or shapes on the report.

---

**Day 10 of #66DaysOfData (July 10, 2021):**

- Reviewed DAX functions within Power BI including CALCULATE, USERLATIONSHIP, ALL, FILTER, TOPN, and Time Intelligence Functions
