# Yashwant Kannan Sathish Kumar - Data Analytics Portfolio

Hi, I'm Yashwant! I'm a 3rd-year Computer Science major at Cal Poly SLO with a burgeoning passion for data analytics. I've united this passion with my interest in NBA basketball to produce several data analytics projects, utilizing data to derive insight to improve game strategy and roster construction. This repository serves to showcase my skills and as a platform to share my projects + track my progress in Data Analytics and Data Science-related topics.

## Project 1: Analyzing Movement Shooting Proficiency to Explain the Thinking Behind a Playoff Coaching Adjustment

Writeup: https://matthewkjho.wordpress.com/2023/08/23/film-and-analytics-intersect-how-a-defensive-change-gave-the-warriors-an-edge-in-the-2022-nba-playoffs/

1. Scraped 450+ values from 2 data tables (playtype data for Handoffs/Off-screen) from Synergy Sports.
2. Performed Data Cleaning in Excel to remove errors, duplicates, and irrelevant data from raw datasets.
3. Imported data to Tableau and related the tables via outer join -- related by player name.
4. Deduced appropriate graph (double line) to compare proficiency between 2 players.
    * Used handoff & off-screen shooting as approximation of 'movement shooting' ability. 
5. Touched-up in Canva for user-friendliness.

![Mavs Movement Shooting](MavsMovementShooting.png)

## [Project 2: Measuring 'Connective Passing' to Explain the Success of the Sacramento Kings' Offensive System](https://github.com/yashwantsathish/Connective-Passing-Analysis/tree/main)

1. Pulled/Scraped 600+ data values from stats.nba.com API (using py_ball python wrapper) and basketball-reference.com. Extracted 'Touches' and 'Passing' data. 
2. Imported data into Python as Pandas DataFrames and cleaned to remove errors, duplicates, and irrelevant values.
3. Merged dataframes by player name using Pandas functionality.
4. Deduced that scatterplot was appropriate & used Python libraries Seaborn and Matplotlib to plot 'Assist %' against 'Time of Possession'. 
5. Used Python's NumPy library to generate and plot line of best fit -- meant to denote 'average' connective passing ability.
6. Touched-up in Canva for user-friendliness.

![Kings' Connective Passing](KingsConnectivePassing.png)

## Project 3: Finding a Measure for 'Rim Protection Ability' to Identify the Best Rim Protectors in the NBA
1. Pulled 500+ data values from stats.nba.com API (using nba_api API Client). Extracted 'defensive' data for opponent shots taken within 6 feet of the basket (rim). 
2. Structured data into Python DataFrame and cleaned to remove errors, duplicates, and irrelevant values.
3. Deduced that horizontal bar chart was appropriate & used Python Library Plotly to plot 'PCTDiff' for each player (% effect on opponent shooting % within 6 ft).

![Rim Protection](RimProtection.png)

## Project 4: Rebounding (Tableau)

## Project 5: Warriors Touches
