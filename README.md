# Tweet_Sentiment_Analysis
The objective of this evaluation is to provide a comparison between the performances of an RNN and LSTM model on the Tweet Emotions dataset, classifying between three classes: sadness, neutral and happiness. The evaluation focuses on the models’ final validation accuracies, training stability, and classification reports.

Dataset: Tweets emotion dataset (19.012 filtered out belonging to 3 classes)
Optimization: SMOTE oversampling technique applied to two classes to balance dataset, Bidirectional layers, 
              Layer normalization, L2 regularization, Adam optimizer, gradient clipping, 3 fold cross validation, 
              80:20 ratio, early stopping, 10 epochs and 32 batch size
