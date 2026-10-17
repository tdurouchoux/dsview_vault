---
already_read: false
link: https://www.kenkoonwong.com/blog/roc-auc-dca/
read_priority: 4
relevance: 0
source: Data Elixir
tags:
- Data_Analysis
type: Content
upload_date: '2026-10-17'
---

https://www.kenkoonwong.com/blog/roc-auc-dca/

## Summary

A deep dive into ROC-AUC, its limitations (low prevalence, miscalibration), and how Decision Curve Analysis (DCA) addresses blind spots in model evaluation.

**ROC-AUC Basics**
- ROC curve plots TPR (sensitivity) vs FPR (1-specificity).
- ROC-AUC computed from scratch via trapezoidal rule on TPR/FPR pairs.
- Youden-J index (J = TPR + Specificity - 1) identifies optimal threshold.

**Pitfalls of ROC-AUC**
- Low prevalence (e.g., 1% positive class) inflates AUC despite poor PPV (e.g., 0.17).
- Identical ROC-AUC (0.74) for well-calibrated, biased, overconfident, and underconfident models.

**Calibration Analysis**
- Calibration curves: bin predictions, compare mean predicted vs observed rates.
- Bias = intercept shift (e.g., biased model: intercept = -0.952, slope = 0.958).
- Miscalibration = slope shift (overconfident: slope = 0.319; underconfident: slope = 2.39).
- Brier score (lower = better): well-calibrated (0.207), biased (0.245), overconfident (0.237), underconfident (0.219).
- Cox calibration: fit logistic regression on predicted logits vs true labels.

**Decision Curve Analysis (DCA)**
- Net benefit = (TP/n) - (FP/n) * (threshold / (1 - threshold)).
- Compares model to "treat all" and "treat none" strategies.
- XGBoost (AUC=0.762, Brier=0.198) outperforms logistic regression (AUC=0.710, Brier=0.216) in nonlinear simulation.
- DCA shows XGBoost yields higher net benefit at thresholds ≥0.25 (e.g., 0.28 at threshold=0.4).

**Key Takeaways**
- ROC-AUC alone is insufficient; assess calibration (Brier, Cox) and decision utility (DCA).
- DCA quantifies clinical value: net benefit in true-positive-equivalents per patient.
- Bias vs miscalibration: intercept vs slope deviations in calibration plots.

## Links

- [Wikipedia: Receiver Operating Characteristic](https://en.wikipedia.org/wiki/Receiver_operating_characteristic) : A comprehensive overview of the ROC curve, its history, and its applications in binary classification, including definitions of sensitivity, specificity, and the ROC curve itself.
- [Frank Harrell's Blog: Decision Curve Analysis](https://www.fharrell.com/post/addmarkerdca/) : A detailed explanation of Decision Curve Analysis (DCA), its purpose, and how to interpret net benefit curves for model evaluation in clinical or decision-making contexts.
- [Springer Article: Decision Curve Analysis in Medical Research](https://link.springer.com/article/10.1186/s41512-019-0064-7) : A peer-reviewed article introducing Decision Curve Analysis (DCA) as a method for evaluating prediction models, particularly in medical research, and comparing it to other metrics like ROC-AUC.


## Topics

![[topics/Concept/ROC Curve and AUC]]

![[topics/Concept/Cox calibration]]

![[topics/Concept/Decision Curve Analysis DCA]]

![[topics/Concept/Youden J index]]

![[topics/Library/tidyverse]]

![[topics/Library/pROC]]

![[topics/Concept/Calibration]]

![[topics/Concept/Low prevalence]]

![[topics/Concept/Brier Score]]

![[topics/Model/XGBoost]]