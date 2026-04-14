# Summary of Ensemble

[<< Go back](../README.md)


## Ensemble structure
| Model    |   Weight |
|:---------|---------:|
| 3_Linear |        1 |

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
