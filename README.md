# Sentiment Analysis on IMDB Reviews

This project demonstrates how to build a sentiment analysis model using the IMDB Reviews dataset. The model classifies movie reviews as positive or negative based on the text input. The steps include text preprocessing, feature engineering, model training, and evaluation.

## Steps Involved:
DataSet link: https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews
1. **Text Preprocessing:**
   - **Tokenization:** Splitting the text into individual words.
   - **Stopword Removal:** Removing common words (e.g., 'the', 'and', 'is') that do not contribute to the meaning of the sentence.
   - **Lemmatization:** Converting words to their base or root form (e.g., "running" to "run").

2. **Feature Engineering:**
   - **TF-IDF:** Convert the text data into numerical format using Term Frequency-Inverse Document Frequency (TF-IDF).
   - Alternatively, word embeddings can be used to represent the text data numerically.

3. **Model Training:**
   - **Classifier:** A machine learning model (Logistic Regression or Naive Bayes) is used to predict sentiment (positive or negative).
   - The model is trained on the preprocessed data and tested for accuracy.

4. **Model Evaluation:**
   - **Metrics:** The model's performance is evaluated using precision, recall, and F1-score.

## Dependencies

Make sure to install the following libraries for the project:

- Python 3.x
- `pandas`
- `numpy`
- `scikit-learn`
- `nltk`
- `matplotlib`

To install the dependencies, run:

```bash
pip install pandas numpy scikit-learn nltk matplotlib
