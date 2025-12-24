# Bellabeat Case Study — Smart Device Usage Analysis

## Project Overview
This case study analyzes smart fitness device usage data to understand how consumers engage with activity and sleep tracking features. The insights are used to inform potential marketing and product positioning strategies for Bellabeat.

The analysis follows the complete data analytics lifecycle (Ask, Prepare, Process, Analyze, Share, Act) as outlined in the Google Data Analytics program.

This project emphasizes analytical rigor, scope awareness, and clear communication over exhaustive modeling.

## Business Task
The objective of this analysis is to understand how consumers use smart fitness devices in their daily lives, with a focus on habitual behavior rather than performance-driven usage. These insights are intended to help Bellabeat identify opportunities for targeted marketing, product positioning, and user engagement within the global smart device market.

## Data & Limitations
The analysis uses publicly available Fitbit smart device data sourced from Kaggle. The dataset includes daily activity and sleep records from a limited sample of users over a short time period.

The data does not represent actual Bellabeat customers and is used as a proxy to understand general smart device usage behavior. Findings should be interpreted as exploratory insights rather than definitive conclusions, and may not be fully generalizable to the broader population.

These constraints informed a conservative analytical approach focused on descriptive insights rather than predictive or causal claims.

## Key Findings
Analysis of daily activity data revealed the following behavioral patterns among smart device users:

- Average daily step count was approximately 7,600 steps, with a median of around 7,400 steps.
- Users spent an average of roughly 990 minutes per day in sedentary activity.
- Average daily active time (light, moderate, and very active combined) was approximately 230 minutes.
- Activity level segmentation showed:
  - ~32% of users classified as low activity (<5,000 steps/day)
  - ~36% classified as moderate activity (5,000–10,000 steps/day)
  - ~32% classified as high activity (>10,000 steps/day)
- Moderate-activity users exhibited the lowest average sedentary time compared to low- and high-activity users.

## Analyst Notes
Several analytical paths were intentionally not pursued in this case study. While both activity and sleep data were available, sleep records were inconsistently logged across users, limiting the reliability of correlation analysis. Rather than forcing relationships that were not sufficiently supported by the data, the analysis focused on well-documented activity patterns and sedentary behavior.

This approach reflects a preference for analytical integrity and interpretability over complexity, particularly when working with proxy datasets and limited samples.

## Recommendations
Based on observed activity and sedentary behavior patterns, the following high-level recommendations are suggested for Bellabeat’s marketing and product positioning:

- Emphasize daily balance and habit formation rather than performance-oriented fitness goals, aligning with how most users engage with smart devices.
- Focus marketing efforts on moderate-activity users, who demonstrated the most balanced activity profiles and lower sedentary time.
- Address sedentary behavior explicitly across all user segments, as higher activity levels did not consistently correspond to reduced sedentary time.
- Position the Bellabeat app as a holistic wellness companion that supports sustainable routines rather than short-term intensity.

For a detailed walkthrough of the full analysis process, please take a look at the documentation in the docs/folder.
