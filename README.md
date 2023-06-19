# Google-Data-Analytics-Capstone-Case-Study
Course: https://www.coursera.org/learn/google-data-analytics-capstone

# Introduction
In this case study, I will analyze data as  a junior data analyst at a fictional company, Cyclistic. In order to answer the critical business questions, I will follow the steps of the data analysis process: Ask, Prepare, Process, Analyze, Share, and Act.

#links
data source: [divvy_tripdata](https://divvy-tripdata.s3.amazonaws.com/index.html)

# Case-Study
Cyclistic
A bike-share program that features more than 5,800 bicycles and 600 docking stations. Cyclistic sets itself apart by also offering reclining bikes, hand tricycles, and cargo bikes, making bike-share more inclusive to people with disabilities and riders who can’t use a standard two-wheeled bike. The majority of riders opt for traditional bikes; about 8% of riders use the assistive options. Cyclistic users are more likely to ride for leisure, but about 30% use them to commute to work each day.

Until now, Cyclistic’s marketing strategy relied on building general awareness and appealing to broad consumer segments. One approach that helped make these things possible was the flexibility of its pricing plans: single-ride passes, full-day passes, and annual memberships. Customers who purchase single-ride or full-day passes are referred to as casual riders. Customers who purchase annual memberships are Cyclistic members.

Cyclistic’s finance analysts have concluded that annual members are much more profitable than casual riders. Although the pricing flexibility helps Cyclistic attract more customers, Moreno (the director of marketing and my manager) believes that maximizing the number of annual members will be key to future growth. Rather than creating a marketing campaign that targets all-new customers, Moreno believes there is a very good chance to convert casual riders into members. She notes that casual riders are already aware of the Cyclistic program and have chosen Cyclistic for their mobility needs.

Moreno has set a clear goal: Design marketing strategies aimed at converting casual riders into annual members. In order to do that, however, the marketing analyst team needs to better understand how annual members and casual riders differ, why casual riders would buy a membership, and how digital media could affect their marketing tactics. Moreno and her team are interested in analyzing the Cyclistic historical bike trip data to identify trends.

# Scenario
I am assuming to be a junior data analyst working in the marketing analyst team at Cyclistic, a bike-share company in Chicago. The director of marketing believes the company’s future success depends on maximizing the number of annual memberships. Therefore, my team wants to understand how casual riders and annual members use Cyclistic bikes differently. From these insights, my team will design a new marketing strategy to convert casual riders into annual members. But first, Cyclistic executives must approve our recommendations, so they must be backed up with compelling data insights and professional data visualizations.

# Ask
### Business Task
Devise marketing strategies to convert casual riders to members.

### Analysis Questions
Three questions will guide the future marketing program:

How do annual members and casual riders use Cyclistic bikes differently?<br>
Why would casual riders buy Cyclistic annual memberships?<br>
How can Cyclistic use digital media to influence casual riders to become members?<br>

Moreno has assigned me the first question to answer: How do annual members and casual riders use Cyclistic bikes differently?

# Prepare
Data Source
I will use Cyclistic’s historical trip data to analyze and identify trends from Jan 2022 to Dec 2022 which can be downloaded from divvy_tripdata. The data has been made available by Motivate International Inc. under this license.

This is public data that can be used to explore how different customer types are using Cyclistic bikes. But note that data-privacy issues prohibit from using riders’ personally identifiable information. This means that we won’t be able to connect pass purchases to credit card numbers to determine if casual riders live in the Cyclistic service area or if they have purchased multiple single passes.

# Data Organization
There are 12 files with naming convention of YYYYMM-divvy-tripdata and each file includes information for one month, such as the ride id, bike type, start time, end time, start station, end station, start location, end location, and whether the rider is a member or not. The corresponding column names are ride_id, rideable_type, started_at, ended_at, start_station_name, start_station_id, end_station_name, end_station_id, start_lat, start_lng, end_lat, end_lng and member_casual.

# Process
JupyterNotebook  is used to combine the various datasets into one dataset and clean it.
Reason:
An excel worksheet can only have 1,048,576 rows in Microsoft Excel because of its inability to manage large amounts of data. Because the Cyclistic dataset has more than 5.6 million rows, it is essential to use a platform like Jupyter Notebook that supports huge volumes of data.

# Combining the Data
Jupyter tool : Data Combining
12 CSV files are uploaded as tables in the dataset '2022_tripdata'. Another table named "combined_data" is created, containing 5,667,717 rows of data for the entire year.

# Data Exploration
# Data cleaning
# Analyze and Share
 data analysis: [Jupyter Notebook (python)]()
 Data Visualization : [tableau](https://public.tableau.com/views/CyclisticDashboard_16871775780630/Dashboard1?:language=en-GB&:display_count=n&:origin=viz_share_link)

 ### The analysis question is: How do annual members and casual riders use Cyclistic bikes differently?
 1. The first chart shows the difference between how casual and members have taken the ride per month and we got the insight that in the month of July, member cyclists recorded the highest number of rides, and in August month casual cyclists recorded the highest rides.
 2. the second chart shows the types of rideable used by members and casual cyclists, we gain the insight that members don't use docked bikes.
 3. the third chart shows the ride length per minute by casual riders and member cyclists, we got to know that casual riders take rides for long distances whereas member ride for short distances
 4. The fourth chart shows how cyclists take rides in a week, we got to know that member's cyclist rides increase during working days whereas casual rider's rides increase during weekends and holidays.
 5. the fifth chart shows which rideable bikes are used mostly used in terms of months, and we got to know that docked bike rides remained constant with not much increase as compared to electric and classic bikes. 
 
 ![Dashboard 1](https://github.com/alimjahagirdar/Google-Data-Analytics-Capstone-Case-Study/assets/69685661/426f92b9-977b-4f3b-8e56-b50000699c82)

 # Act
 After identifying the differences between casual and member riders, marketing strategies to target casual riders can be developed to persuade them to become members.
Recommendations:

1. Marketing campaigns might be conducted in spring and summer at tourist locations popular among casual riders.
2. Casual riders are most active on weekends and during the summer and spring, so special season offers can be given to the casual riders to attract them to become a member.
3. since casual riders take rides for longer distances than members, discounts on long routes can be a good idea to attract members to take the ride for longer durations.

 


