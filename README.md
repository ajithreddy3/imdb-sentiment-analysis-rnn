# imdb-sentiment-analysis-rnn
# IMDB Sentiment Analysis using PyTorch RNN

This project implements a **sentiment analysis model for movie reviews** using the IMDB dataset.  
The pipeline includes **text preprocessing, TF-IDF vectorization, and a Recurrent Neural Network (RNN) implemented in PyTorch** for binary sentiment classification.

The model predicts whether a movie review is **positive or negative**.

---

## Dataset

Dataset used: **IMDB Movie Reviews Dataset**

- 50,000 movie reviews
- Binary sentiment labels:
  - Positive
  - Negative

Each review is processed and converted into numerical features before being passed into the neural network.

---
## Architecture
TF-IDF Input Features
        ↓
Recurrent Neural Network (RNN)
        ↓
Fully Connected Layer
        ↓
Sigmoid Activation
        ↓
Binary Sentiment Output


---

## Technologies Used

- Python
- PyTorch
- Scikit-learn
- Pandas
- NumPy
- NLTK

---

