# ALGORITHMIC_TRADING

This project is aimed to predict whether Alphabet Soup funding applicants will be successful by creating a binary classification model using a deep neural network.

Step 1: Establish a Baseline Performance



                precision    recall  f1-score   support

        -1.0       0.43      0.04      0.07      1804
         1.0       0.56      0.96      0.71      2288

    accuracy                           0.55      4092
   macro avg       0.49      0.50      0.39      4092
weighted avg       0.50      0.55      0.43      4092

Noted that the precision is 0.43 for the -1 class and 0.56 for the 1 class. The recall is 0.04 for he -1 class and 0.96 for the 1 class. Based on the higher recall, it seems that this model is better at predicting the 1 class than -1 class.


Step 2: Tune the Baseline Trading Algorithm

Step 3: Evaluate a New Machine Learning Classifier

Step 4: Create an Evaluation Report

Information about the reference data resources: 

emerging_markets_ohlcv.csv

## Technologies Jupyter lab with the following library and module:
pandas
hvplot
numpy
Pathlib
matplotlib.pyplot
sklearn: svm
sklearn.preprocessing: StandardScaler
pandas.tseries.offsets: DateOffset
klearn.metrics: classification_report




Contributors Brought to you by 2coconi@gmail.com

License This is under NM 2.0.


