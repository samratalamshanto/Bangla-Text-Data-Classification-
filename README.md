# Bangla-Text-Data-Classification-
Here some Deep Learning and Machine Learning approaches are used to classify Bangla Text Data.

Comparing multiple model architectures, I got highest accuracy from Bi-LSTM model for batch_size =128 and the accuracy is 93.50%. The File name is "Num_4_Bangla_Text_Data_Classification_using_Bi_LSTM_(batch_size=128)_93_50_.ipynb".

1. In file "Num_1_Exploratory_Data_Analysis_(EDA).ipynb", I try to do some Exploratory Data Analysis(EDA) for given data.
2. In file "Num_2_Bangla_Text_Data_Classification_using_Machine_Learning_Approach.ipynb", I used some machine learnig classifier like naive bayes and logistic regression on the given data. I got 87% accuracy from Multinomial Naive Bayes and 89% from Multinomial Logistic Regression.
3. In file "Num_3_simple_LSTM_batch_size=128_without_L2_regularization_small_layer_90_82_.ipynb", I used a simple RNN model using LSTM and got 90.82% accuracy.
4. In file "Num_4_Bangla_Text_Data_Classification_using_Bi_LSTM_(batch_size=128)_93_50_.ipynb", I used RNN model using Bi-LSTM and used some dense layer, L2 Regularization and got highest accuracy of 93.50% from this model.
5. In file "Num_5_1_different_LSTM_layer_batch_size=128_without_L2_regularization_less_layer_91_65_.ipynb", I tried to comapre the differences with other models. Here, I used some different units in LSTM layer and did not use the L2 regularization in the model. I got 91.65% accuracy from this model.
6. In files "Num_6_1_LSTM_without_L2_regularization_less_layer_92_.ipynb" and "Num_6_2_Bi_LSTM_without_L2_regularization_less_layer_93_32_.ipynb", I tried to compare the difference between the LSTM layer and Bi-LSTM layer in RNN. I got better accuracy from Bi-LSTM(93.32%) than LSTM(92.0%).
7. In file "Num_7_Bangla_Text_Data_Classification_using_CNN_(batch_size=64).ipynb", I used CNN model and used 64 as batch_size. I got 92.97% accuracy from this model.
8. In file "Num_8_Bangla_Text_Data_Classification_using_CNN_(batch_size=128).ipynb", I used same CNN model but changed the batch_size(128). I got 92.67% accuracy from this model.

