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
- Steel rod length validation (SD is known)
- Packinging fill weight suspicion (SD is unknown)
- 
---

### 🛟 Interpretation

1. *Situation: On the shop floor, the planning manager at the Hot Rolling division recently changed the Slitting machine to improve the parting (cut along the length) process of output steel sheet. To understand the quality of the machine on parting, the team has taken the 75 data points. Subsequently, the manager decided to consider the population for analysis taking sample of 50 data points.*

    **Inference**: *One sample Z.Test* || From the excel analysis, p-value ~ 0, it means the probability of observing such an extreme result (or more extreme) under the null Hypothesis (H₀) is extremely low - so low that is effectively 0. You have a very strong evidence                                           against H₀

    **Conclusion**: - Reject H₀ at any common significance level
                    - The selected sample provides overwhelming evidence that the true population parameter is not equal to the null hypothesis value


3. *Situation: At the warehouse, the Inbound inventory manager suspects that there's a packaging fill weight has drifted from the target of 250 gm of paper. Ideally, identical steel rods possess same weight, if there's any deviation in the packaging weight, then the root cause lies in the machine through which the steel rod has passed finally. In steel manufacturing plant, it is packaging machine. Now, the manager wants to audit the machine accuracy but he is not sure about the population standard deviation.*

    **Inference**: *One sample T.Test* || From the excel analysis, p-value ~ 0, it means the probability of observing sample result (or more extreme) assuming the null hypothesis (H₀) is true.

    **Conclusion**: - Reject H₀ as we have extremely low p-value i.e., we have overwhelming evidence against H₀
                    - The result is statistically significant
                    - There is an extremely strong difference between the groups (or treatment effect)
   
