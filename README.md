# Top 10 MLB Hitters in 2024

## Overview
Pulled MLB hitting statistics and visualized the top 10 hitters based on key metrics. Designed a clean bar chart for comparison.

## Tools & Technologies
- Python
- pandas, matplotlib
Data Source: MLB Stats API

## Project Structure
- Jupyter notebook with data wrangling and visualization
- Bar chart output

## Problem Statement
Who were the top 10 hitters last season based on advanced offensive metrics?

## Methodology
- Pulled full player-season dataset
- Filtered based on PA > X to remove small sample sizes
- Sorted by batting average
- Created bar chart to compare players

## Results
- Identified top 10 hitters with high offensive impact
- Visualized with clear, labeled bar chart

## Sample Output
![download](https://github.com/user-attachments/assets/fd963e44-f8ba-43d8-873f-7289d07b54a7)


## Future Improvements
- Add percentile ranks: show how top 10 hitters compare to league average
- Include defensive value: combine with defensive stats like DRS or UZR to create an overall value ranking
- Use interactive visuals: build interactive charts with Plotly for users to filter by team, stat, or position
- Add historical comparisons: see how the top 10 of this season compare with past seasons
