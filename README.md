# Malware modus operandi - NT230.N21.ANTT
There is a set of machine learning methods to leverage a binary classification task to classify MS Office documents as malicious or benign. 
I used Random Forest, XGBoost, a Support Vector Classifier (SVC), and a Multi-layer Perceptron (MLP) classifier.
## Best configuration parameters of each model
- Random Forest:	n_estimators=200, max_depth=20, max_features=10
- XGBoost:	learning_rate=0.02, max_depth=5, subsample=0.6, max_features=10
- Support Vector Classifier:	kernel=’rbf’
- Multi-layer Perceptron: hidden_layer_sizes=(11,11,11), max_iter=500
