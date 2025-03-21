# Artificial-Intellegence
# SMS Spam Classification using NLP  

## 1. Introduction  
With the increasing use of SMS and messaging applications, spam messages have become a significant issue, often leading to fraud, phishing attacks, and unnecessary clutter. The goal of this project is to develop a **machine learning model** to classify SMS messages as **Spam (Unwanted messages) or Ham (Genuine messages)** using **Natural Language Processing (NLP)** techniques.  

By applying **text preprocessing, feature engineering, and classification algorithms**, we aim to build an efficient spam detection system.  

---

## 2. Tools & Libraries Used  

### **Data Handling & Processing:**  
- `pandas` – For loading and handling the dataset  
- `numpy` – For numerical operations  

### **Text Preprocessing & Feature Engineering:**  
- `nltk` – For stopword removal, tokenization, stemming, and lemmatization  
- `re` – For regular expressions (text cleaning)  
- `sklearn.feature_extraction.text` – For Bag of Words (BoW) and TF-IDF transformation  

### **Machine Learning Models:**  
- `sklearn.naive_bayes` – Naïve Bayes classifier (suitable for text classification)  
- `sklearn.linear_model` – Logistic Regression  
- `sklearn.svm` – Support Vector Machines (SVM)  

### **Model Evaluation:**  
- `sklearn.metrics` – Accuracy, Precision, Recall, F1-score, and Confusion Matrix  

---

## 3. Steps Followed  

### **Step 1: Data Collection & Exploration**  
- Imported and analyzed the dataset containing SMS messages labeled as **Spam or Ham**.  
- Checked for missing values, imbalanced data, and message length distribution.  

### **Step 2: Text Preprocessing**  
- Converted text to **lowercase** for uniformity.  
- Removed **punctuation, special characters, and stopwords** to retain meaningful words.  
- Applied **tokenization** to split messages into words.  
- Used **stemming and lemmatization** to reduce words to their root form.  

### **Step 3: Feature Engineering**  
- Converted text into numerical vectors using:  
  - **Bag of Words (BoW)** – Word frequency-based representation.  
  - **TF-IDF (Term Frequency-Inverse Document Frequency)** – To weigh words based on importance.  

### **Step 4: Model Training**  
- Split the dataset into **training and testing sets** (e.g., 80% train, 20% test).  
- Trained different machine learning models:  
  - **Naïve Bayes** (best suited for text classification)  
  - **Logistic Regression**  
  - **Support Vector Machine (SVM)**  
- Tuned hyperparameters to optimize model performance.  

### **Step 5: Model Evaluation**  
- Used metrics like **Accuracy, Precision, Recall, and F1-score** to compare models.  
- Plotted a **Confusion Matrix** to analyze false positives and false negatives.  

---

## 4. Insights & Findings  

✅ **Naïve Bayes performed the best** in terms of accuracy and efficiency, making it a great choice for spam detection.  
✅ **TF-IDF outperformed BoW**, as it reduced the impact of commonly occurring words.  
✅ **Text preprocessing (removing stopwords, stemming, etc.) significantly improved accuracy.**  
✅ **Spam messages tend to have more links and special characters**, which can be leveraged for better classification.  
✅ **The model can be further improved** using deep learning (**LSTMs, Transformers**) or ensemble techniques.  




