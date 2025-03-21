# Artificial-Intellegence
Process and Concepts Followed
1. Data Import and Exploration
Loaded SMS dataset for spam detection.
Explored dataset to understand class distribution (spam vs. ham).
Checked for missing values and inconsistencies.
2. Data Preprocessing
Text Cleaning:
Converted text to lowercase.
Removed punctuation, stopwords, and special characters.
Applied tokenization to break messages into words.
Used stemming/lemmatization for word normalization.
3. Feature Engineering
Used Bag of Words (BoW) to create word count vectors.
Applied TF-IDF (Term Frequency-Inverse Document Frequency) to weigh words based on importance.
4. Model Selection & Training
Split data into training and testing sets.
Experimented with machine learning models:
Naïve Bayes (good for text classification).
Logistic Regression.
Support Vector Machines (SVM).
Trained and tested models to classify SMS messages as spam or ham.
5. Model Evaluation
Used accuracy, precision, recall, and F1-score for performance assessment.
Plotted confusion matrices to visualize classification results.
6. Deployment Considerations
Possible real-world applications: Spam detection in messaging apps, email filtering, fraud prevention.

