# Summary of 2_DecisionTree

[<< Go back](../README.md)


## Decision Tree
- **n_jobs**: -1
- **criterion**: gini
- **max_depth**: 3
- **explain_level**: 2

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.75
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
auc

## Training time

7.5 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.663917 |  nan        |
| auc       | 0.860931 |  nan        |
| f1        | 0.807018 |    0.347826 |
| accuracy  | 0.819672 |    0.347826 |
| precision | 0.933333 |    0.833333 |
| recall    | 1        |    0.05     |
| mcc       | 0.63823  |    0.347826 |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.663917 |  nan        |
| auc       | 0.860931 |  nan        |
| f1        | 0.807018 |    0.347826 |
| accuracy  | 0.819672 |    0.347826 |
| precision | 0.793103 |    0.347826 |
| recall    | 0.821429 |    0.347826 |
| mcc       | 0.63823  |    0.347826 |


## Confusion matrix (at threshold=0.347826)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |               27 |                6 |
| Labeled as 1 |                5 |               23 |

## Learning curves
![Learning curves](learning_curves.png)

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



[<< Go back](../README.md)
