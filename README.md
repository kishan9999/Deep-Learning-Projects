# Deep-Learning-Projects
exploring deep learning concepts using simple python code implementation.


### Python-Libraries:
1. tensorflow 2.3.0
2. matplotlib: 3.2.2
3. pandas: 1.0.5
4. numpy: 1.18.5



some suggested settings combinations for the `RandomForestRegressor`:

| Combination | maxDepth | maxBins | minInstancesPerNode | minInfoGain | maxMemoryInMB | cacheNodeIds | checkpointInterval | impurity | numTrees | featureSubsetStrategy | seed | subsamplingRate |
|-------------|----------|---------|---------------------|-------------|---------------|--------------|--------------------|----------|----------|-----------------------|------|-----------------|
| 1           | 5        | 32      | 1                   | 0.0         | 256           | False        | 10                 | variance | 50       | auto                  | 42   | 1.0             |
| 2           | 10       | 64      | 2                   | 0.01        | 512           | True         | 5                  | variance | 100      | sqrt                  | 123  | 0.8             |
| 3           | 20       | 32      | 1                   | 0.001       | 256           | False        | 15                 | variance | 150      | log2                  | 42   | 1.0             |
| 4           | 15       | 40      | 3                   | 0.0         | 128           | True         | 20                 | variance | 200      | all                   | 99   | 0.9             |
| 5           | 8        | 50      | 1                   | 0.005       | 256           | False        | 10                 | variance | 75       | onethird              | 7    | 1.0             |



| Combination | max_depth | learning_rate | n_estimators | gamma | min_child_weight | subsample | colsample_bytree | reg_alpha | reg_lambda | random_state |
|-------------|-----------|---------------|--------------|-------|------------------|-----------|------------------|-----------|------------|--------------|
| 1           | 3         | 0.1           | 100          | 0     | 1                | 1.0       | 1.0              | 0.0       | 1.0        | 42           |
| 2           | 6         | 0.05          | 200          | 0.1   | 3                | 0.8       | 0.8              | 0.1       | 1.0        | 123          |
| 3           | 10        | 0.01          | 300          | 0.2   | 5                | 0.7       | 0.9              | 0.5       | 1.5        | 99           |
| 4           | 5         | 0.1           | 150          | 0.3   | 2                | 0.9       | 0.7              | 0.3       | 0.8        | 77           |
| 5           | 7         | 0.2           | 100          | 0.0   | 1                | 1.0       | 0.5              | 0.0       | 2.0        | 202          |
