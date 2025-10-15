# HIT-140-Assessment-3-Group-75-
🦇🐀 Bat vs Rat: The Forage Files
HIT140 – Foundations of Data Science (Assessment 3)
📘 Project Overview

This repository contains the complete Python implementation and datasets for HIT140 Assessment 3 – Group Project: Bat vs Rat: The Forage Files.
The study investigates nocturnal feeding interactions between Egyptian fruit bats (Rousettus aegyptiacus) and black rats (Rattus rattus) that share a provisioned food platform in Northern Australia.

The analysis explores two complementary investigations:

Investigation A: Do bats perceive rats as predators or competitors?

Investigation B: How does rat activity vary with season, time, and food availability?

Using Python-based data science techniques, the project applies data wrangling, descriptive and inferential statistics, and regression modelling to understand behavioural coexistence patterns.

🎯 Objectives
Investigation	Focus	Main Question
A	Bat Behavioural Response	Do bats alter vigilance, risk-taking, or foraging success in the presence of rats?
B	Rat Seasonal & Temporal Activity	How do environmental factors (season, time after sunset, food availability) influence rat foraging?
📊 Datasets
Dataset	Description	Records	Key Variables
dataset1.csv	Individual bat landings and behaviour relative to rat presence.	907	start_time, risk, reward, vigilance_proxy, season, hours_after_sunset
dataset2.csv	Rat arrivals in 30-minute intervals and environmental context.	2,123	rat_minutes, rat_arrival_number, food_availability, hours_after_sunset, season, bat_landing_number

Both datasets originate from motion-activated observations of shared feeding events.

🧠 Tools & Libraries

All analysis and visualisation were performed in Python using:

pandas – data cleaning and preprocessing

matplotlib / seaborn – visualisations

scipy.stats – statistical testing (Mann–Whitney U, Chi-Square, ANOVA)

scikit-learn – linear regression modelling

🔎 Analysis Workflow
Investigation A – Bat Behavioural Response

Data Cleaning & Feature Engineering:

Converted and standardised datetime formats.

Created vigilance_proxy and rats_present_at_landing variables.

Descriptive Analysis:

Balanced risk-taking vs avoidance.

Feeding success unaffected by rat presence.

Vigilance duration stable across all seasons.

Inferential Tests:

Mann–Whitney U and Chi-Square tests found no significant differences.

Regression Modelling:

Linear regression (R² = 0.034) showed that vigilance is influenced more by behavioural traits (risk, reward) than by rat presence.

🧩 Key Insight:

Bats perceive rats as neutral co-foragers, not threats or competitors.

Investigation B – Rat Seasonal and Temporal Patterns

Data Preparation: Cleaned and mapped months to Australian seasons (Dec–Jun).

Descriptive Analysis: Identified peak activity during Autumn and decline in Winter.

Inferential Analysis:

One-way ANOVA (F = 2.21, p = 0.112) showed no significant seasonal mean difference.

Correlation (r = 0.82) between rat_minutes and rat_arrival_number.

Regression Model:

Multiple Linear Regression (R² = 0.375, MAE = 0.442).

Rat activity primarily influenced by season, hours_after_sunset, and food availability.

🧩 Key Insight:

Rat activity follows environmental cycles, with minimal behavioural interference from bats.

📈 Summary of Findings

Coexistence: Bats and rats forage simultaneously with no competitive exclusion.

Temporal Adaptation: Both species show consistent nocturnal feeding patterns.

Environmental Influence: Seasonal decline in rat activity due to cooler temperatures and reduced food.

Behavioural Stability: Bats maintain vigilance regardless of rat presence.
