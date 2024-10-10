**IMDB Sentiment Analysis with LSTM**


This project uses TensorFlow Keras to classify IMDB movie reviews as positive or negative. It utilizes an LSTM-based model to capture context from text data for accurate sentiment analysis.

Features
Model: Sequential model with Embedding, LSTM, and Dense layers.
Dataset: IMDB dataset (50,000 labeled reviews).
Goal: Binary classification (positive/negative).

Installation
Prerequisites
Ensure you have the following installed:

Python 3.x
TensorFlow 2.x
Keras
Jupyter Notebook (optional, for interactive exploration)
Steps to Install
Clone the repository: Open a terminal and run the following command to clone the repository to your local machine:

bash
Copy code
git clone <repository_url>
Navigate to the project directory: Change into the project directory:

bash
Copy code
cd imdb-sentiment-analysis
Install required dependencies: Install the necessary libraries by running:

bash
Copy code
pip install tensorflow keras
Run the script: Execute the sentiment analysis script:

bash
Copy code
python imdb_sentiment_analysis.py
Model Architecture
The model consists of:

Embedding Layer: Converts words into dense vectors of fixed size.
LSTM Layer: Captures long-term dependencies in review text.
Dense Layer: Outputs the sentiment classification (positive/negative).
Dataset
The project uses the IMDB movie reviews dataset, which includes 50,000 labeled reviews, split equally into positive and negative sentiments.
