# Handwritten recognition by CNN & Bidirectional LSTM

## Problem Statement
A medical company needs to take handwritten prescription and retrieve the text from it. To do
this manually, it will require a lot of time and lots of cost to the company. So, the company
wants to automate this task. I need to create a neural network model that will take images
as input, read the text images, and convert it into digital text.
To solve this problem, I created a CNN LSTM model.


# model architecture 
1. input layer that takes image shape.
2. two block from [conv2D,maxpoling2d ] layers to extract features. 
3. reshape, dense and dropout layers to passing the output to RNN model.
4. two layers from Bidirectional lstm.
5. input (label) and dense layers to extract the word.
6. finally , added CTC layer for calculating CTC loss at each step. 
