IMDB Sentiment Analysis using LSTM (TensorFlow Keras)
This project builds a sentiment analysis model to classify IMDB movie reviews as positive or negative. The model utilizes an LSTM (Long Short-Term Memory) layer, making it effective at capturing long-range dependencies in text data, allowing for better understanding of context and sentiment in movie reviews.

Features
Text Preprocessing: Tokenization and padding of movie reviews.
Model Architecture: Sequential model with an embedding layer, LSTM layer, and dense layer.
Sentiment Classification: Binary classification (positive/negative) based on review content.
IMDB Dataset: Trained and tested on the IMDB movie review dataset.
Getting Started
Prerequisites
Python 3.x
TensorFlow 2.x
Keras
Jupyter Notebook (optional, for running the project interactively)
Installation
Clone the repository:

bash
Copy code
git clone <repository_url>
Install the required libraries:

bash
Copy code
pip install tensorflow keras
Run the project:

bash
Copy code
python imdb_sentiment_analysis.py
Model Details
Embedding Layer: Transforms input words into dense vectors.
LSTM Layer: Captures long-term dependencies and context from the review text.
Dense Layer: Outputs the final sentiment prediction (positive or negative).
Dataset
The project uses the IMDB movie reviews dataset, which is a collection of 50,000 movie reviews labeled as positive or negative.
