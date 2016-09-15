# MasterThesis
Trained Neural Network Model and weight results, implemented in python (Keras libraries)  

This repository contains the result of my master thesis with the topic of "Sensor Modelling with a focus on noise modelling in the context of Self-Driving Vehicles using Neural Network".  
The saved pre-trained model and related weights can simply be loaded with keras libraries.  
Name of the saved weight and models represent the number of hidden neurons, number of epochs (not needed for predict.model) and the batch size respectively.  
The input pattern is a normalized vector with the shape  of incident angle [0-45] degree with interval of 5, reflectance level [0.1,0.9], sensor reading [0-620], and the credence [0-1].  
The output of the NN model is a real value representing a real distance which needs to get denormalized.
