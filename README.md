# Sentimental Analysis using LSTM(KNN)

### Aim and motivation
LSTM have truly changed the way in NLP. My goal here is to create basic reference for LSTM for NLP here w.r.t sentimental analysis.

### What is LSTM ?
Long short-term memory (LSTM) units (or blocks) are a building unit for layers of a recurrent neural network (RNN). A RNN composed of LSTM units is often called an LSTM network. A common LSTM unit is composed of a cell, an input gate, an output gate and a forget gate. The cell is responsible for "remembering" values over arbitrary time intervals; hence the word "memory" in LSTM.

### This repository provides insights into following basic operations w.r.t LSTM for NLP:
1) Load embeddings
2) Build the vocabulary and improved its coverage
3) Tokenize
4) Used callbacks like early stopping and model checkpoint to improve model performance
5) Used dropout regularization to regularize deep neural network
6) Used Bidirectional, GlobalMaxPooling1D, SpatialDropout1D, Embedding, CuDNNLSTM layers to improve model
performance
