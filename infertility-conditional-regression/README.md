# 🩺 Predicting Infertility with Conditional Logistic Regression

📊 Recreating and adapting a published miscarriage risk-factor study using R and matched case-control data.

## 🎯 Project Overview

This project investigates how previous induced abortions and spontaneous abortions (miscarriages) are associated with infertility using the built-in `Infert` dataset in R.

Inspired by *Predictors of Miscarriage: A Matched Case-Control Study* by Jalal Poorolajal et al., we compare logistic regression approaches to understand the importance of accounting for matched data.

## ❓ Research Question

How do previous miscarriages and abortions affect the odds of infertility in women?

## 🛠️ Methods & Tools

- **Language:** R
- **Dataset:** `Infert` (built-in R dataset)
- Ordinary Logistic Regression
- Logistic Regression with Stratum Fixed Effects
- Conditional Logistic Regression
- Model Comparison Using AIC and BIC
- Odds Ratios and 95% Confidence Intervals

## 💡 Key Findings

- 🔬 **Induced abortion:** 4.1× greater odds of infertility.
- 🩺 **Spontaneous abortion (miscarriage):** 7.3× greater odds of infertility.
- 📈 Conditional logistic regression accounts for the matched case-control design by comparing women within matched sets.

**95% Confidence Intervals**
- Induced abortion: (2.018, 8.298)
- Spontaneous abortion: (3.651, 14.536)

## 📌 Conclusion

Conditional logistic regression is useful for matched case-control studies because it accounts for the matched structure and focuses on within-stratum comparisons. In this analysis, previous induced and spontaneous abortions were associated with higher odds of infertility.

*These results describe associations in the analyzed dataset and do not establish causation.*

## 👥 Authors

Fiona Vo · **Srinidhi Muralidharan** · Zayna Badr

---
*An academic project in statistical modeling, women's health, and regression analysis.* 📈
