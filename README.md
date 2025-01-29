
![image](https://github.com/user-attachments/assets/ef10e4d6-6775-41b6-94fd-3bd12b837988)

# Project Outline
1. Abstract
2. Objective
3. Problem Statement
4. Tools & Libraries
5. Data Description
6. Analysis
7. Key Insights
8. Recommendation

## Abstract
The New York City Metropolitan Transportation Authority (MTA) subway system experiences numerous operational disturbances. These incidents are pain points that impact subway operations, commuters’ daily safety, and service reliability. This analysis aims to find the root cause and factors that influence subway rider experiences and daily travel schedules.

## Objective
The goal of this project is to explore and uncover major challenges that disrupt services for New York City Subway riders. Millions of New Yorkers rely on the subway for daily commutes to work and other travel needs. Exploring the data will help to better understand some of the factors that influence delays and also look at patterns during different seasons of the year and weekends vs. weekdays, how that might contribute to some of the problems, and what MTA can do to improve service for NYC daily commuters.

## Problem Statement
This analysis used historical data from 2020 to November 2024 to gain insights and better understand the contributing factors behind incidents that affect service quality and rider safety in NYC

- Identify the most frequent incident categories, divisions, and lines affected.
- Uncover seasonal trends and patterns in incidents across time.
- Understand the severity of incidents
- Assess the relationship between day types (weekdays, weekends) and incident occurrences.

  ## Tools and Libraries
- Google Colab

- Tableau Desktop

- Python program

- Pandas, numpy, matplothlib and seaborn

## Understanding the Dataset

Data collected was collected from Data.gov
Jan 2000 to November 2024
Data type = CVS
Columns = 6 and Rows = 1966

## Data Description
Month: The month in which the Major Incidents are being calculated (yyyy-mm-dd).

Division The A Division (numbered subway lines) and B Division (lettered subway lines).

Line: Each subway line (1, 2, 3, 4, 5, 6, 7, A, C, E, B, D, F, M, G, J, Z, L, N, Q, R, W, S 42nd, S Rock, S Fkln).

day_type: Represents weekday as 1, weekend as 2.

Category:The six categories that fall under the definition of a Major Incident: Track, Signals, Persons on Trackbed/Police/Medical, Stations and Structure, Subway Car, and Other.

Count: The number of major incidents that occurred per month and per subway line.


## Insights
Based on the analysis, the top categories of subway incidents are Persons on Trackbed/Police/Medical, Signals, and Track. Persons on Trackbed incidents consistently rank the highest across all months, emphasizing potential safety issues and operational challenges. Signal disruptions also present a significant problem, affecting service reliability and efficiency. Although track incidents occur less frequently, their impact on operations remains substantial.

Division A experiences the highest number of incidents compared to the B Division, with certain subway lines showing disproportionate disruptions. Weekday operations (Day Type 1) see higher incident counts than weekends (Day Type 2), possibly due to heavy traffic during workdays.

Seasonal trends show peaks in certain months, like January, February, and some July, for categories like Persons on Trackbed and Signals. These can be influenced by weather conditions in winter and summer, when more people living on the street flock to the subway station to escape the unpleasant seasonal conditions of heat and cool. And of course, when there is heavy snow, it affects signals and train tracks, causing lots of details.

## Recommendation
To address these challenges, MTA can implement measures to prevent Persons on Trackbed incidents, such as adding fencing, more surveillance systems, and safety protocols to reduce these incidents. Especially to high-incident divisions and lines, . Seasonal readiness and additional resources to prevent signal problems during winter seasons.

More resources are required for weekday operations for high-incident lines to create a smooth rider experience. Finally, public safety and passengers are very important. Therefore, I strongly believe having more NYPD officers in subways and trains is great for public and passenger protection and safety and potentially reduces people on the trackbed.

For those of us who ride the MTA train daily, it is daily anxiety because of so many homeless people on the trains on the subways. I have personal experience of people lying on the entire train seat sleeping, and you cannot do anything about it. Also, another big problem that is disgusting is people smoking in moving trains, and despite the no smoking sign, they still do it. Even if you wear a mask( which I always do), it’s still challenging to tolerate the smoke. I am eager to see how the number of this analysis will change by the end of 2025, which will increase commuters on the trains due to congestion pricing.
