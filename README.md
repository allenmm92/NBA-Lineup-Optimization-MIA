# NBA Lineup Optimization Project

**Blending Basketball Expertise with Data Science**  
As a former player, coach, and trainer with 20+ years of basketball experience, I leverage statistical analysis to evaluate NBA lineups and uncover patterns that maximize team performance.  
This project demonstrates how data-driven insights can inform coaching decisions and player development by ranking lineups based on key performance metrics.

## Overview
This project analyzes NBA 5-man lineups and identifies the best overall lineups based on three key performance metrics:

- **Points per Game (PTS)**
- **Effective Field Goal Percentage (eFG%)**
- **Rebound Percentage (REB%)**

Each lineup is ranked in these categories, and the ranks are summed to create a **Combined Rank** score.  
The lower the Combined Rank, the better the lineup performs across all three metrics.

## Objective
The goal of this project is to provide a data-driven method to evaluate and compare NBA lineups, helping coaches, analysts, or basketball operations staff identify the most effective lineup combinations.

## Methodology
1. **Data Collection**: NBA lineup statistics were collected from [Basketball Reference](https://www.basketball-reference.com/).  
2. **Data Cleaning**: Raw data was converted into CSV format and cleaned for consistency.  
3. **Ranking**: Each lineup was ranked in PTS, eFG%, and REB%.  
4. **Combined Score**: Ranks were summed to produce a Combined Rank score for each lineup.  
5. **Visualization**: Results are visualized using a horizontal bar chart to highlight top-performing lineups.  
6. **Top Lineups**: The script outputs the top 5 lineups by Combined Rank.

## Tools Used
- **Python**: pandas for data manipulation, matplotlib for visualization  
- **Data Source**: Basketball Reference

## How to Run
1. Upload the `lineups.csv` file (downloaded from Basketball Reference) to the notebook.  
2. Run the notebook cells sequentially.  
3. The notebook outputs:
   - The top 5 lineups based on Combined Rank
   - A full table of all lineups ranked
   - A bar chart visualization of Combined Rank

## Insights
- This ranking method balances scoring, shooting efficiency, and rebounding to identify lineups that perform well across multiple aspects of the game.  
- Provides a simple, reproducible way to analyze lineup efficiency without relying on proprietary APIs.
