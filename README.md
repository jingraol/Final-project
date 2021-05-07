# Final-project

This is the repository for final project.
I choose to analyze the cat and dog project. Through preprocessing the dataset, I know that the total number of data is 25,000, and two types of images: cats and dogs.
After viewing the dataframe, I started to split the dataset to training data and testing data. Because I want to have a higher accuracy on the model, and also I want 
to do something different than what we usually do in class assignments (70%/30%), so I split the dataset into 90% training and 10% testing to let the model learn the underlying distribution better.
In terms of choosing the model, I did some research online that when talking about image classification, there are two pre-trained model that performs well: VGG and ResNet.
So I choose these two models and test and compare on their accuracy. It's clear to see VGG's accuracy is much better than ResNet. So I use VGG model to test the test set.
The result is pretty accurate. 
