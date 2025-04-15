# 🚧 Crash Scene Clearance Time Analysis – Denton, Texas

This project focuses on crash data in Denton, Texas, sourced from the Texas Department of Transportation (TxDOT). The main objective is to analyze the **time taken to clear accident scenes** and uncover patterns using supervised and unsupervised machine learning techniques.

---

## 📁 Dataset Overview

- **Source**: Texas Department of Transportation (TxDOT)
- **Location**: Denton, Texas
- **Time Period**: April 1, 2023 – July 31, 2024
- **Crashes**: 3,608
- **Units Involved**: 7,673
- **Persons Involved**: 9,479
- **Features**: 15 columns

> ⚠️ *Disclaimer*: All opinions and conclusions from this analysis are my own and do not represent the views of the State of Texas or the Department of Transportation.

---

## 🎯 Objective

The goal is to determine the **scene clearance time** after crashes using the following key time-related fields:
- Crash Date
- Crash Time
- Date Scene Cleared
- Time Scene Cleared

We explore trends and apply ML techniques to better understand patterns and influencing factors.

---

## 📂 Repository Structure

- Data set - Denton Accidents
- Lab1
- Lab2
- Lab3
- Lab4
- Readme.md file

---

## 🧪 Lab Summaries

### ✅ Data Exploration
- Data types, missing values
- Distribution of crash dates, times, surface conditions, weather
- Initial visuals to understand scene clearance time

### ✅ K-Means Clustering
- Grouped crash events into clusters
- Explored if patterns emerge in time/location/surface/clearance

### ✅ Classification
- Predicted crash severity using features like road class, weather, surface, etc.
- Models: KNN, Decision Tree
- Evaluated accuracy, precision, recall

### ✅ Regression
- Predicted total scene clearance time using linear regression
- Identified factors affecting time duration
