Google Data Analytics Capstone Project on Cyclistic Bike Share
Project Reference & Resource:  Google Data Analytics Capstone: Complete a Case Study
Project Quick Summary
I'll be acting as a junior data analyst at Cyclistic, a fictional company.
I'll encounter various characters and team members throughout the study.
My goal is to address critical business questions by following the data analysis process: ask, prepare, process, analyze, share, and act.
Tools used: MySQL, Tableau.
Project Introduction
Scenario
I am a junior data analyst at Cyclistic in the marketing analyst team.
The director of marketing thinks annual memberships are crucial for the company's success.
My team's goal is to analyze how casual riders and annual members use Cyclistic bikes differently.
We aim to use these insights to create a strategy for converting casual riders into annual members.
Our recommendations need approval from Cyclistic executives and require strong data insights and professional data visualizations.
Characters and teams
Cyclistic is a bike-share program that features more than 5,800 bicycles and 600 docking stations. Cyclistic sets itself apart by also offering reclining bikes, hand tricycles, and cargo bikes, making bike-share more inclusive to people with disabilities and riders who can't use a standard two-wheeled bike. The majority of riders opt for traditional bikes; about 8% of riders use the assistive options. Cyclistic users are more likely to ride for leisure, but about 30% use them to commute to work each day.

Lily Moreno is the director of marketing and my manager. Moreno is responsible for the development of campaigns and initiatives to promote the bike-share program. These may include email, social media, and other channels.

The Cyclistic marketing analytics team is a group of data analysts who are responsible for collecting, analyzing, and reporting data that helps guide Cyclistic marketing strategy. I joined this team six months ago and have been busy learning about Cyclistic's mission and business goals — as well as how I, as a junior data analyst, can help Cyclistic achieve them.

The Cyclistic executive team is known for being notoriously detail-oriented. They will decide whether to approve the recommended marketing program.

Project Kickoff
Ask Phase: Business Questions & Key Stakeholders
Three questions will guide the future marketing program:
How do annual members and casual riders use Cyclistic bikes differently?
Why would casual riders buy Cyclistic annual memberships?
How can Cyclistic use digital media to influence casual riders to become members?
Moreno has assigned me the first question to answer: How do annual members and casual riders use Cyclistic bikes differently?

Prepare Phase: Data Gathering & EDA Report
Data Gathering
I plan to utilize Cyclistic's archived trip information to conduct an analysis and detect patterns. This data can be obtained through the divvy_tripdata source, with permission granted by Motivate International Inc. pursuant to their licensing agreement.
Note - This is public data that you can use to explore how different customer types are using Cyclistic bikes. But note that data-privacy issues prohibit you from using riders’ personally identifiable information. This means that you won’t be able to connect pass purchases to credit card numbers to determine if casual riders live in the Cyclistic service area or if they have purchased multiple single passes.

Concerned Source Data
Data Timeframe: June 2022 to May 2023 (Past 1 year data)
Source Data Description and Structure:
The data is organized into individual .csv files, each corresponding to a specific month.
These files share common fields relevant to our analysis.
After our initial examination, we can confidently assert that the source data is Reliable, Original, Comprehensive, Current and Cited.
Tool Selection for Analysis
Tool for Data Cleaning, Transformation, and Processing: SQL
We chose SQL for these tasks because the dataset exceeded 5.8 million rows, making it impractical to manage with Excel (which is typically suitable for datasets of less than 1 million rows). SQL's capacity to handle large volumes of data makes it the preferred choice for data wrangling.
Tool for Analysis and Visualization: Tableau
While there are several tools available for data visualization, including Excel and Power BI, our selection of Tableau is deliberate. Tableau offers dynamic capabilities and a diverse range of visualization options, making it the ideal choice for our analytical and visualization needs.
Data Loading
File Naming Convention: Files are named in the format of YYYYMM-divvy.csv.
Data Integration into 'combined_Table': The data has been uploaded and consolidated into a unified table named 'combined_Table'. (To see the process of data upload and consolidation into a single table, please click here.)
Data Observation
Data Observation with MySQL
Size of Data (Rows & Column)
