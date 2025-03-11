# Language Detection Model using NLP - CountVectorizer and Naive Bayes

## Project Overview
This project implements a Language Detection Model using Natural Language Processing (NLP) techniques. The model utilizes **CountVectorizer** to convert text into a bag-of-words representation and uses the **Naive Bayes** classifier to predict the language of a given text.

## Requirements

Before running the project, make sure you have Python 3.x installed along with the following libraries:

- `scikit-learn` (for machine learning algorithms)
- `pandas` (for data manipulation)
- `numpy` (for numerical computations)
- `nltk` (for natural language processing)

You can install the required libraries using `pip`:

```bash
pip install scikit-learn pandas numpy 
```


### Key Steps Included:
1. **Data Preparation**: The dataset should be in CSV format with labeled text data.
2. **Model Training**: Use `CountVectorizer` to convert text data into numerical vectors and train a Naive Bayes model.
3. **Model Evaluation**: After training, the model's accuracy is evaluated on the test set.
4. **Prediction**: The trained model can predict the language of unseen text inputs.
5. **Saving Models**: You can save both the trained Naive Bayes model and `CountVectorizer` for later use.

