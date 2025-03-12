# 455 Final Project

## The Problem
I was interested in applying what I have learnt this quarter to the bird classification challenge.
We were given a dataset of images of different birds and challenged to develop a model that would be able to classify them by their species.
I have been really interested in the different forms of neural networks that we have learnt throughout this quarter, so I decided to train models with different levels of complexity to determine how well they were able to be trained on a large and complex dataset. 
## The Approach
I considered three different neural network implementations. 
1. a simple one layer Linear model 
2. a Linear model with a hidden layer with ReLU activation function 
3. a pretrained ResNet model

## Results
The two linear layer models showed similar accuracies over the 20 epochs. However, they didn't have the expected initial steep increase and later plateau in accuracy. This could be because these models were too simple and therefore could not fit well to the data or due to suboptimal hyperparamter settings.
So, I decided to perform some hyperparameter tuning on the Linear model with a hidden layer to see if it would improve performance. This also did not have any impact on the performance of the model.
The ResNet model performed better than the linear layer models as expected. The graph of accuracy over epochs additionally showed a steady increase in accuracy over the 20 epochs it was trained for. However, this accuracy still remained relatively low, reaching a training accuracy around 0.6 and a test accuracy of 0.29.
## Discussion
Through this project I was able to visualize how different levels of complexity in neural networks performed on real world data.
I was also able to explore using PyTorch for Computer Vision applications.
It was a bit of a challenge to get familiar with the toolset and debug the issues I encountered,
I was unfortunately not able to achieve a high accuracy with any of these models, so I would like to experiment more with hyperparameter tuning and transfer learning to improve my accuracy. I would also like to try out image augmentation to prevent overfitting to the ResNet model.
I would like to incorporate other pretrained models available in PyTorch to compare their performance against these models. It would also be interesting to explore ways to make the training process more efficient.
## Video
https://youtu.be/DJZTdgomSa4
