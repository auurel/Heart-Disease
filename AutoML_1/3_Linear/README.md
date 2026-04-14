# Summary of 3_Linear

[<< Go back](../README.md)


## Logistic Regression (Linear)
- **n_jobs**: -1
- **explain_level**: 2

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.75
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
auc

## Training time

3.3 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.334924 | nan         |
| auc       | 0.931818 | nan         |
| f1        | 0.872727 |   0.591134  |
| accuracy  | 0.885246 |   0.591134  |
| precision | 1        |   0.846318  |
| recall    | 1        |   0.0133119 |
| mcc       | 0.776719 |   0.738523  |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.334924 |  nan        |
| auc       | 0.931818 |  nan        |
| f1        | 0.872727 |    0.591134 |
| accuracy  | 0.885246 |    0.591134 |
| precision | 0.888889 |    0.591134 |
| recall    | 0.857143 |    0.591134 |
| mcc       | 0.768734 |    0.591134 |


## Confusion matrix (at threshold=0.591134)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |               30 |                3 |
| Labeled as 1 |                4 |               24 |

## Learning curves
![Learning curves](learning_curves.png)

## Coefficients
| feature   |   Learner_1 |
|:----------|------------:|
| ca        |   1.0175    |
| sex       |   0.711283  |
| cp        |   0.605118  |
| thal      |   0.546046  |
| chol      |   0.46079   |
| slope     |   0.24261   |
| exang     |   0.242417  |
| restecg   |   0.198602  |
| trestbps  |   0.147938  |
| oldpeak   |   0.143452  |
| intercept |   0.0215842 |
| age       |  -0.0101871 |
| fbs       |  -0.167585  |
| thalach   |  -0.495158  |


## Permutation-based Importance
![Permutation-based Importance](permutation_importance.png)
## Confusion Matrix

![Confusion Matrix](confusion_matrix.png)


## Normalized Confusion Matrix

![Normalized Confusion Matrix](confusion_matrix_normalized.png)


## ROC Curve

![ROC Curve](roc_curve.png)


## Kolmogorov-Smirnov Statistic

![Kolmogorov-Smirnov Statistic](ks_statistic.png)


## Precision-Recall Curve

![Precision-Recall Curve](precision_recall_curve.png)


## Calibration Curve

![Calibration Curve](calibration_curve_curve.png)


## Cumulative Gains Curve

![Cumulative Gains Curve](cumulative_gains_curve.png)


## Lift Curve

![Lift Curve](lift_curve.png)



## SHAP Importance
![SHAP Importance](shap_importance.png)

## SHAP Dependence plots

### Dependence (Fold 1)
![SHAP Dependence from Fold 1](learner_fold_0_shap_dependence.png)

## SHAP Decision plots

### Top-10 Worst decisions for class 0 (Fold 1)
![SHAP worst decisions class 0 from Fold 1](learner_fold_0_shap_class_0_worst_decisions.png)
### Top-10 Best decisions for class 0 (Fold 1)
![SHAP best decisions class 0 from Fold 1](learner_fold_0_shap_class_0_best_decisions.png)
### Top-10 Worst decisions for class 1 (Fold 1)
![SHAP worst decisions class 1 from Fold 1](learner_fold_0_shap_class_1_worst_decisions.png)
### Top-10 Best decisions for class 1 (Fold 1)
![SHAP best decisions class 1 from Fold 1](learner_fold_0_shap_class_1_best_decisions.png)

[<< Go back](../README.md)
