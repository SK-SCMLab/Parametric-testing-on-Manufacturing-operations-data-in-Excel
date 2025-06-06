# 🛖 Parametric-testing-on-Manufacturing-operations-data-in-Excel
This repository contains Excel-based case study demonstrating how to apply parametric testing to real-world manufacturing operations data including:

- 1 Sample T.Test and Z.Test
- Chi-Square Hypothesis test
- 2 Sample Independent T.Test
- 2 Sample Paired T.Test
- F.Test for independent groups
- Means of Two groups - Comparison
- Analysis of Variance (ANOVA)

---

## 🏝 1 Sample T.Test & Z.Test
These tests help to determine whether a sample mean differs significantly from a known or hypothesized population mean. But they differ in when and why you use each. 

| *1 Sample Z.Test* | *1 Sample T.Test* |
|-------------------|-------------------|
| 1. Population standard deviation is known | 1. Population standard deviation is unknown |
| 2. Sample size is large (typically n≥30) | 2. Sample size is small (n<30) |
| 3. Population is normally distributed | 3. Population is assumed to be approximately normal | 
| 4. To test if the sample mean (x̄) is significantly different from a known population mean (μ), assuming σ is known | 4. To test if sample mean differs from the population mean. But the t-distribution accounts for extra uncertainty in estimating σ from the sample | 

---

## 🚌 Chi-Square Hypothesis Test (χ²)
- To test if two categorical variables are independent (e.g. gender vs. preference)
- Or to test **goodness-of-fit** - whether observed frequencies match expected ones
- To determine if there's a statistically significant association between categorical variables

---

## 🎡 Two-sample Paired T.Test
- To compare two related samples (same group before and after treatment)
- To test if the mean difference is significantly different from 0
- To evaluate if a treatment, intervention, or change has had a statistically significant effect

---

## 🗿 Two-sample Independent T.Test
- To compare two independent groups (e.g Group A vs Group B)
- The population standard deviations are unknown but assumed equal or unequal
- To test whether the means of two independent samples are significantly different

---

## 💺 F.Test for Independent Group (Equality of Variances)
- To test if two groups have equal variances
- Often used before running a T.Test to determine if equal-variance T.Test or Welch's T.Test should be used
- To compare variability between two independent samples

---

## ⛲️ Means of Groups - Comparison
- Understand the significant difference in the outcome of two process
- Understand whether a new process is better than the old process
- Understand whether two samples belong to the same population or different populations
- Benchmark the existing process with another benchmarked process

---

## ⚓️ ANOVA
- Used to compare more tha two samples
- Stands for Analysis of Variance
- Helps in understanding that all sample means are not equal
- ANOVA based significant samples can be tested further
- Generalize the T.Test to include more than two samples

---

## 🛝 Case study: Statistical Testing of Steel rod FG in Manufacturing Plant

### 🛺 Objectives
- Problem definition
- Hypothesis setup
- Statistical test
- Excel implementation
- Interpretation of results

