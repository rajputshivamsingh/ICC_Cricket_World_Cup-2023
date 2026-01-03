# ICC Cricket World Cup 2023 – Data Analysis Project

Project Overview
This project analyzes the ICC Cricket World Cup 2023 using Python and data analysis techniques to uncover insights into team performance, player contributions, and match-winning factors.

The goal is to understand how batting, bowling, and team strategies influenced match outcomes during the tournament.

Technologies Used
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

Datasets Used
1. **batting_summary.csv** – Match-wise batting statistics  
2. **bowling_summary.csv** – Match-wise bowling statistics  
3. **match_schedule_result.csv** – Match results and details  
4. **world_cup_players_info.csv** – Player metadata  

Data Processing Steps
- Cleaned column names and removed extra spaces
- Standardized player names for accurate merging
- Merged datasets using match and player identifiers
- Created derived columns such as:
  - Result (Winning / Losing)
  - Win_Type (Chasing / Defending)
- Handled missing values using appropriate methods

Key Analyses Performed

Batting Performance
- Average runs in winning vs losing matches
- Winning teams showed higher batting contributions

Bowling Performance
- Average wickets in winning vs losing matches
- Strong bowling correlated with match victories

Team Strategy
- Chasing vs defending performance analysis
- Teams showed distinct strategic strengths

Overall Team Performance
- Combined wins, total runs, and total wickets
- Identified consistently strong teams

Team Strength
- Average runs and wickets per match
- Balanced teams performed better across the tournament

Visualizations
- Bar charts for batting and bowling impact
- Team-wise performance comparisons
- Strategy-based performance analysis

Key Insights
- Batting and bowling both significantly affect match outcomes
- Winning teams outperform losing teams in runs and wickets
- Team strategies vary and influence success
- Data-driven analysis provides clear performance patterns

Conclusion
This project highlights the power of data analytics in sports. By combining match-level and player-level data, meaningful insights were derived that explain team success and tournament dynamics.
