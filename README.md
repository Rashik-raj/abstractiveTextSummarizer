# abstractiveTextSummarizer

This is an abstractive text summarizer on **Amazon food reviews data set**. This is done using encoder-decoder seq2seq LSTM model.

1. Run **test.ipynb** to calculate the model weight.
2. Alternatively you can simply run **test_predict.py** to predict the summary.
3. Initially **trainedModel_weights2.h5** is loaded and used. It has max_text_len = 30 and max_summary_len = 10, trained over 42241 and tested over 4679 data set with accuracy rate of 72.19%.
4. You can also load **trainedModel_weights.h5** and use it. It has max_text_len = 50 and max_summary_len = 10, trained over 59683 and tested over 6613 data set with accuracy rate of 70.56%.
5. Total data set is above 500K but only 100K is loaded to train and test the model.
