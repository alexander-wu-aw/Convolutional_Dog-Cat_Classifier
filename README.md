# Convolutional_Dog-Cat_Classifier
A convolutional neural network is trained with images of dogs and cats. It then predicts whether a new image is either a dog or a cat

A data set is obtained with 1000 images of cats and dogs, 50% cats, and 50% dogs. The set is split up into 80% training and 20% test. A convolutional neural network is built from the keras library. We keep each image's color, so each example is a 3 dimensional tensor, with red green and blue values. The first convlution layer of the netowrk has a filter of 3x3 pixels, a relu activation function, and then a max pooling layer with a 2x2 scanner. The only hidden layer has 128 neurons, and the output layer outputs one sigmoid acitvation neuron.

The average accuracy obtained from training the model was around 80%


This project was built to solidify my knowledge of deep learning, and image based artificial intelligence. I created this project with the help of the Deep Learning A-Z Udemy course. 
