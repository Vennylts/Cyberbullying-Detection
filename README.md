# Augmenting Cyberbullying Detection with Machine Learning and NLP
This project addresses the challenges in predicting cyberbullying instances in digital text content using machine learning algorithm, methodology and Natural Language Processing (NLP).

## Project Aim
The proposed solution aims to augment current detection methods (e.g., raditional rule-based systems & human judgment limitation) by providing a more nuanced and context-aware understanding of potential cyberbullying incidents.

## Project Objectives
1. To conduct a review of existing literature on cyberbullying detection to understand the range of methodologies currently in use, the strengths and limitations of these methods, and the gaps in the existing research.
2. To examine the application of ML and NLP techniques in related fields such as spam detection, sentiment analysis, and text classification, and to evaluate the relevance and applicability of these techniques for cyberbullying detection.
3. To reimplement cyberbullying detection models using sets of selected ML and NLP techniques 
from the literature. 
4. To evaluate and compare the effectiveness of the reimplemented methods in detecting cyberbullying in a controlled test environment, using a common dataset and established performance metrics.

## Key Features
- **Dataset:**
  - **Source:** https://www.kaggle.com/code/andrewmvd/cyberbullying-classification-getting-started/notebook
  - "Cyberbullying Classification" dataset on Kaggle.
  - Records online bullying and non-bullying remarks on Twitter.
  - 47692 tweets
  - Collected using Twitter API and manually classified into 6 instances by the author.
- **Methodology:**
  - **Experimental Design:** Three experiments are conducted using the same sets of preprocessing methods and text representation, but with different classification algorithms.
  - **Pre-processing methods:**
    - Data cleaning
      - Label Encoding
      - Lowercasing
      - Stopword Removal
      - Punctuation Removal
      - URL Removal
      - Numeric Removal
    - Tokenization
    - Stemming
    - Lemmatization
  - **Text Representation:**
    - Bag-of-Words
    - Word Embedding (Word2Vec)
    - TF-IDF
  - **Models:** 
    - **Experiment 1:** Support Vector Machine (SVM)
    - **Experiment 2:** Logistic Regression
    - **Experiment 3:** Random Forest Classifier
  - **Evaluation metrics:**
    - Accuracy, Precision, Recall, F1-Score, Confusion Matrix
- **Performance:**
  - **Benchmark Model (Random Forest with TF-IDF):** 98.5%
  - **Best Performance from the Experiment:**
    - **Logistic Regression (Bag of Word):** 82%
