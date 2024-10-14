# Hand-written digit classification using Numpy
## Introduction
Handwritten digit recognition is the ability of a computer to recognize the human handwritten digits from different sources like images, papers, touch screens, etc, and classify them into 10 predefined classes (0-9).

So, here we are making *ANN* from scratch using *Numpy* for handwritten digit classification

## Dataset and Data loading :-
The dataset which we are using here is MNIST dataset. MNIST contains a total of 70,000 handwritten digit images (60,000 - training set and 10,000 - test set) in 28x28 pixel bounding box and anti-aliased.

![](https://github.com/Srishti002/hand-written-digit-classification-using-numpy/blob/main/Screenshot%202024-10-14%20000348.png)

![](https://github.com/Srishti002/hand-written-digit-classification-using-numpy/blob/main/Screenshot%202024-10-14%20000423.png)

## Step by Step Guide :-
1. Weight initialization
   
   ![](https://github.com/Srishti002/hand-written-digit-classification-using-numpy/blob/main/Screenshot%202024-10-14%20002013.png)

   - Weights and biases are initialized randomly.
   - Here in first layer, the number of neurons are 20 and 784 means 28 * 28 = 784 is size of the input image.
   - In second layer again, 20 neurons
   - Third layer is softmax layer containing 10 neurons.
     
2. Forward Propogation :-

   ![](https://github.com/Srishti002/hand-written-digit-classification-using-numpy/blob/main/Screenshot%202024-10-14%20190209.png)

   - Activation function used here is ReLU upto first two layers.
   - As we have 10 categories of output so the last layer will be softmax layer.

3. Backpropogation :-

   ![](https://github.com/Srishti002/hand-written-digit-classification-using-numpy/blob/main/Screenshot%202024-10-14%20192630.png)
   
    


   
