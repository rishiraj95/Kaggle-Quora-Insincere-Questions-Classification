# Kaggle-Quora-Insincere-Questions-Classification
This repository contains the different kernels I wrote for the Kaggla Quora Insincere Questions Classification Competition.

I have posted four kernels including LSTM, GRU with and without attention and Separable Convolution 1D. All the kernels create the embedding matrix from glove embeddings posted in the Kaggle dataset. The notebooks are well commented and pretty straightforward.

Google claims the Separable Convolution separates cross channel and cross feature correlation and works best, however, the LSTM, GRU implementation with attention worked best for this competition with an F1 score 0.695, where the winner had an F1 score of 0.705. 
