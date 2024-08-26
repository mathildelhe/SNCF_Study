# SNCF_Study - Data Analysis with Python - Jupyter Notebooks
This repository contains the notebooks I created as part of my Data Analysis course with CareerFoundry.

I chose to work on open data from SNCF because I'm interested in the topic of public transportation, and I wanted to verify if the usual complaints from French people about the SNCF always being late would be justified by a data analysis.

I focused this study on the TGV (high speed trains) data, and left the TER (regional trains) out of the scope of this analysis.

These notebooks contain my data preparation steps, consistency checks, derivation of variables, exploration of relationships between variables, grouping and aggregating for geographical analysis, linear regression, cluster analysis and time series analysis that I performed to get insights about the railway traffic in France.

## Objectives
Find out how efficient the French railway system is, and if some regions or specific train stations do better than others. Highlighting the areas that generate the less delays can pave the path to further investigation, in which we could study how the most efficient stations/regions are administrated, to learn from them and implement their methods nationwide.

Uncover relationships between variables and find out which ones inflence the occurence of delays/cancellations.

## Key questions

● What is the top 3 most punctual train stations in France? The 3 least punctual ones?

● Is the average delay greater in some regions than in others?

● Do train stations that receive a lot of visitors have tendency to have more delay on departure/arrival?

● Are trains leaving Paris more often delayed/cancelled than trains going to Paris? Than trains going from province to province?

● What are the train stations that received the most travelers in 2023 (including, and then excluding Paris) Are they the same as in 2015? 

● What is the proportion of trains delayed over 60 minutes in each region? 

● What was the impact of the 2020 pandemic on the French rail traffic?

## Data sets used
● [Information about delays and cancellations on each TGV line, 2018-2024](https://ressources.data.sncf.com/explore/dataset/regularite-mensuelle-tgv-aqst/information/?sort=date)

● [Number of passengers per year in each station, 2015-2023](https://ressources.data.sncf.com/explore/dataset/frequentation-gares/information/?disjunctive.nom_gare&disjunctive.code_postal)

● [Train stations in France (GeoJSON)](https://ressources.data.sncf.com/explore/dataset/gares-de-voyageurs/information/?disjunctive.segment_drg)

● French regions (GeoJSON)
