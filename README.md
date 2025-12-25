# Sleep Efficiency & Health Analysis 💤

This project involves the detailed statistical analysis and visualization of sleep patterns, efficiency, and the impact of lifestyle habits (smoking, alcohol, caffeine) on sleep quality, based on the "Krizantem" dataset.

## 👥 Project Author
* **Ferhat ARSLAN**

## 📊 Project Summary
Using a dataset comprising 450 subjects, this study examines the relationship between physiological characteristics (Age, Gender) and sleep stages (REM, Deep, Light). The project specifically focuses on how behavioral changes, such as smoking cessation, affect sleep duration.

The objectives of this study are:
* To analyze the impact of lifestyle choices (smoking, alcohol) on sleep efficiency,
* To investigate the correlation between age and deep sleep percentages,
* To determine if gender plays a significant role in sleep architecture (Light vs. Deep sleep).

## 🛠️ Technologies and Libraries Used
The project was prepared in **Quarto** format using the **R** programming language.

* **Data Processing:** `tidyverse`, `readxl`, `dplyr`, `dlookr`
* **Visualization:** `ggplot2`, `ggpubr`, `skimr`
* **Reporting:** `knitr`, `kableExtra`, `flextable`
* **Statistical Analysis:** `stats` (t-test, ANOVA, Shapiro-Wilk)

## 🔎 Key Findings

1. **Smoking Impact:** A Paired T-Test analysis revealed a statistically significant increase in **sleep duration** after subjects quit smoking (comparing 2022 vs. 2023 data).
2. **Age Correlation:** A strong relationship was observed between **Age** and **Deep Sleep Percentage**, suggesting that sleep depth changes as individuals age.
3. **Gender Differences:** ANOVA results indicated that **Light Sleep Percentage** varies significantly between male and female subjects.
4. **Sleep Distribution:** Normality tests (Shapiro-Wilk) showed that REM sleep percentages do not follow a normal distribution across the population.

## 📂 Setup and Execution

To run this project on your own computer:

1. Clone this repository:
```bash
   git clone https://github.com/ferhatarslan/Sleep-Efficiency-Health-Analysis.git
