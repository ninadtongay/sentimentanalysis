# Sentiment Analysis deployed using SageMaker Project

The notebook and Python files provided here which result in a simple web app which interacts with a deployed recurrent neural network performing sentiment analysis on movie reviews. This project assumes some familiarity with SageMaker, the mini-project, Sentiment Analysis using XGBoost, should provide enough background.

Steps to do:
1. Downloading the data
2. Preparing and Processing the data
3. Upload the data to S3
4. Build and Train the PyTorch Model
5. Testing the Model
6. Deploying the model for testing
7. Use the model for testing
6. Deploy the model for the web app
7. Use the model for the web app

Always make sure to delete your endpoints if you are no longer using it. You will be charged for the length of time the endpoint is running.

Run this command to delete the endpoint: predictor.delete_endpoint()
