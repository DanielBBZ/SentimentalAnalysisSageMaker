# Deploying a Sentiment Analysis Model on AWS

## Project Overview

This project is derived from a course work from Udacity Machine Learning Nanodegreee. The purpose of this project is to use Amazon SageMaker to complete end to end machine learning project, and build a simple web page in which a user can input a movie review and the model behind the scenes will predict whether it's Positive or Negative.

Please see the [README](https://github.com/udacity/sagemaker-deployment/tree/master/README.md) in the root directory for instructions on setting up a SageMaker notebook and downloading the project files (as well as the other notebooks).

### General Outline

- Step 1: Downloading the data
- Step 2: Preparing and Processing the data
- Step 3: Upload the data to S3
- Step 4: Build and Train the PyTorch Model
- Step 5: Testing the Model
- Step 6: Deploying the model for testing
- Step 7: Use the model for testing
- Step 6  Deploy the model for the web app
- Step 7  Use the model for the web app

### Libraries

The list below represents main libraries and its objects
for the project.
- [Amazon SageMaker](https://ap-northeast-2.console.aws.amazon.com/sagemaker/home?region=ap-northeast-2#/landing) (Build, train, and deploy a model)
- [tensorflow](https://www.tensorflow.org/) (LSTM classifier)
