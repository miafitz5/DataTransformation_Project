
# Caitlin Clark Career Stat. Insights

**Authors:** Mia Fitzgerald & Angela McMahon  
**Date:** 4/8/2026

## Project Overview
This project analyzes Caitlin Clark’s complete college basketball career at the University of Iowa (2020-2024), using a comprehensive game log to explore her performance and impact on the team. The analysis covers 139 games, examining scoring, shooting, assists, rebounds, and more.

## Data Source
The data was sourced from [sports-reference.com](https://www.sports-reference.com/cbb/players/caitlin-clark-1/gamelog/), converted to CSV, and cleaned for analysis in R. Adjustments included renaming columns, handling missing values, and splitting complex columns (e.g., separating game results and scores).

## Data Preparation
- Imported the CSV into R and tidied columns for compatibility.
- Recoded variables (e.g., 'Away' and 'Games Started' as Yes/No).
- Split the 'Result' column into 'Result' (W/L) and 'Points' (score).
- Addressed missing values and merged columns as needed.

## Key Analyses & Visualizations
- **Three-Point Shooting:** Identified games where Clark shot over 60% from three, noting increased consistency in later seasons.
- **Assists:** Compared home vs. away assists, finding higher averages in away games. Highlighted games with 12+ assists, all resulting in wins.
- **High-Scoring Games:** Tracked games where Clark scored over 40 points, especially frequent in her later seasons.
- **Rebounds:** Compared offensive and defensive rebound distributions, finding defensive rebounds were higher and more variable.
- **Turnovers:** Summarized games with 0 or 1 turnover, including field goal percentage and results.
- **Game Types & Timing:** Analyzed game frequency by month and day of week, showing more games in winter and on weekends, with playoff games highlighted.
- **Season Trends:** Visualized the number of games played per season, showing a gradual increase over her career.

## Main Findings
- Clark’s offensive efficiency and contributions increased each season.
- She became a more consistent and prolific scorer and playmaker, especially in her last two years.
- High assist games strongly correlated with team wins.
- Defensive rebounding was a key strength, while offensive rebounds were less frequent.
- Most games and wins occurred on weekends, with a concentration of games in winter and March Madness.

## How to Reproduce
1. Download the [CC_career_stats.csv](CC_career_stats.csv) file.
2. Open `DataTransformation_Project.Rmd` in RStudio.
3. Knit the R Markdown file to generate the HTML report.

## Credits
Collaboration with Angela McMahon.
Data: [sports-reference.com](https://www.sports-reference.com/cbb/players/caitlin-clark-1/gamelog/)
