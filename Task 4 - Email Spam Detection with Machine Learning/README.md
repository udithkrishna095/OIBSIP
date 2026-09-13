# Task 4 - Email Spam Detection with Machine Learning

## Objective

Build a Machine Learning model using Natural Language Processing (NLP) to classify messages as **Spam** or **Ham (legitimate)**.

## Dataset

The project uses the **SMS Spam Collection dataset**, containing messages labelled as spam or ham.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK / Regular Expressions
- Matplotlib
- Seaborn
- WordCloud
- Jupyter Notebook

## Project Workflow

1. Load and inspect the dataset.
2. Check spam and ham class distribution.
3. Handle missing values and duplicate messages.
4. Preprocess text by converting it to lowercase and removing punctuation and unnecessary characters.
5. Use **TF-IDF Vectorization** to convert text into numerical features.
6. Split the data into training and testing sets.
7. Train two classification models:
   - Multinomial Naive Bayes
   - Logistic Regression
8. Evaluate the models using:
   - Accuracy
   - Precision
   - Recall
   - F1-score
   - Confusion Matrix
9. Compare the performance of both models.
10. Visualize common words in spam and ham messages using WordCloud.

## Machine Learning

**TF-IDF** converts text messages into numerical features based on the importance of words in the dataset.

**Multinomial Naive Bayes** is well suited for text classification.

**Logistic Regression** is used as a second classifier for comparison.

## Evaluation

The models are evaluated using accuracy, precision, recall, F1-score, and confusion matrices.

Recall is particularly important for spam detection because it shows how many actual spam messages are correctly identified.

## Result

Both models are capable of distinguishing spam messages from legitimate messages. The model with the higher F1-score is considered the better-performing model for this dataset.

## Conclusion

This project demonstrates how NLP, TF-IDF, and Machine Learning can be combined to build a spam detection system that automatically classifies messages as Spam or Ham.