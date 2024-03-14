## Description
The task involves analyzing a dataset containing 10,000 samples of historical loan applications. Each sample comprises 83 initial data points (columns).
The target variable, denoted as fpd30 (FPD for First Payment Delay 30 days),
indicates whether the client defaulted (1) or paid back the loan (0). The goal is to develop a classification model to predict whether the client will default or repay the loan.

### Task Execution
- Conducted exploratory analysis on the provided dataset to gain insights into the data distribution, identify patterns, and understand relationships between variables.

- Pre-processed the data to prepare it for model training. This included encoding features to ensure compatibility with the selected model.

- Trained the chosen model using the pre-processed dataset. This involved fitting the model to the training data to learn patterns and relationships that can be used for prediction.

- Evaluated the feature importance within the trained model to determine which features have the most significant impact on the prediction task. This step helps in understanding the underlying factors contributing to loan default or repayment.

#### Execution environment: [Google Colab](https://colab.research.google.com/)
#### Python Libraries: [pandas](https://pandas.pydata.org/), [scikit-learn](https://scikit-learn.org/stable/)
#### Model trained using [RandomForestClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html) from scikit-learn.

