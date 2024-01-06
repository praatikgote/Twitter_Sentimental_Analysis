# Twitter Sentiment Analysis using Python

## Overview
This project focuses on sentiment analysis of Twitter data, classifying tweets into positive, negative, or neutral sentiments. The analysis is performed using a Logistic Regression classification model implemented in Python.

## Dataset
The project utilizes the [Sentiment140 dataset](https://www.kaggle.com/datasets/kazanova/sentiment140) from Kaggle, which contains 1.6 million tweets labeled with sentiment (positive or negative). The dataset is a valuable resource for training and evaluating sentiment analysis models.

## Key Features
- **Sentiment Classification:** Utilized a Logistic Regression model to classify tweets based on sentiment.
- **Text Preprocessing:** Applied text preprocessing techniques, including removal of stop words and stemming using NLTK.
- **Collaborative Development:** Developed the project using Google Colab for efficient collaboration and streamlined workflow.
- **Evaluation Metric:** Assessed model performance using accuracy_score, achieving accurate sentiment predictions.

## Libraries and Tools
- Python
- NumPy
- pandas
- Google Colab
- NLTK (Natural Language Toolkit)
- Scikit-learn

## Project Structure
- **`notebooks/`:** Contains Jupyter notebooks used for data exploration, preprocessing, and model training.
- **`data/`:** Includes datasets used for training and testing the model. (Note: Download the Sentiment140 dataset from [Kaggle](https://www.kaggle.com/datasets/kazanova/sentiment140) and place it in this directory.)
- **`src/`:** Houses source code files, including Python scripts for data preprocessing and model implementation.

## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/praatikgote/Twitter_Sentimental_Analysis.git
   cd Twitter_Sentimental_Analysis
