# Bulldozer-price-prediction-project

## Bulldozer Price Prediction Model
This Bulldozer Price Prediction Model was created using Scikit-Learn to participate in the Blue Book for Bulldozers competition, organized by Fast Iron on Kaggle. The goal of this competition is to predict the auction sale price of a piece of heavy equipment, such as bulldozers and excavators, based on factors like equipment usage, type, and configuration.

## Project Description
The model is trained on auction data provided by Fast Iron, which includes detailed information about each piece of equipment, such as its usage history, configuration, and additional specifications. The purpose is to assist Fast Iron in building a “blue book” for bulldozers, giving customers a reference point for valuing their heavy equipment fleet at auction.

## About Fast Iron
 Fast Iron specializes in helping clients create enterprise data standards and maintain high-quality data, particularly for the heavy equipment industry. With a data-cleansing team and proprietary applications, they’ve managed over 2.5 million records for machinery and customer information.

 ## Evaluation
 The competition uses RMSLE (Root Mean Squared Logarithmic Error) as the evaluation metric, measuring the accuracy of the predicted auction prices against actual sale prices. The final submission file must contain a header ("SalesID,SalePrice") and be formatted with the SalesID for each piece of equipment and the corresponding predicted sale price.

 ## Usage
 To use this model:
 1. Clone the repository:
    git clone https://github.com/yourusername/bulldozer-price-prediction.git
2. Install the necessary libraries:
   pip install -r requirements.txt
3. Load and preprocess the data as shown in the project documentation.
4. Train the model on the training set and make predictions on the test set.

## Model Performance
Following the contest’s guidelines and tuning hyperparameters, the model achieved [insert RMSLE or any other performance metric] on the validation set, indicating its reliability in predicting auction prices accurately.

## Timeline & Competition Details
The competition timeline included multiple phases from January 25 to April 17, 2013, allowing participants to train, validate, and test their models. The final leaderboard ranking is based on test set predictions submitted by the deadline.

## Citation
 Ben Hamner, Fast Iron 2, and FastIron. Blue Book for Bulldozers. Kaggle, 2013. [Competition Link](https://www.kaggle.com/competitions/bluebook-for-bulldozers)
