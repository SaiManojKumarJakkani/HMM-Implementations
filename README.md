# HMM-Implementations
I have considered the following HMM definition for the implementation of Forward, Backward and Viterbi algorithms:
Prior probabilities = [0.5, 0.5, 0.0]
Transition Matrix = [[0.6, 0.4, 0.0],
                     [0.3, 0.5, 0.2],
                     [0.0, 0.1, 0.9]]
Emission matrix = [[0.25, 0.25, 0.25, 0.25, 0.0, 0.0, 0.0, 0.0],
                  [0.125, 0.125, 0.125, 0.125, 0.125, 0.125, 0.125, 0.125],
                  [0.0, 0.0, 0.0, 0.0, 0.0, 0.5, 0.5, 0.0]]
       
Likelihood estimation of a sample file:
It contains the implementation of forward and backward algorithm from scratch. It is used to estimate the likelihood of a sample each from speech 
and music files then reporting which file is more likely under the given HMM model
