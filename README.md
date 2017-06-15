# SELU_Keras_Tutorial

[Self-Normalizing Neural Networks](https://arxiv.org/abs/1706.02515)

```
This paper introduces new methods to significantly increase NN effectiveness using three design choices:

1. By using a new activation function called SELU. 
2. By using weight initialization technique (lecun_normal).
3. By using a new Dropout function called AlphaDropout (set to a default value around 0.1).

NOTE: In the few experiments I have conducted, I have also observered a small bump in scores just changing the Dense Fully Connected layers using SELU/SSN.

```

![SELU HOT](https://github.com/bigsnarfdude/SELU_Keras_Tutorial/blob/master/seluSoHotRightNow.jpg)


#### Step #1

Take a look at the benchmark comparison to understand MLP-SELU

https://github.com/bigsnarfdude/SELU_Keras_Tutorial/blob/master/Basic_MLP_combined_comparison.ipynb

![SELU COMPARISON](https://github.com/bigsnarfdude/SELU_Keras_Tutorial/blob/master/sleu.png)

