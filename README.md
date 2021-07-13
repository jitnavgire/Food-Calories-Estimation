# Food-Calories-Estimation
# Introduction

In today’s world a healthy lifestyle is a must for every individual and what they consume is of utmost importance in order to achieve the same.We focus on creating software which gives the calorie of the food which the user is going to consume.
The software will take images as input from the user. The food item in the image will be detected with the help of CNN algorithm. 
After classification image segmentation will be done. After segmentation of images,the volume of the food item is calculated using the known volume of the probe object.Then  the mass of the food item is calculated with the help of formulas and then the calories of the food item will be calculated using the relation between mass and calories

# Motivation
Nowadays it is very difficult for a person to track the calories consumed by them. The intake of calories plays a very vital role in one’s healthy lifestyle. 
Earlier the users used to track their calories intake with the help of charts or timetable. These methods are a bit tedious and difficult for the user to follow judiciously. We have come up with a project to help the user track the number of calories which it takes in with the help of simple images of the food item.


# Objective
Due to improvement in people standard of living, obesity rates are increasing at an alarming speed and this is reflective to the risks in people health.
To help people for  tracking  the calories of the food we aim to design a system which  will be able to predict the calories of the food using the food image.

# Research Methodology
The project consists of three steps, identifying food from an image ,calorie estimation from it and then model deployment. 
1.Trained the model: 
We trained the model with 7 food images using the classifier CNN (convolutional Neural Network) Model. We used Food dataset name FOODD which contains different kinds of food.
2.Calorie Prediction
We have predicted the calories from the segmented image. We use the thumb finger for calibration purposes. The thumb is placed next to the dish while clicking the photo and this thumb gives us the estimate of the real-life size of the food item and helps estimate volume accurately.
3. Model Deployment
We have deployed our model using flask 


                 Architectural Design
            
![design](https://user-images.githubusercontent.com/64503158/125401147-6c9f1600-e3d0-11eb-96ab-b4ab31a69f62.PNG)

                Convolutional Neural Network
![cnn](https://user-images.githubusercontent.com/64503158/125401659-12eb1b80-e3d1-11eb-9257-b1753c72f996.PNG)
                  
                  Image Segmentation
                  

