Got it 👍 — here’s a **simplified, clean README.md** version with only the essential details and no tables:

---

# 🦇🐀 Bat vs Rat: The Forage Files

### HIT140 – Foundations of Data Science (Assessment 3)

## 📘 Project Overview

This repository contains the Python scripts and datasets for our HIT140 Assessment 3 group project titled **“Bat vs Rat: The Forage Files.”**
The project investigates nocturnal foraging interactions between **Egyptian fruit bats** and **black rats** sharing a food platform in Northern Australia.
It aims to understand whether bats perceive rats as competitors or predators and how rat activity changes with season, time, and food availability.

---

## 🎯 Objectives

The project is divided into two main investigations:

* **Investigation A:** Analyse bat foraging behaviour and vigilance in the presence of rats.
* **Investigation B:** Examine rat activity across different seasons and times after sunset.

---

## 📊 Datasets

Two datasets were used:

* **Dataset 1:** Records of 907 bat landings, including timing, vigilance, risk-taking, and feeding success.
* **Dataset 2:** Records of 2,123 rat observation intervals, including arrival frequency, duration, and food availability.

Both datasets were collected through motion-activated cameras monitoring a shared feeding site.

---

## 🧠 Tools & Libraries

All analysis was conducted using Python with libraries including:

* pandas
* matplotlib
* seaborn
* scipy.stats
* scikit-learn

---

## 🔎 Analysis Summary

### Investigation A – Bat Behavioural Response

Data was cleaned and processed to create features such as vigilance proxy and rat presence flag.
Descriptive and inferential analyses (Mann–Whitney U and Chi-Square tests) showed that bats maintained stable vigilance, risk-taking, and feeding success regardless of rat presence.
A regression model confirmed that bat behaviour was mostly influenced by internal factors rather than by rats.
**Conclusion:** Bats treat rats as neutral co-foragers, not threats.

### Investigation B – Rat Seasonal and Temporal Patterns

Rat data was cleaned and mapped to seasonal categories.
Descriptive analysis showed that rat activity peaked in autumn and declined in winter.
Regression and correlation analysis revealed that seasonal conditions and food availability had the greatest influence on activity levels.
**Conclusion:** Rat foraging is shaped by environmental conditions, not bat presence.

---

## 📈 Key Findings

* Bats and rats coexist peacefully at the feeding site.
* Rat activity follows seasonal cycles, while bat behaviour remains stable.
* Environmental factors such as temperature and food availability are stronger drivers than interspecies competition.
* Both species demonstrate adaptive nocturnal behaviour and efficient resource sharing.

---

## 👥 Team Contributions

* **Aman:** Data cleaning and feature engineering
* **Deepak:** Descriptive analysis and visualisation
* **Yashwanth:** Statistical testing and interpretation
* **Rahul:** Regression modelling and report compilation

---

Would you like me to create this as a downloadable **README.md** file for GitHub?
