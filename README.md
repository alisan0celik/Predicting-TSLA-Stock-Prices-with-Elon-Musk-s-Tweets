# Predicting-TSLA-Stock-Prices-with-Elon-Musk-s-Tweets
This project utilizes a fine-tuned BERT model to predict TSLA (Tesla) stock prices based on tweets from Elon Musk. The repository includes two Jupyter Notebooks:

## 1. Training the Model

#### Dependencies
sqlite3

pandas

scikit-learn

transformers

torch

## Usage
Open and run the first notebook cell to train the model and save it.

Open and run the second notebook cell to load the model and make predictions for new tweets from Elon Musk.

### Additional Notes

Some weights of the model checkpoint at bert-base-uncased might not be used, as indicated during initialization. This is expected behavior.

Ensure that the SQLite database (twitterTesla.db) contains the necessary data for Elon Musk's tweets and TSLA stock prices.

Adjust the number of training epochs in the training notebook as needed.

Feel free to run these notebooks to train the model and make predictions based on new tweets from Elon Musk.
