# Sentiment_Analysis_SageMaker_Deployment
Deployment of sentiment analysis model using Amazon AWS SageMaker
Forecast sentiment of movie review using neural networks. Implementation is made using PyTorch.

## Project Overview
In this project a recurrent neural network is constructed for the purpose of determining the sentiment of a movie review using the IMDB data set. The model is created using Amazon's SageMaker service. In addition, the model is deployed and a simple web app is constructed which will interact with the deployed model.

![alt text](https://github.com/udacity/deep-learning-v2-pytorch/raw/master/project-dog-classification/images/sample_dog_output.png)

## Features
IMDB reviews supported and checked
POSITIVE and NEGATIVE output is supported

## General Outline
Step 1: Downloading the data <br>
Step 2: Preparing and Processing the data<br>
Step 3: Upload the data to S3<br>
Step 4: Build and Train the PyTorch Model<br>
Step 5: Testing the Model<br>
Step 6: Deploying the model for testing<br>
Step 7: Use the model for testing<br>
Step 6 Deploy the model for the web app<br>
Step 7 Use the model for the web app<br>
## Setup
Clone this repo:<br>

git clone (https://github.com/Coder-Nikita/Sentiment_Analysis_SageMaker_Deployment.git)<br>
Install all the dependencies.

## Delete the Endpoint
Remember to always SHUT DOWN YOUR ENDPOINT if you are no longer using it. You are charged for the length of time that the endpoint is running so if you forget and leave it on you could end up with an unexpectedly large bill.

	predictor.delete_endpoint()
