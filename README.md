# Malware modus operandi - NT230.N21.ANTT
There are several machine learning methods available to classify MS Office documents as malicious or benign in a binary classification task. 
For this purpose, I utilized the Random Forest, XGBoost, Support Vector Classifier (SVC), and Multi-layer Perceptron (MLP) classifier.

## Best configuration parameters of each model
- Random Forest:	n_estimators=200, max_depth=20, max_features=10
- XGBoost:	learning_rate=0.02, max_depth=5, subsample=0.6, max_features=10
- Support Vector Classifier:	kernel=’rbf’
- Multi-layer Perceptron: hidden_layer_sizes=(11,11,11), max_iter=500
