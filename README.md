# Spam-Classification
## Objective
The goal of this exercise is to classify messages as either spam or ham using Natural Language Processing techniques. You will preprocess the text data, apply feature extraction methods, train a machine learning model, and evaluate its performance.
_______________________________________________________________________________________________________________________________________________________________________
## Explanation of the Dataset Columns
•	Class: The label indicating whether the message is ham (not spam) or spam.

•	Message: The actual content of the message.
_______________________________________________________________________________________________________________________________________________________________________
## Steps to Follow
1. Data Loading
- Load the sample dataset into a Pandas DataFrame.
- Inspect the first few rows to understand the structure of the data.
- Check for any missing or null values and handle them appropriately.
  
2. Text Preprocessing
Preprocess the text data to make it suitable for machine learning:

- Lowercasing: Convert all text to lowercase to ensure uniformity.
- Remove Punctuations and Special Characters: Use regular expressions to clean the text.
- Stop Word Removal: Eliminate common words (like "and", "the") that do not contribute much to the analysis.
- Tokenization: Split the text into individual words or tokens.
- Lemmatization: Reduce words to their base form to unify different word forms (e.g., "running" -> "run").
- 
3. Feature Extraction
Convert the preprocessed text into a numerical format suitable for machine learning:

- Bag of Words (BoW): Create a matrix where each row represents a message and each column represents a word. The value in each cell is the count or frequency of the word in the respective message.
- TF-IDF: Apply Term Frequency-Inverse Document Frequency to highlight the importance of unique words in each message.

4. Model Training
- Split the dataset into training and testing sets (e.g., 80% training, 20% testing).
- Train a machine learning model:
  algorithms: Logistic Regression, Naive Bayes, or Random Forest.
- Fit the model to the training data using the extracted features.
  
5. Prediction
- Use the trained model to predict whether new messages are ham or spam.
- Store the predictions for evaluation.
  
6. Evaluation
Confusion Matrix: To understand how well the model correctly identifies spam and ham messages.
_______________________________________________________________________________________________________________________________________________________________________

## 📁 Repository Structure

Spam CLassification/<br>
|<br>
├── data/<br>
|      └── Spam_SMS<br>
|<br>
├── main/<br>
|      └── Spam_Classification_code.ipynb<br>
|<br>
└── README.md<br>






