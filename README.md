# weather-trend-forecasting

## [Principal Component Analysis (PCA)](https://scikit-learn.org/1.5/modules/generated/sklearn.decomposition.PCA.html)
- PCA is a dimensionality reduction technique that transforms the data into a set of orthogonal components, capturing the maximum variance of the dataset.
- By reducing dimensions, it can potentially enhance model performance by mitigating overfitting and improving computational efficiency.

## [Random Forest](https://scikit-learn.org/1.5/modules/generated/sklearn.ensemble.RandomForestClassifier.html)
- Random Forest is an ensemble learning method that constructs multiple decision trees using bootstrapped subsets of the data and features.
- Each tree votes on the outcome, and the final prediction is determined by aggregating the results, improving overall accuracy and robustness.

## [XGBoost (XGB)](https://xgboost.readthedocs.io/en/stable/)
- XGBoost is a powerful gradient boosting method that builds an initial weak model and iteratively adds models to correct misclassified points.
- This approach minimizes errors by giving higher weights to misclassified points in subsequent iterations, improving predictive performance.

## [Stacking Method](https://scikit-learn.org/dev/modules/generated/sklearn.ensemble.StackingClassifier.html)
- Stacking combines multiple models into a unified pipeline, leveraging the strengths of different algorithms.
- The predictions from base models are used as input features to train a meta-model, enhancing the overall predictive accuracy.
