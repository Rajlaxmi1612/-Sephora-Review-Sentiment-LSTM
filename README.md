# Sentiment Analysis of Sephora Product Reviews using LSTM

A deep learning project that classifies beauty and skincare product reviews as positive or negative using an LSTM neural network.

## Problem Statement
Online stores receive thousands of reviews, and reading them manually is slow. This project automatically detects whether a customer review is positive or negative, which helps brands understand customer feedback at scale.

## Dataset
- **Source:** Sephora Products and Skincare Reviews (Kaggle)
- **Used:** customer review text and ratings, converted into positive/negative sentiment labels
- [Add: number of reviews used and how you created the labels, e.g. rating 4-5 = positive]

## Approach
1. **Data cleaning:** [e.g. removed missing values, lowercased text, removed punctuation]
2. **Tokenization and padding:** converted review text into number sequences of equal length
3. **Model:** LSTM network with [embedding layer, LSTM layer, dense output layer, adjust to your notebook]
4. **Training:** [epochs, batch size, train/test split]
5. **Prediction:** the model can classify any custom review typed by the user

## Results
- **Test accuracy: 93.8%**

## Example Predictions
| Review | Predicted Sentiment |
|---|---|
| "[positive review you tested]" | Positive |
| "[negative review you tested]" | Negative |

## Tools Used
Python, [TensorFlow/Keras, Pandas, NumPy, Matplotlib, adjust to your notebook]

## Notebook
[Kaggle Notebook](PASTE-YOUR-KAGGLE-LINK-HERE)

## Author
Rajlaxmi Ghadi | [LinkedIn](https://www.linkedin.com/in/rajlaxmi-ghadi-a09770294) | [GitHub](https://github.com/Rajlaxmi1612)
