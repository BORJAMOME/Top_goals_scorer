<h1 align="Left">Football Player Performance Analysis</h1>
<p align="left">
  <img src="https://img.shields.io/badge/Language-R-blue" alt="Language">
  <img src="https://img.shields.io/badge/Status-Active-brightgreen" alt="Status">
</p>
<p align="left">
 
</p>

# Overview
This repository contains R code for analyzing the performance of football players over time. It utilizes data from Fbref.com to track the evolution of goals and assists per 90 minutes for select players from the 2000-2024 seasons. The analysis includes visualizations to illustrate the trends in player performance.

# Data
The data used in this analysis is sourced from Fbref.com, a comprehensive football statistics website. The dataset includes advanced season statistics for players from the top five European leagues (Big Five) from 2000 to 2024. Relevant metrics such as goals per 90 minutes (Gls_Per), assists per 90 minutes (Ast_Per), expected goals per 90 minutes (xG_Per), and expected assists per 90 minutes (xAG_Per) are considered.

# Analysis
The R code provided in this repository conducts the following analyses:

**1.Evolution of goals and assists per 90 minutes:** Visualizes the evolution of goals and assists per 90 minutes over the seasons for the selected players.

![1](https://github.com/BORJAMOME/Top_goals_scorer/assets/19588053/61eee283-001c-40f2-8b06-d85dac080d18)

**2.Percentile of goals and assists per 90 minutes:** Examines the percentile ranks of goals and assists per 90 minutes to identify player performance relative to their peers.

![2](https://github.com/BORJAMOME/Top_goals_scorer/assets/19588053/fdc4433c-43cd-47f2-957b-0c467d33dac6)

**3.Expected Goals and Assists per 90 minutes each season:** Analyzes the expected goals and assists per 90 minutes for each season, providing insights into player performance beyond actual statistics.

![3](https://github.com/BORJAMOME/Top_goals_scorer/assets/19588053/3f61fe72-b470-4184-9167-72a1dc60769b)

**4.Expected goals and goals scored per 90 minutes each season:** Compares expected goals with actual goals scored per 90 minutes to evaluate player effectiveness.

![4](https://github.com/BORJAMOME/Top_goals_scorer/assets/19588053/8b40d4b1-1680-422f-820e-ca0b7c78856e)

# Dependencies
The R code relies on several R packages, including CDR, tidyverse, janitor, ggbeeswarm, here, patchwork, ggtext, ggrepel, worldfootballR, and showtext. Ensure these packages are installed before running the code.



# Author
This project is maintained by Borja Mora.

