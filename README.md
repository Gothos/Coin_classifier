# Coin_classifier
Simple CNN-based coin classifier in Keras. Uses a ResNet-50 backbone to extract features and a custom 211-class classifier head.Uses Gaussian noise as a form of data augmentation.
To use, please reset the training paths within the notebook to the data directories, and train the model. Was trained on data from
this [Kaggle Challenge](https://www.kaggle.com/competitions/currency-prediction-challenge) (expects csv data in the same format)\n
Achieved over 80% accuracy on the same Kaggle Challenge.


