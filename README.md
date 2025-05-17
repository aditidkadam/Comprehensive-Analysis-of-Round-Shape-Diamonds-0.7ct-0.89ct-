## 💎 Comprehensive Analysis of Round Shape Diamonds (0.7ct – 0.89ct)

###  Goal
To compare **Lab Grown** and **Natural Diamonds** based on their **Color**, **Clarity**, and **Average Price/Carat**, and to evaluate how these factors influence pricing using regression analysis and statistical modeling.

---

###  Learnings
- Applied regression modeling and statistical methods to pricing data.
- Identified how quality attributes like **color** and **clarity** affect diamond prices.
- Observed distinct pricing trends between **lab grown** and **natural diamonds**.
- Practiced data cleaning, aggregation, and visualization to support insights.

---

### Findings
- **Natural diamonds** have a higher price per carat across all clarity and color levels.
- **Color** has a stronger influence on price than clarity, especially in natural diamonds.
- **Lab grown diamonds** show price clustering around lower clarity grades (SI1, SI2).
- Regression models show **strong predictability** (R² > 0.90 for all models).
- **Heatmaps and covariance analysis** support the price variation across quality levels.

---

### Metrics

#### Statistical Summary

| Diamond Type     | Mean Price/Carat | Std. Deviation | 95% Confidence Interval |
|------------------|------------------|----------------|--------------------------|
| Natural Diamond  | $3,991.55        | 486.47         | ±181.65                  |
| Lab Grown Diamond| $821.76          | 176.66         | ±65.97                   |

---

####  Regression Metrics

| Diamond Type     | Covariance (Color) | R² (Color) | Covariance (Clarity) | R² (Clarity) |
|------------------|--------------------|------------|-----------------------|--------------|
| Natural Diamond  | -1622.54           | 0.9907     | -1262.07              | 0.9604       |
| Lab Grown Diamond| -720.84            | 0.9527     | -196.32               | 0.9113       |
