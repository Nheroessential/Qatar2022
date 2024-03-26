# Qatar2022: Stat Analysis using Excel

## Overview
The FIFA World Cup Qatar 2022™ was the 22nd edition of the tournament. Here are some key details:

  Host Country: Qatar 

  Stadiums: Eight stadiums in Qatar
  
  Teams: 32 national teams
  
  Matches: A total of 64 matches were played between 20 November and 18 December 2022

## Table of Contents
1. Introduction
2. Data Sources
3. Excel Analysis
4. Visualization
5. Conclusion


## Introduction
The 2022 FIFA World Cup was the 22nd edition of the world championship for national football teams, organized by FIFA. It took place in Qatar from 20 November to 18 December 2022 after the country was awarded the hosting rights in 2010. This tournament marked several significant milestones:

1. First World Cup in the Arab World and Muslim World: It was the first World Cup to be held in the Arab world and the Muslim world. Qatar’s hosting showcased the rich culture and passion for football in the region.
2. Change in Timing: To mitigate the extreme heat of Qatar’s climate, the event was held in November and December, a departure from the traditional months of May, June, or July. This reduced the time frame to 29 days, during which 64 matches were played across eight venues in five cities.
3. 32 Participating Teams: The 2022 World Cup featured 32 participating teams, but this format would change in the subsequent edition. The number of teams will be increased to 48 for the 2026 World Cup.
4. Historic Host: Qatar entered the event as the host’s national team, making it their first World Cup appearance.
The 2022 FIFA World Cup was a celebration of football excellence, cultural diversity, and global unity.

## Data Sources
The dataset was obtained from [Kaggle](https://www.kaggle.com/datasets/greysonmb/2022-world-cup-stats) in csv format. I performed data cleaning using power query and conditional formatting.

## Excel Analysis
The raw data had a lot of abbreviated column which I formatted properly.

![Dirty data](https://github.com/Nheroessential/Qatar2022/assets/90351195/a3a14b2b-40c5-4f20-83a7-4a66fbfe401e)

The Cleaned data:
![Cleaned football](https://github.com/Nheroessential/Qatar2022/assets/90351195/f9f2acb8-c831-4742-986a-9badf78192ff)

## Visualization
Creating a pivot table was the next step towards creating a dashboard that visualizes the participating nations individual stats. I utilized `VLOOKUP` to derive the Important stat that will go into the dashboard.
![Vlok](https://github.com/Nheroessential/Qatar2022/assets/90351195/a15d1022-0941-42e0-8ad0-b5dfb8b05752)


The final dashboard:
![wc dashboard](https://github.com/Nheroessential/Qatar2022/assets/90351195/27fb1425-70a8-4b13-a8c7-f8b2bf368a63)


## Conclusion
This dashboard easily displays the stats of selected nation.

