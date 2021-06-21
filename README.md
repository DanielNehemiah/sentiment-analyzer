1. BERT trained first on imdb, fine tuned with inverted labels from our data.. 
	- Kaggle Score: 0.81554
	- corrected_bert_based_imdb_plus_our_data_colab_inverted_training.csv
2. BERT trained first on imdb, fine tuned with our data - 1 epoch training.. 
	- Kaggle Score: 0.85858
	- 2_bert_based_imdb_plus_our_data_colab_correctly_trained_1epoch.csv
	- loss: 0.2872 - accuracy: 0.8741 - val_loss: 0.3422 - val_accuracy: 0.8616
	- Validation
	              precision    recall  f1-score   support

	           0       0.89      0.93      0.91      4765
	           1       0.71      0.60      0.65      1313

	    accuracy                           0.86      6078
	   macro avg       0.80      0.77      0.78      6078
	weighted avg       0.86      0.86      0.86      6078
	
3. BERT trained first on imdb, fine tuned with our data - 2 epoch training.. 
	- Kaggle Score: 0.83906
	- 3_bert_based_imdb_plus_our_data_colab_correctly_trained_2epoch.csv
	- loss: 0.0847 - accuracy: 0.9676 - val_loss: 0.6467 - val_accuracy: 0.8467
	- Validation
	              precision    recall  f1-score   support

	           0       0.89      0.91      0.90      4765
	           1       0.66      0.60      0.63      1313

	    accuracy                           0.85      6078
	   macro avg       0.78      0.76      0.77      6078
	weighted avg       0.84      0.85      0.84      6078
4. Non-trained existing model with emojis cardiffnlp/twitter-roberta-base-offensive
5. Non-trained existing model without emojis cardiffnlp/twitter-roberta-base-offensive
6. Non-trained existing model with emojis cardiffnlp/twitter-roberta-base-sentiment
7. Non-trained existing model without emojis cardiffnlp/twitter-roberta-base-sentiment