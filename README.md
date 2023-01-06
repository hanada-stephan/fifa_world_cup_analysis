# FIFA World Cup Analysis: Project Overview

**Tags: EDA, data visualization, soccer, FIFA**

This notebook's main steps were:

- Basic EDA;
- Calculate and plot the average scored goals by World Cup Edition;
- Average number of goals during all the World Cup editions analysis;
- Qatar 2022 World Cup average number of goals;
- Scored goals over game time analysis.

## Code and resources

Platform: Jupyter Notebook

Python version: 3.9.13

Packages: matplotlib, pandas, seaborn, and warnings

## Data set

For the World Cup score goals analysis, there are two data sets: 
- the **historic_world_cup_goals** contains the number of goals and matches of all FIFA World Cups until 2018;
- the **qatar_world_cup_goals** contains the number of goals and matches of the FIFA World Cup Qatar 2022.

Both data sets used in this notebook had all the information collected from Wikipedia and FIFA sites (for more info, check the README file in the data folder).

## Insights

- There are two distinct eras in terms of average scored goals: 1930-1958 (all the editions had above 3.5 goals/game); 1962- (all the editions had below 3 goals/game);
- The average number of goals scored by tournament day oscillates a lot in the group stage due to the low number of games, and this number tends to stabilize over time;
- The 2022 Qatar World Cup had 172 goals scored, with an average of 2.69 goals per game. Both numbers are the highest numbers in the 32-team era;
- Most of the goals in the 2022 Qatar WC were scored in the second half (59%). 
