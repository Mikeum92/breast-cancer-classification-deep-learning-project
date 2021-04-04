# breast-cancer-classification-deep-learning-project

Keras TF 2.0 - Classification Project
Classification task with Keras API for TF 2.0

The Data
Breast cancer wisconsin (diagnostic) dataset
Data Set Characteristics:

:Number of Instances: 569
:Number of Attributes: 30 numeric, predictive attributes and the class

Attempting to predict if cancer is benign or not based on features. 
Deep learning neural network model used in classification.
Project illustrates:
      * The effect of using too many epochs during model fitting resulting in overfitting.
      * Introducing EarlyStopping() method to top training when a monitored loss quantities has stopped improving.
      * Adding DropOut Layers to turn off a fraction set of neurons during training to prevent overfitting. 

Model Evaluation 
Classification Report
          precision    recall  f1-score   support

           0       0.98      0.98      0.98        55
           1       0.99      0.99      0.99        88

    accuracy                           0.99       143
   macro avg       0.99      0.99      0.99       143
weighted avg       0.99      0.99      0.99       143

Confusion Matrix
[[54  1]
 [ 1 87]]
