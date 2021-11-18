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

---

**Day 11 of #66DaysOfData (July 11, 2021):**

- Watched video from Guy in a Cube on getting started on understanding Power BI performance (https://www.youtube.com/watch?v=14KCckNbmvs&ab_channel=GuyinaCube). This video gives an introduction to the performance analyzer and some brief recommendations for optimizing performance 

---

**Day 12 of #66DaysOfData (July 12, 2021):**

- Watched a video from Guy in a Cube about a technique to reduce the number of visuals within a Power BI report to improve performance (https://www.youtube.com/watch?v=kkIXtvU1AiM&t=229s&ab_channel=GuyinaCube). The technique shown on the video is similar to a blog post I read a couple of days ago, except on this video, it takes it a step further by adding icons as a KPI indicator on the visuals

- Did some practice and messing around with some formatting options with objects and charts in Power BI, such as conditional formatting 

---

**Day 13 of #66DaysOfData (July 13, 2021):**

- Reviewed Power BI visuals and their features including drill-through filters, bookmarks, tooltips, and R/Python visuals

- Watched a video on SQL by Alex The Analyst on using Partition By with SQL (https://www.youtube.com/watch?v=D6XNlTfglW4&list=PLUaB-1hjhk8HTgPnBukmMq7QTe83ANirL&index=7&ab_channel=AlexTheAnalyst) 

---

**Day 14 of #66DaysOfData (July 14, 2021):**

- Spent most of the day analyzing and messing around with California COVID data on Power BI 

---

**Day 15 of #66DaysOfData (July 15, 2021):**

- Learned about Power BI's accessibility features including themes and tab/layer orders in the selection pane

- Watched a SQL video from Alex The Analyst on the Having clause with SQL (https://www.youtube.com/watch?v=tYBOMw7Ob8E&list=PLUaB-1hjhk8HTgPnBukmMq7QTe83ANirL&index=4&ab_channel=AlexTheAnalyst) 

---

**Day 16 of #66DaysOfData (July 16, 2021):

- Learned about the dashboard interface and how to create a dashboard in Power BI service. Also learned about managing and viewing roles in Power BI desktop

- Read w3schools tutorial on Python's replace() method (https://www.w3schools.com/python/ref_string_replace.asp) 

---

**Day 17 of #66DaysOfData (July 17, 2021):**

- Reviewed Python's comparison operators, if and else statements, for loops, while loops, range function, and list comprehension 

---

**Day 18 of #66DaysOfData (July 18, 2021):**

- Reviewed basics of Python's functions, lambda expressions, and methods such as lower(), upper(), and split() 

---

**Day 19 of #66DaysOfData (July 19, 2021):**

- Learned about chart analytics options within Power BI, such as constant lines for scatter charts, trend lines and forecasting for line charts. Also dived into Q&A visuals, key influencer visuals, and the decomposition tree visual 

---

**Day 20 of #66DaysOfData (July 20, 2021):**

- Learned about static row-level security (RLS) and dynamic RLS in Power BI

- Spent about an hour working on a Power BI report for my pedometer project 

---

**Day 21 of #66DaysOfData (July 21, 2021):**

- Learned about applying RLS, subscriptions, sharing options, user roles & permissions, publishing apps, and deployment pipelines, all within Power BI Service

- Watched a video on designing navigation panels in Power BI (https://www.youtube.com/watch?v=34pBbd92BQI&ab_channel=biDezine)

- Continued working on my Pedometer project 

---

**Day 22 of #66DaysOfData (July 22, 2021):**

- Slow day today. Spent my free time learning about data lineage within Power BI service 

---

**Day 23 of #66DaysOfData (July 23, 2021):**

- Watched videos on Udemy about incremental refreshes, endorsing content, and sensitivity labels in Power BI service 

---

**Day 24 of #66DaysOfData (July 24, 2021):**

- Read and completed Microsoft's learning path on Getting started with Microsoft data analytics, which includes modules on discovering data analysis, and getting started on building with Power BI. Also read the first module on the Preparing data for analysis which focuses on getting data in Power BI

---

**Day 25 of #66DaysOfData (July 25, 2021):**

- Read the 2nd module about cleaning, transforming, and loading data in Power BI on Microsoft's Preparing data for analysis learning path. Also read the 1st module about designing a data model in Power BI on Microsoft's Modeling data in Power BI learning path

- Finished working on my pedometer project using Power BI 

---

**Day 26 of #66DaysOfData (July 26, 2021):**

- Read Microsoft's modules on an introduction to creating measures using DAX, and optimizing a model for performance in Power BI 

---

**Day 27 of #66DaysOfData (July 27, 2021):**

- Read Microsoft's modules on working with Power BI visuals, and creating a data-driven story with Power BI reports

---

**Day 28 of #66DaysOfData (July 28, 2021):**

- Read Microsoft's modules on creating dashboards in Power BI, and creating paginated reports with the Power BI report builder

---

**Day 29 of #66DaysOfData (July 29, 2021):**

- Read Microsoft's modules on performing analytics in Power BI, and working with AI visuals in Power BI

- Spent a short amount of time making changes to pedometer project

---

**Day 30 of #66Days of Data (July 30, 2021):**

- Read Microsoft's modules on creating and managing workspaces in Power BI, managing datasets in Power BI, and implementing row-level security

- Worked on portfolio website 

---

**Day 31 of #66DaysOfData (July 31, 2021):**

- Took my DA-100: Analyzing Data with Power BI exam today and passed! 🥳 I am officially now a Microsoft Certified Data Analyst Associate!

- Watched Guy in a Cube's video on Query Dependency in Power BI (https://www.youtube.com/watch?v=jibBmpW3w_8&ab_channel=GuyinaCube) 

---

**Day 32 of #66DaysOfData (August 1, 2021):**

- Watched StatQuest video on the Normal Distribution (https://www.youtube.com/watch?v=rzFX5NWojp0&ab_channel=StatQuestwithJoshStarmer) 

---

**Day 33 of #66DaysOfData (August 2, 2021):**

Already halfway there! 😃 

- Watched a video by Guy in a Cube about a simple trick on changing column headers in a matrix visual in Power BI
(https://www.youtube.com/watch?v=_On_aX8DbJw&ab_channel=GuyinaCube) 

---

**Day 34 of #66DaysOfData (August 3, 2021):**

- Watched a video by Guy in a Cube about a trick on using Power BI bookmarks to switch contents on tooltips (https://www.youtube.com/watch?v=r46kUh40SN8&ab_channel=GuyinaCube)

- Although I already completed the program, I actually skipped the project portion of the Google Data Analytics Program. So I'm going back and working on a capstone project about a data analysis case study on Bellabeat. For today, I just read the introduction and details of the case study 

---

**Day 35 of #66DaysOfData (August 4, 2021):**

- Watched video by Guy in a Cube about the possible reasons that one should look into when trying to figure out why Power BI reports may be running slow (https://www.youtube.com/watch?v=91D1WrNrHtY&ab_channel=GuyinaCube)

---

**Day 36 of #66DaysOfData (August 5, 2021):**

- My company is looking into filtering data based on specific users accessing reports in Power BI.. so I went ahead and watched some videos online about Row-Level security, mainly those by Guy in a Cube

- Completed the "Ask" portion of the capstone project #2 from the  Google Data Analytics Program 

---

**Day 37 of #66DaysOfData (August 6, 2021):**

- Read a blog post by Maven Analytics on career tips for entry level data analysts (https://www.mavenanalytics.io/blog/10-tips-for-entry-level-data-analyst)

- Completed the "Prepare" portion of the capstone project #2 from the  Google Data Analytics Program 

---

**Day 38 of #66DaysOfData (August 7. 2021):**

- Watched video by Alex the Analyst on a SQL tutorial about installing SQL Server Management Studio and creating tables (https://www.youtube.com/watch?v=RSlqWnP-Dy8&ab_channel=AlexTheAnalyst)

- Continued working on Google Capstone project by importing files to SQL server 

---

**Day 39 of #66DaysOfData (August 8, 2021):**

- Watched video by Alex the Analyst on SQL basics, such as SELECT and aggregate functions, using SQL Server (https://www.youtube.com/watch?v=PyYgERKq25I&ab_channel=AlexTheAnalyst) 

---

**Day 40 of #66DaysOfData (August 9, 2021):**

- Watched video by Guy in a Cube about the Power Automate Visual in Power BI (https://www.youtube.com/watch?v=T0dsCUeCFjg&ab_channel=GuyinaCube)

- Watched video by Alex the Analyst on using the WHERE statement in SQL Server (https://www.youtube.com/watch?v=A9TOuDZTPDU&ab_channel=AlexTheAnalyst) 

---

**Day 41 of #66DaysOfData (August 10, 2021):**

- Read blog post by Maven Analytics about the 3 essential attributes that are needed for development as an analyst (https://www.mavenanalytics.io/blog/data-analyst-skills-trifecta)

- Watched video by Guy in a Cube about working with images using image URLs in Power BI (https://www.youtube.com/watch?v=uvYFyNkqWF4&ab_channel=GuyinaCube)

- Learned how to create databases, schemas, and tables in Snowflake 

---

**Day 42 of #66DaysOfData (August 11, 2021):**

- Watched video by Guy in a Cube about exploring the Visio visual in Power BI (https://www.youtube.com/watch?v=ZkL2jo3b_5M&ab_channel=GuyinaCube) 

---

**Day 43 of #66DaysOfData (August 12, 2021):**

- Watched video by Guy in a Cube about using the paginated visual in Power BI (https://www.youtube.com/watch?v=5Fcf8eXRq2E&ab_channel=GuyinaCube)

- Continued working on Google Capstone project by cleaning the data 

---

**Day 44 of #66DaysOfData (August 13, 2021):**

- Watched video by Data Professor on using the Overleaf editor to write LaTeX code to create article layouts (https://www.youtube.com/watch?v=mX8ctLGR_FY&ab_channel=DataProfessor)

- Started on Udemy course: Advanced DAX for Microsoft Power BI Desktop by Maven Analytics. Went over introduction to the course and data modeling fundamentals

- More data cleaning on Google Capstone Project 

---

**Day 45 of #66DaysOfData (August 14, 2021):**

- Continued Udemy Course: Advanced DAX for Microsoft Power BI Desktop. Went over basic DAX review

- Read article about some of the best practices in data analytics (https://towardsdatascience.com/best-practices-in-data-analytics-cfcb2baebcb3) 

---

**Day 46 of #66DaysOfData (August 15, 2021):**

- More data cleaning on Google Capstone project

- Read blog article by Maven Analytics on pro tips for dashboard designing (https://www.mavenanalytics.io/blog/6-pro-tips-for-dashboard-design?utm_source=linkedin&utm_campaign=DashboardDesignTips_er04202021) 

---

**Day 47 of #66DaysOfData (August 16, 2021):**

- Continued Udemy Course: Advanced DAX for Microsoft Power BI Desktop. Went over an introduction to the course project along with setting up the Data model for the course

- Read blog post by Maven Analytics on the career journey of a data analyst along with their advice for data analysts (https://www.mavenanalytics.io/blog/eriks-career-journey-and-advice-for-data-analysts)

- Watched Ken's Nearest Neighbors video about the guest speaker talking about how much the improvement of their data visualizations have changed over time (https://www.youtube.com/watch?v=LQGK4IL7kOE&ab_channel=KNNClips) 

---

**Day 48 of #66DaysOfData (August 17, 2021):**

- Read blog post by Maven Analytics on the most difficult analytics skills that recruiters think are difficult to find among data analysts (https://www.mavenanalytics.io/blog/the-hardest-analytics-skills-to-find)

- More data cleaning on Google Capstone Project with python on jupyter notebook 

---

**Day 49 of #66DaysOfData (August 18, 2021):**

- Watched video by Guy in a Cube about using conditional drill-throughs in Power BI with buttons (https://www.youtube.com/watch?v=4Qy-bksqExI&ab_channel=GuyinaCube)

---

**Day 50 of #66DaysOfData (August 19, 2021):**

- Watched video by Guy in a Cube about the 3 signs that one can look for that help us know when it is time to optimze our Power BI report (https://www.youtube.com/watch?v=uKSkMDEGM2I&ab_channel=GuyinaCube) 

---

**Day 51 of #66DaysOfData (August 20, 2021):**

- Continued Udemy course: Advanced DAX for Microsoft Power BI Desktop. Learned about how the 2 engines, the formula engine and the storage engine, work together to process every DAX query

- Watched video by Ken Jee about how data visualization is important for data science (https://www.youtube.com/watch?v=k8YxyrcAXJs&ab_channel=KenJee) 

---

**Day 52 of #66DaysOfData (August 21, 2021):**

- Watched video by Alex the Analyst on using Group By and Order By statements with SQL (https://www.youtube.com/watch?v=LXwfzIRD-Ds&list=PLUaB-1hjhk8GT6N5ne2qpf603sF26m2PW&index=4&ab_channel=AlexTheAnalyst) 

---

**Day 53 of #66DaysOfData (August 22, 2021):**

- Read blog post on Towards Data Science about 5 tips to boost Power BI development (https://towardsdatascience.com/5-tips-to-boost-your-power-bi-development-a44d7e782037)

---

**Day 54 of #66DaysOfData (August 23, 2021):**

- Watched video by Guy in a Cube about building a slicer panel in Power BI (https://www.youtube.com/watch?v=xy9nmSQeUWg&ab_channel=GuyinaCube)

- Continued Udemy Course: Advanced DAX for Power BI. Learned about the data and storage types stored by the interal DAX engine 

---

**Day 55 of #66DaysOfData (August 24, 2021):**

- Continued Udemy Course: Advanced DAX for Power BI. Learned about the Vertipaq's columnar data structure along with how it uses compression and encoding to reduce the amount of memory needed to evaluate DAX queries 

---

**Day 56 of #66DaysOfData (August 25, 2021):**

- Watched video by Guy in a Cube about 5 tips for improving public speaking or presentation skills (https://www.youtube.com/watch?v=2HYl3V5ak1U&ab_channel=GuyinaCube)

- Continued Udemy course: Advanced DAX for Power BI. Learned about the value encoding process that VertiPaq uses to covert values in a column into smaller values for storage 

---

**Day 57 of #66DaysOfData (August 26, 2021):**

- Continued Udemy course: Advanced DAX for Power BI. Learned about the hash encoding and run length encoding processes

---

**Day 58 of #66DaysOfData (August 27, 2021):**

- Continued Udemy course: Advanced DAX for Power BI. Learned about VertiPaq Relations, and reviewed the different DAX engines used in Power BI 

---

**Day 59 of #66DaysOfData (August 28, 2021):**

- Started Section 5 of Udemy Course: Advanced DAX for Power BI. Learned about some useful DAX keyboard shortcuts

- Read blog post about how to know how much data would be enough to find a statistically signifcant result (https://towardsdatascience.com/how-much-data-is-enough-366d5b11ca3c) 

---

**Day 60 of #66DaysOfData (August 29, 2021):**

- Continued Udemy Course: Advanced DAX for Power BI. Learned about the best practices for formatting DAX code
