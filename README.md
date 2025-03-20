PRESENTATION LINK
(https://docs.google.com/presentation/d/1ZuTlFUI3WVkuOO3rLTGtmfgRA-Nwul6H-GjnuLe9dbQ/edit?usp=sharing)
# PROJECT-4
# Analyzing the Impact of Gel States and Temperature Variations on ATP Concentration

## Background
The dataset originates from an experimental setup designed to measure ATP concentration under various conditions involving incubation times, gel states, and environmental factors (e.g., temperature). This dataset provides a controlled environment to study the effects of these variables on ATP levels across different samples.

## Objectives
1. To explore the relationship between incubation conditions and ATP concentration.

2. To identify patterns in ATP levels under varying gel states (e.g., Live-Gel, Dead-Gel, Gel-Only).

3. To engineer features that can be used for deeper insights.

4. To determine the significance of temperature and gel states on ATP concentration levels.

## Research Questions
a. **How do temperature conditions (incubator vs. 23ºC) influence ATP concentrations in gel samples?**

b. **What is the relationship between incubation time and ATP levels across various gel states?**

c. **Do Live-Gel samples exhibit significantly different ATP levels compared to other gel states?**

d. **What insights can be gained from engineered features like ratios and log-transformed variables?**

e. **Are there any observable patterns or anomalies in ATP concentrations within the experimental setup?**

## Data Description
The dataset used in this analysis is sourced from the ***Data.gov*** website. It contains experimental records measuring ATP concentration under various conditions, including incubation times, gel states, and environmental factors like temperature. Key features include Metric, Sample, Incubation_Time, Unnamed_3, Unnamed_4, Unnamed_5, Live_Gel_Incubator, and Live_Gel_23C. These variables capture measurements for live gel samples and provide insights into how ATP levels vary under different experimental setups.

## Methodology
The analysis wil involve the following key steps:
1. **Exploratory Data Analysis (EDA):** Visualize data distributions, including ATP concentrations under various conditions. Examine correlations between incubation time, gel states, and temperature effects. Handle missing values and standardize numeric features.

2. **Feature Engineering:** Calculate ratios (e.g., Live_Gel_Ratio) and other derived metrics for deeper insights. Apply log transformations to handle skewness in numeric variables.

## Significance
Provides insights into how environmental conditions like temperature and incubation affect ATP concentrations, potentially informing laboratory protocols or experimental designs. Helps identify optimal experimental settings for future studies focusing on gel states and cellular health.
## Summary of Key Findings
1. **ATP Concentration Trends:** The analysis revealed noticeable variations in ATP concentrations under different gel states (e.g., Live-Gel, Dead-Gel) and temperature conditions (incubator vs. 23ºC).

2. **Effect of Temperature:** Samples measured at 23ºC showed consistent patterns, with notable differences compared to incubator measurements, especially for Live-Gel samples.

3. **Feature Ratios:** Derived metrics, like Live_Gel_Ratio, provided deeper insights into the relative changes in ATP levels across experimental setups.

4. **Log Transformations:** Applying log transformations to variables like Live_Gel_Incubator reduced skewness, enabling better representation of the data for analysis

## Implications
The findings can guide experimental designs by highlighting the significance of temperature and gel states on metabolic activity, as reflected by ATP concentrations. Understanding these patterns may help researchers optimize incubation conditions for experiments that require precise metabolic measurements. The generated features, such as ratios and log-transformed variables, can serve as predictors in future modeling efforts, potentially improving accuracy.

## Limitations
Missing and placeholder values (e.g., Unnamed_3, Unnamed_4) may limit the completeness of the analysis. The dataset is focused on specific experimental conditions and may not generalize to broader biological contexts or other environments.

## Future Work
Include more samples and experimental conditions to generalize findings.

Use engineered features to build machine learning models predicting ATP concentrations under new conditions.

Develop metrics tailored to specific biological or experimental goals, such as energy efficiency indicators.

Conduct hypothesis testing to evaluate the significance of differences between conditions.
References
https://catalog.data.gov/dataset?q=medical+engineering
