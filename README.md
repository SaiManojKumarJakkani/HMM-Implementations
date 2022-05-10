# HMM-Implementations
Speech-Music classification using HMM:
Here the data samples are audio files. The task is to classify the given audio file into Speech or Music class. Since the data samples are of time series data, so we used HMM model for the classification. The prior, tranisiton matrix and the emission matrix of the HMM model are learnt by training using training samples. Then using the learned model, when tried to classify test samples, it gave 0.89 accuracy score
       
Likelihood estimation of a sample file:
It contains the implementation of forward and backward algorithm from scratch. It is used to estimate the likelihood of a sample each from speech 
and music class then reporting which file is more likely under the given HMM model

Viterbi_algorithm:
It the implementation of Viterbi_algorithm from scratch. It is used to give the hidden state sequence of a given sample based upon on the above HMM model



