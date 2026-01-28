| Experiment ID | Model Type    | Hyperparameters | Preprocessing Steps | Feature Selection | Train/Test Split | Precision | AUC Score |
|---------------|---------------|-----------------|---------------------|-------------------|------------------|-----------|-----------|
| EXP-01        | Decision Tree | Default         | None                | All features      | 80/20            |           |           |
| EXP-02        | Decision Tree | Max depth = 5   | Scaling             | Selected          | 80/20            |           |           |
| EXP-03        | kNN           | k = 5           | StandardScaler      | Numeric only      | 80/20            | 0.96      | 0.98      |
| EXP-04        | kNN           | k = 10          | StandardScaler      | Numeric only      | 75/25            | 0.94      | 0.97      |