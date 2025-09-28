# MiLB-Prospects-Batting-Projections

## Overview
Trying to predict how a player will perform once they get to the big leagues have always been a question since the inception of the minor leagues in baseball. For a long time, player evaluations for the minor leagues have been more of an eye test and outdated statistics as Sabermetrics and Advanced Analytics have taught us through recent decades. I want to find out just how much of a difference traditional batting statistics (BA, OBP, SLG, OPS, etc.) differ from current advanced analytics (HardHit%, LA%, Bat Speed, etc.) when it comes to using them in creating machine learning models. In this project, I will attempt to showcase the value of having advanced analytics in StatCast data when it comes to predicting major league success for minor league players in terms of their batting performance.

## Data
* MiLB batted data (2015-2025) from [FanGraphs](https://www.fangraphs.com/leaders/minor-league?pos=all&level=1&lg=2,4,5,6,7,8,9,10,11,14,12,13,15,16,17,18,30,32&stats=bat&qual=y&type=1&team=&season=2015&seasonEnd=2025&org=&ind=0&splitTeam=true&players=&sort=20,1).
* MiLB data (2023-2025) from [StatCast](https://baseballsavant.mlb.com/statcast-search-minors).
* MLB data (2015-2025) from [StatCast](https://baseballsavant.mlb.com/leaderboard/custom?year=2025&type=batter&filter=&min=q&selections=pa%2Ck_percent%2Cbb_percent%2Cwoba%2Cxwoba%2Csweet_spot_percent%2Cbarrel_batted_rate%2Chard_hit_percent%2Cavg_best_speed%2Cavg_hyper_speed%2Cwhiff_percent%2Cswing_percent&chart=false&x=pa&y=pa&r=no&chartType=beeswarm&sort=xwoba&sortDir=desc).
* PlayerIDs from [Chadwick Bureau](https://github.com/chadwickbureau).

## TODO: File Structure

## TODO: Methodology (to be expanded upon later)
1) EDA on MiLB data
2) Initalize Fixed Values
3) Calculate wOBA, wRAA, wRC in MLB
4) Calculate Aggregate Career Stats for MLB Players
5) Map players through FanGraphID and StatCastID
6) Data Cleaning and Feature Engineering
7) Model Building
8) Model Evaluation
9) Repeat for StatCast Data

## Results

### Batting Data
![image](img/model_results.png)

### StatCast Data
![image](img/statcast_model_results.png)

## TODO: Discussion

## TODO: Limitations

## TODO: Future Work
