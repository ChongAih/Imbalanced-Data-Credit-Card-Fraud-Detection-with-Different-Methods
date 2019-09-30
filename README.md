# Imbalanced-Data-Credit-Card-Fraud-Detection-with-Different-Methods
Comparison study of metrics (F1, recall), sampling (under, over, SMOTE), cost sensitive (class weight) and different model (GB, XGB)'s performance in handling imbalanced data

* The script is coded in Google Colab, thus there exist commands to retrieve files from and store files to google drive. Modification is required for any personal use.

* Besides the script, the data used in the project can be retrieved from Kaggle website: https://www.kaggle.com/mlg-ulb/creditcardfraud. 

* In this project, several methods are explored for handling imbalanced data and performances are compared. For metric methods, the metrics to be trained by the neural network model are modified. F1-score and recall score are tested. For sampling methods, the distribution of training and testing dataset is modified. Undersampling and oversampling (SMOTE - synthetic minority oversampling technique) are tested. For cost sensitive methods, the class weight is computed for each label and the minority class gets a higher class weight and more attention. For different model methods, a tree based machine learning method (gradient boosting and extreme gradient boosting) are tested.
