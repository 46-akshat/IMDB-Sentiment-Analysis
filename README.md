**IMDB Sentiment Analysis with LSTM**

This project uses TensorFlow Keras to classify IMDB movie reviews as either positive or negative. The model is built with an LSTM layer to capture contextual information from the review text.

Installation
Clone the repository:

bash
Copy code
git clone <repository_url>
Navigate to the project directory:

bash
Copy code
cd imdb-sentiment-analysis
Install dependencies:

bash
Copy code
pip install tensorflow keras
Run the script:

bash
Copy code
python imdb_sentiment_analysis.py
Model Overview
Embedding Layer: Converts words into dense vectors.
LSTM Layer: Captures long-range dependencies.
Dense Layer: Outputs sentiment (positive/negative).

