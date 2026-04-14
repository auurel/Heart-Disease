# AutoML Leaderboard

| Best model   | name                                                         | model_type     | metric_type   |   metric_value |   train_time |
|:-------------|:-------------------------------------------------------------|:---------------|:--------------|---------------:|-------------:|
|              | [1_Baseline](1_Baseline/README.md)                           | Baseline       | auc           |       0.5      |         1.35 |
|              | [2_DecisionTree](2_DecisionTree/README.md)                   | Decision Tree  | auc           |       0.860931 |         7.89 |
| **the best** | [3_Linear](3_Linear/README.md)                               | Linear         | auc           |       0.931818 |         4.68 |
|              | [4_Default_Xgboost](4_Default_Xgboost/README.md)             | Xgboost        | auc           |       0.878788 |         4.34 |
|              | [5_Default_NeuralNetwork](5_Default_NeuralNetwork/README.md) | Neural Network | auc           |       0.919913 |         2.69 |
|              | [6_Default_RandomForest](6_Default_RandomForest/README.md)   | Random Forest  | auc           |       0.906926 |         3.9  |
|              | [Ensemble](Ensemble/README.md)                               | Ensemble       | auc           |       0.931818 |         1.47 |

### AutoML Performance
![AutoML Performance](ldb_performance.png)

### AutoML Performance Boxplot
![AutoML Performance Boxplot](ldb_performance_boxplot.png)

### Features Importance (Original Scale)
![features importance across models](features_heatmap.png)



### Scaled Features Importance (MinMax per Model)
![scaled features importance across models](features_heatmap_scaled.png)



### Spearman Correlation of Models
![models spearman correlation](correlation_heatmap.png)

