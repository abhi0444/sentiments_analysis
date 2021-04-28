# Sentiments_Analysis

`` Hear I have done sentiment analysis of US Airline Dataset on Kaggle using NLP and Deep Leaning ``
`` Dataset Link - https://www.kaggle.com/crowdflower/twitter-airline-sentiment ``
`` Classes in Dataset - Positive, Negative & Neutral ``

## Appraoch 1 - Using Machine Learning 

  `` 1 . Algorith Used  - Multinomial Naive Bayes Classifier ``
  
  `` 2 . Accuracy - 76% ``
  
  Classification Matrix 
  
  ``            precision    recall  f1-score   support

           0       0.82      0.89      0.85      2771
           1       0.61      0.45      0.52       944
           2       0.68      0.67      0.68       677

    accuracy                           0.76      4392
   macro avg       0.70      0.67      0.68      4392
weighted avg       0.75      0.76      0.75      4392   ``


## Approach 2 - Using Deep Learning

`` 1 . Validation Accuracy - 80.26% ``

`` 2 . Testing Accuracy - 78.83% ``

  Model Actitecture 
  
  ``  Model: "sequential_4"
_________________________________________________________________
Layer (type)                 Output Shape              Param #   
=================================================================
dense_12 (Dense)             (None, 64)                640064    
_________________________________________________________________
dropout_4 (Dropout)          (None, 64)                0         
_________________________________________________________________
dense_13 (Dense)             (None, 64)                4160      
_________________________________________________________________
dropout_5 (Dropout)          (None, 64)                0         
_________________________________________________________________
dense_14 (Dense)             (None, 3)                 195       
=================================================================
Total params: 644,419
Trainable params: 644,419
Non-trainable params: 0
_________________________________________________________________  ``

  `` 3 . Graph Outputs ``
  
  
  
  
