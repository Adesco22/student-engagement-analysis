# 📄 Summary of Findings – Student Engagement Data Analysis

## Overview

This analysis explores student engagement on a learning platform between 2021 and 2022 using metrics such as minutes watched. The data was split by plan type (free vs paid) and location (US, India, etc.).

---

## Task Highlights

### 🧮 Descriptive Statistics
- **Mean & Median (Free Plan)**: Slight increase in 2022.
- **Standard Deviation (Free & Paid)**: Remained high, indicating spread in engagement.
<embed src="./images/summary_statistics_1.pdf" type="application/pdf" width="600" height="400">
[View PDF](./images/summary_statistics_1.pdf)


---

### 📊 Paid vs Free Plan Engagement
- **Hypothesis**: Paid users watch more content than free users.
- **T-test result**: 
  - **t-statistic** = large positive
  - **p-value < 0.05**
- ✅ **Conclusion**: Reject H₀ → Paid users watch significantly more than free users.

---

### 🌍 Country Comparison (India vs US, Free Plan Only - 2022)
- **F-test**:
  - **F = 0.9336**
  - **p-value = 0.0003** → Reject equal variances assumption.
- **T-test (Unequal Variance)**:
  - **t-statistic** = -1.21
  - **p-value = 0.113**
  - **Critical t-value = 1.65**
- ❌ **Conclusion**: Fail to reject H₀ → No significant difference in engagement between the US and India for free-plan students in 2022.

---

## Final Insights

- Platform should continue investing in premium content since paid students show higher engagement.
- Localization strategies in India and the US may not require different engagement methods for free users as their usage patterns are statistically similar.

---

## Next Steps (If Extended)

- Introduce cohort analysis (by age or class level)
- Analyze churn rate or session frequency
- Build dashboards using Power BI or Tableau for better visualization
