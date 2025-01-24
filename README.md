# 🏀 NBA Attendance Forecasting

This repository contains the analysis and forecasting model for predicting NBA home game attendance during the 2018/2019 season. The project involves cleaning and analyzing historical data, building a forecasting model, and presenting insights.

## Table of Contents
- [Problem Statement](#problem-statement)
- [Data Description](#data-description)
- [Project Workflow](#project-workflow)
- [Setup Instructions](#setup-instructions)



## Problem Statement
In the 2018/2019 NBA season, LA Clippers team hosted 41 home games. Attendance, influenced by numerous factors such as team performance, day of the week, and weather, is critical for pricing decisions. The goal is to:
1. Analyze historical attendance data.
2. Build a model to forecast attendance before the season starts.
3. Provide actionable insights to guide ticket pricing.

## Data Description
The dataset includes:
- **Game Date:** Date of the game
- **Opponent:** Opponent team
- **Day of the Week:** Day the game is played
- **Historical Attendance:** Attendance for previous games
- **Weather:** Game day weather
- **Team Performance Metrics:** Team's record, win/loss streak, etc.

Refer to the `dataset/` folder for details.

## Project Workflow
1. **Data Cleaning:** Handling missing values, outliers, and formatting.
2. **EDA:** Exploring trends, correlations, and attendance influencers.
3. **Modeling:** Building regression and time-series models for attendance forecasting.
4. **Insights & Recommendations:** Summarizing findings for pricing decisions.

## Setup Instructions

### Clone the Repository
```bash
git clone https://github.com/your-username/nba-attendance-forecasting.git
cd nba-attendance-forecasting
