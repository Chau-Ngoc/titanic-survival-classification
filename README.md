# Welcome to the Titanic Survival Status Classification
In the notebook, we will explore the Titanic dataset collected from [Kaggle's Titanic competition](https://www.kaggle.com/c/titanic). The data includes **train.csv** and **test.csv**.

The **train.csv** is provided with the outcomes (the ground truth) for each passenger. This data is used to train the models.

The **test.csv** does not include the outcomes, it's the models' job the predict.

Also included is **gender_submission.csv**, a set of predictions that assume all and only female passengers survive, as an example of what a submission file should look like.

The models used in this notebook are SVC, RandomForestClassifier and LogisticRegression and are evaluated on accuracy score. The best model achieves 82% accuracy.
