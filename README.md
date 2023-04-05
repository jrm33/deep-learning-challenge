# deep-learning-challenge Analysis

Neural Network Model Analysis

Overview:
The purpose of this exercise to to evaluate and train the model for efficiency and accuracy for AlphabetSoup.

Data Preprocessing:
We needed to read in the csv and cleanthe data to remove unnecessary columns (EIN and NAME) to help the otimization of the model. In addition
we needed to spilt the data into our features and target arrays from the 'IS SUCCESSFUL" column to test and train the model for accuracy.

Optimizing model:
The first attempt to optimize the model I switched the hidden nodes layers to 50 for layer 1 and 100 for layer 2. 
I also increased to ephochs from 100 which it was initally set at to 150 and switched the activation on the second hidden layer to sigmoid.
This optimized the model to only reach 74%.

The second attempt I added a thirdhidden layer with an activation of sigmoid, updated the hidden layer nodes to 10, 20, 50 and
added a third hidden layer. This model only reached a 73% accuracy.

The third and final attempt, I adjusted the hidden nodes layers to 5, 10, and 15 and updated 
all three hidden layers to "relu', leaving the output layer with an activation of sigmoid.
This model only reached 73% accuracy.

Summary:
In the end, we did not acheieve a 75% accuracy. It seems our first attempt in trying to optmize the model was our best attempt. 