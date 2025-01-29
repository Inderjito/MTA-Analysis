https://medium.com/@sunita-inderjit/new-york-city-subway-incident-analysis-1fd56fc79aa0

![image](https://github.com/user-attachments/assets/ef10e4d6-6775-41b6-94fd-3bd12b837988)
Project Outline
Abstract
Objective
Problem Statement
Tools & Libraries
Data Description
Analysis
Key Insights
Recommendation
Abstract
The New York City Metropolitan Transportation Authority (MTA) subway system experiences numerous operational disturbances. These incidents are pain points that impact subway operations, commuters’ daily safety, and service reliability. This analysis aims to find the root cause and factors that influence subway rider experiences and daily travel schedules.

Objective
The goal of this project is to explore and uncover major challenges that disrupt services for New York City Subway riders. Millions of New Yorkers rely on the subway for daily commutes to work and other travel needs. Exploring the data will help to better understand some of the factors that influence delays and also look at patterns during different seasons of the year and weekends vs. weekdays, how that might contribute to some of the problems, and what MTA can do to improve service for NYC daily commuters.

Problem Statement
This analysis used historical data from 2020 to November 2024 to gain insights and better understand the contributing factors behind incidents that affect service quality and rider safety in NYC

Identify the most frequent incident categories, divisions, and lines affected.
Uncover seasonal trends and patterns in incidents across time.
Understand the severity of incidents
Assess the relationship between day types (weekdays, weekends) and incident occurrences.
Tools and Libraries
Google Colab

Tableau Desktop

Python program

Pandas, numpy, matplothlib and seaborn

Understanding the Dataset
Data collected was collected from Data.gov
Jan 2000 to November 2024
Data type = CVS
Columns = 6 and Rows = 1966
Data Description
Month: The month in which the Major Incidents are being calculated (yyyy-mm-dd).

Division The A Division (numbered subway lines) and B Division (lettered subway lines).

Line: Each subway line (1, 2, 3, 4, 5, 6, 7, A, C, E, B, D, F, M, G, J, Z, L, N, Q, R, W, S 42nd, S Rock, S Fkln).

day_type: Represents weekday as 1, weekend as 2.

Category:The six categories that fall under the definition of a Major Incident: Track, Signals, Persons on Trackbed/Police/Medical, Stations and Structure, Subway Car, and Other.

Count: The number of major incidents that occurred per month and per subway line.
