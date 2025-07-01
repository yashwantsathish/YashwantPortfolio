# Yashwant Sathish Kumar – Software/Data Analysis Portfolio

Hi, I'm Yashwant! I'm a Computer Science graduate from Cal Poly SLO with an immense passion for software engineering and data analytics. I've combined this with my love for NBA basketball to develop several analytics-driven projects that aim to improve game strategy and roster construction. This repository showcases my technical skillset and project evolution across data visualization, statistical modeling, and full-stack development.

---

## Project 1: Cal Poly MBB: Coaching Analytics Web Applications

1. [Scrimmage Tracking Analysis App](https://258pb5-yashwant-sathish.shinyapps.io/CalPolySpringStatting/) 
- Built a custom R Shiny app to visualize and analyze player performance during Cal Poly Men's Basketball spring scrimmages using shot tracking and possession-level data.
- Developed an automated pipeline pulling raw stats from spreadsheets into R using `googlesheets4`, then cleaned and transformed the data with `dplyr` and `tidyr` for accurate, real-time reporting.  
- Key tabs include opportunity breakdowns by game, percent correct execution, and 1v1 situation success rates -- optimized for use on laptop, tablet, and phone.
- Streamlined staff workflows by automating visual summaries and trend identification, used in 1v1 coaching sessions with players and presented to team daily in practice.

2. [Cognitive Tracking Application](https://258pb5-yashwant-sathish.shinyapps.io/CalPolyMBBCognitiveTracking/)
- Built a fully automated pipeline from Google Sheets (coach-tagged cognitive reads) into a polished R Shiny app using `googlesheets4`, `dplyr`, and `tidyr` for real-time data ingestion and cleaning.  
- Designed dynamic filters by player, drill type, and decision category to support fast, scenario-specific cognitive review.  
- Created responsive visualizations and interactive tables with `reactable`, `plotly`, and `shinyWidgets`: accessible across tablets, laptops, and phones.  
- Enabled coaching staff to move from raw inputs to clear, actionable insights within minutes—streamlining film sessions, practice prep, and individualized feedback.

3. [Lineup Tracking Application](https://258pb5-yashwant-sathish.shinyapps.io/lineup_tracking_app/)
- Developed an R Shiny app to analyze player lineup combinations and group performance during practices and scrimmages.
- Supports flexible data input: coaches can log lineup data via a connected Google Sheet or enter it directly through the app’s built-in form interface.
- Performs dynamic computations on the fly—automatically calculating points scored/allowed, possessions, efficiency, and on/off metrics for every unique lineup.
- Uses `dplyr`, `tidyr`, and `reactable` to transform raw logs into sortable, filterable tables that help coaches assess chemistry, impact, and rotational strength in real time.

---

## Project 2: Calgary Surge: Coaching Analytics Web Applications

1. [Cut Slide Reporting App](https://yashwantsathish.shinyapps.io/SurgeCutSlideReport/)
- Built a Shiny app to analyze execution of the “cut slide” spacing concept, categorizing opportunities as either “push” (corner cuts + wing drift) or “dive” (wing dive + corner fill).
- Implemented an automated analytics pipeline: ingesting self-tagged play-by-play data from Hudl Sportscode, cleaning it in R, and computing execution rates and opportunity frequency by game and overall.
- Dynamically breaks down cut slide performance by game, situation type, and execution correctness, enabling coaches to quickly spot spacing issues or successes.
- Delivered an interactive dashboard, transforming data into interpretable visuals and statistics. Used in film sessions and team meetings to reinforce spacing discipline and concept alignment.

3. [Possession Analysis Reporting App](https://yashwantsathish.shinyapps.io/SurgePossessionAnalysis/)
- Designed and built an R Shiny app to analyze possession margin and points per 100 possessions (offensive efficiency) across 12 CEBL games.
- Personally tagged each possession in Sportscode, exported raw data to Google Sheets, and automated ingestion into R using `googlesheets4`, `dplyr`, and `janitor`.
- Computed game-level metrics dynamically—efficiency differential, possession differential, and win/loss alignment—and visualized them using `plotly` bar charts and interpretation zones (Green, Yellow, Red).
- Created an interactive, auto-updating dashboard that I presented in Coaches' meeting: allowed coaches to adjust gameplan based on which game contexts lead to winning outcomes.
    
---

## [Project 2: NBA Draft Hub – Scouting Application for NBA Front Office Decision Makers](https://github.com/yashwantsathish/Mavs-Draft-Hub)

**Live Demo:** [Mavs Draft Hub](https://mavsdrafthub-yash.netlify.app/)  
1. Developed a fully responsive, data-driven scouting interface using React (Vite) and Material UI, inspired by real front office workflows.
2. Implemented an interactive Big Board sortable by individual scouts or average rank, with color-coded indicators to highlight divergent opinions across scouts.
3. Created intuitive Player Profile views featuring toggles for counting, scoring, and total stats—minimizing cognitive load while offering flexible detail.
4. Leveraged JSON-driven architecture and React hooks to support scalable draft classes and in-browser scouting note submissions.
5. Designed with Mavericks branding, real-time UX feedback loops, and device compatibility to simulate realistic team tool adoption.

![Mavs Draft Hub](MavsDraftHubSS.png)

---

## [Project 3: Defensive Efficiency – A Multi-Season Analysis of Key Predictors](https://github.com/yashwantsathish/Defensive-Factors-Analysis)

1. Conducted a regression analysis across 5 NBA seasons (2020–21 to 2024–25) to determine which defensive stats most strongly affect Defensive Rating. Helped Cal Poly Coaching Staff develop defensive system accordingly.
2. Used `hoopR` to scrape NBA Stats API for advanced and opponent data, engineered metrics like Opponent eFG%, Turnover %, and FT Rate.  
3. Built a multiple regression model with season fixed effects and standardized coefficients to compare impact.  
4. Visualized findings using `ggplot2` to clearly communicate results to coaches — emphasizing shot quality and turnovers as the top defensive levers.  
5. Developed a polished Quarto report and final visualization for basketball ops presentation.  

![Defensive Efficiency](DefensiveFactors.png)

---

## [Project 4: Analyzing Movement Shooting Proficiency to Explain the Thinking Behind a Playoff Coaching Adjustment](https://matthewkjho.wordpress.com/2023/08/23/film-and-analytics-intersect-how-a-defensive-change-gave-the-warriors-an-edge-in-the-2022-nba-playoffs/)

1. Scraped 450+ values from Synergy playtype tables (handoffs/off-screen) and cleaned in Excel.  
2. Built a Tableau dashboard using joined tables to compare player movement shooting.  
3. Visualized with a double-line chart to support a coaching decision narrative.  
4. Touched-up in Canva for clarity and presentation.

![Mavs Movement Shooting](MavsMovementShooting.png)

---

## [Project 5: Measuring 'Connective Passing' to Explain the Success of the Sacramento Kings' Offensive System](https://github.com/yashwantsathish/Connective-Passing-Analysis/tree/main)

1. Scraped 600+ values from stats.nba.com and Basketball Reference.  
2. Merged touch and passing data using Pandas, cleaned and filtered the dataset.  
3. Visualized the relationship between Assist % and Time of Possession using Seaborn and Matplotlib.  
4. Used NumPy to fit and plot a regression line denoting 'average' connective passing.  
5. Final visual polished in Canva.

![Kings' Connective Passing](KingsConnectivePassing.png)

---

## [Project 6: Finding a Measure for 'Rim Protection Ability'](https://github.com/yashwantsathish/Rim-Defense-Analysis)

1. Pulled 500+ shot defense values from the NBA API (shots within 6 feet).  
2. Cleaned and structured data using Pandas.  
3. Graphed player impact on FG% at the rim using Plotly horizontal bar charts.  
4. Built to assist front offices in identifying hidden defensive value.

![Rim Protection](RimProtection.png)

---

## [Project 7: Identifying the Best & Most Well-Rounded Guard Rebounders](https://github.com/yashwantsathish/Guard-Rebounding-Analysis)

1. Scraped rebounding stats from Basketball Reference and cleaned in Excel.  
2. Imported to Python, visualized OREB% vs DREB% using Seaborn and Matplotlib.  
3. Created a custom bounding box using 85th percentile thresholds to highlight elite rebounders.  

![Rebounding](Rebounding.png)

---

## Project 8: Measuring Offensive 'Involvedness' Across a Roster

**Twitter Writeup:** [See thread](https://twitter.com/Mathketball1/status/1558086524297654272)  
1. Pulled roster-level touch data via NBA API into Excel.  
2. Filtered for players with 20+ touches and aggregated by team.  
3. Built visual in Tableau to illustrate the benefits of distributed offensive involvement in Golden State’s motion offense.  
4. Canva used for finishing touches.

![WarriorsTouches](WarriorsTouches.jpeg)
