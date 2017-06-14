# SELU_Keras_Tutorial

[Self-Normalizing Neural Networks](https://arxiv.org/abs/1706.02515)

#### Step #1

Take a look at the benchmark to understand how RELU works on basic CNN

https://github.com/bigsnarfdude/SELU_Keras_Tutorial/blob/master/CNN_Basic_Benchmark.ipynb

Loss after 12 epochs is: 0.0275088263036


#### Step #2

SELU based MLP without Dropout

https://github.com/bigsnarfdude/SELU_Keras_Tutorial/blob/master/SELU_NoDropOut_Exploration.ipynb

Loss after 10 epochs is: 0.09173990068372441


#### Step #3

SELU based MLP with normal Dropout

https://github.com/bigsnarfdude/SELU_Keras_Tutorial/blob/master/SELU_Dropout_exploration.ipynb

Loss after 10 epochs is: 0.081480191320957962


#### Step #4

SELU based MLP with AlphaDropout

https://github.com/bigsnarfdude/SELU_Keras_Tutorial/blob/master/SELU_Dropout_Exploration_SSN.ipynb

Loss after 10 epochs is: 0.092325189258183393



#### Step #5

SELU based CNN with normal Dropout

https://github.com/bigsnarfdude/SELU_Keras_Tutorial/blob/master/SELU_Basic_CNN.ipynb

Loss after 200 epochs is: 0.0824557533961



#### Step #6

SELU based CNN with AlphaDropout

https://github.com/bigsnarfdude/SELU_Keras_Tutorial/blob/master/SELU_SSN_based_CNN_AlphaDropout.ipynb

Loss after 200 epochs is: 0.098869990336
