# Sentiment Analysis using LSTM
## Table of Contents
- Introduction
- Data Source
- Features
- Installation
- Usage
- Project Structure
- Model Training
- Results
### Introduction
This project focuses on performing sentiment analysis on product reviews for Crista Spices. The sentiment analysis model utilizes Long Short-Term Memory (LSTM) to classify the sentiment (positive, negative, or neutral) of the reviews.
### Data Source
The data used in this project is sourced from product reviews of Crista Spices on Amazon. The dataset contains reviews and their corresponding sentiment labels.
### Features
- Sentiment analysis on product reviews
- Implementation of LSTM neural networks
- Visualization of sentiment classification results
### Installation
To install the necessary dependencies, run:
```python
git clone https://github.com/AMATI-TP-02/sentiment-analysis-ml.git
cd sentiment-analysis-ml
pip install -r requirements.txt
```
### Usage
To use the sentiment analysis model, run:
```python
python Sentiment_Analysis_on_Crista_Spices_Reviews.ipynb --data_path CristaSpices_ReviewsData.csv
```
### Project Structure
```python
sentiment-analysis-ml/
├── CristaSpices_ReviewsData.csv
├── CristaSpices_ReviewsData_Augmented.csv
├── CristaSpices_ReviewsModel.h5
├── CristaSpices_ReviewsModel.zip
├── NewCristaSpices_ReviewsData.csv
├── README.md
├── Sentiment_Analysis_on_Crista_Spices_Reviews.ipynb
```
### Model Training
To train the sentiment analysis model, run:
```python
python Sentiment_Analysis_on_Crista_Spices_Reviews.ipynb --train --data_path CristaSpices_ReviewsData.csv
```
### Results
The results of the model, including predictions and evaluation metrics, are saved in the following files:
- CristaSpices_ReviewsModel_Processed.h5: Contains the trained LSTM model in HDF5 format.
- CristaSpices_ReviewsModel_Processed.zip: Contains the TensorFlow.js version of the trained model for web deployment.
