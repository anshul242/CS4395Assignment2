# CS4395 Assignment 2: Neural Networks for Sentiment Analysis

This project implements two neural network architectures for sentiment analysis on Yelp reviews:
- Feedforward Neural Network (FFNN)
- Recurrent Neural Network (RNN)

The task is to predict star ratings (1-5) based on review text.

## Files
- ffnn.py: Implementation of the Feedforward Neural Network
- rnn.py: Implementation of the Recurrent Neural Network
- CS4395_Assignment2_Report.pdf: Detailed report of implementations and results

## Running the code

### FFNN:
```
python ffnn.py --hidden_dim 100 --epochs 1 --train_data ./training.json --val_data ./validation.json
```

### RNN:
```
python rnn.py --hidden_dim 128 --epochs 10 --train_data ./training.json --val_data ./validation.json
```

## Requirements
- Python 3.8.x
- PyTorch 1.10.1
- NumPy
- tqdm
- pickle
