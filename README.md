# NLP Disaster Tweets Classification Project
Mini-project for a Kaggle competition on classifying disaster tweets, link below

https://www.kaggle.com/competitions/nlp-getting-started/submissions

## Project Description
This project builds a machine learning model to classify tweets as either real disasters or non-disasters. Using Natural Language Processing techniques, I developed a simple neural network model that achieved a Kaggle score of 0.77137.

## Dataset
- Training set: 7,613 labeled tweets
- Test set: roughly 10,900 tweets
- Features: tweet text, keywords, location
- Target: Binary classification (disaster/non-disaster)

## Implementation
- Text preprocessing and TF-IDF vectorization
- Neural network with dropout layers
- Class weight balancing for improved performance

## Results
- Validation Accuracy: 77.48%
- Kaggle Score: 0.77137

## Files
- `nlp_disaster_tweets.ipynb`: Main project notebook
- `submission.csv`: Kaggle submission file
- `data/`: Contains training and test datasets

## Requirements
- Python 3.x
- TensorFlow/Keras
- Scikit-learn
- Pandas
- NumPy