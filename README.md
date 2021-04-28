# Sentiments_Analysis

`` Hear I have done sentiment analysis of US Airline Dataset on Kaggle using NLP and Deep Leaning ``
`` Dataset Link - https://www.kaggle.com/crowdflower/twitter-airline-sentiment ``
`` Classes in Dataset - Positive, Negative & Neutral ``

## Appraoch 1 - Using Machine Learning 

  `` 1 . Algorith Used  - Multinomial Naive Bayes Classifier ``
  
  `` 2 . Accuracy - 76% ``
  
  Classification Matrix 
  
                precision    recall  f1-score   support

           0       0.79      0.92      0.85      1806
           1       0.62      0.42      0.50       589
           2       0.74      0.58      0.65       486
           
   accuracy                            0.76      2881
   macro avg       0.72      0.64      0.67      2881
   weighted avg    0.75      0.76      0.75      2881
  
  


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
  
  
  
  
