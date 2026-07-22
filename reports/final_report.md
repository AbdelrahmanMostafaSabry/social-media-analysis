# 📊 Social Media Impact Analysis Report

---

## Executive Summary

This report analyzes the relationship between social media usage and mental health among teenagers.

The analysis explores how factors such as daily social media usage, sleep duration, stress level, anxiety level, and platform preference relate to depression.

The project was completed using Python for data cleaning, exploratory data analysis (EDA), statistical analysis, and data visualization.

---

## Project Objective

The main objective of this project is to investigate whether social media usage is associated with mental health indicators.

The analysis focuses on the following questions:

- Does spending more time on social media relate to depression?
- Does sleep duration differ between depressed and non-depressed participants?
- Which platform is the most popular?
- Are there meaningful correlations between the variables?

---

## Dataset Overview

| Item | Value |
|------|-------|
| Number of Records | 1200 |
| Number of Features | 13 |
| Target Variable | Depression Label |

### Features

- Age
- Gender
- Daily Social Media Hours
- Platform Usage
- Sleep Hours
- Screen Time Before Sleep
- Academic Performance
- Physical Activity
- Social Interaction Level
- Stress Level
- Anxiety Level
- Addiction Level
- Depression Label
---

## Dashboard

![Dashboard](../images/dashboard.png)

# Key Findings

## 1. Age Distribution

- Participants are between **13 and 19 years old**.
- The dataset is well balanced across all age groups.
- No age group dominates the dataset.

---

## 2. Platform Usage

- Instagram has the highest number of users.
- TikTok is a close second.
- Users who use both platforms are also well represented.
- The difference between the three groups is relatively small.

---

## 3. Depression Distribution

- Most participants are labeled as **Not Depressed (0)**.
- Only a small percentage are labeled as **Depressed (1)**.
- The dataset is imbalanced, which should be considered before training any machine learning model.

---

## 4. Social Media Usage and Depression

- Participants with depression spend more hours on social media.
- The box plot shows a higher median daily usage for the depressed group.
- This suggests a positive relationship between heavy social media use and depression.

---

## 5. Sleep Hours and Depression

- Participants with depression sleep fewer hours.
- The difference between the two groups is clearly visible.
- Longer sleep duration appears to be associated with lower depression levels.

---

## 6. Platform Comparison

- Daily social media usage is similar across Instagram, TikTok, and users of both platforms.
- No platform appears to encourage significantly longer usage than the others.

---

## 7. Correlation Analysis

The strongest relationships observed were:

| Variables | Correlation |
|-----------|------------:|
| Daily Social Media Hours ↔ Depression | 0.18 |
| Stress Level ↔ Depression | 0.17 |
| Anxiety Level ↔ Depression | 0.17 |
| Sleep Hours ↔ Depression | -0.19 |

Most other relationships are weak, suggesting that depression is influenced by multiple factors rather than a single variable.

---

# Recommendations

Based on the analysis, the following recommendations can be made:

- Encourage healthier social media habits among teenagers.
- Promote better sleep routines.
- Monitor excessive daily social media usage.
- Collect more behavioral and demographic data for deeper analysis.
- Build predictive machine learning models to identify individuals at higher risk of depression.

---

# Conclusion

This project explored the relationship between social media usage and mental health using exploratory data analysis and visualization techniques.

The findings indicate that participants with depression generally spend more time on social media and sleep fewer hours than non-depressed participants.

Although the observed correlations are relatively weak, the visualizations reveal meaningful behavioral patterns that could support future predictive modeling and mental health research.