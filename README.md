# Artificial-Intellegence
## INTRODUCTION
With the rise of SMS and messaging apps, spam messages have become a major concern, leading to fraud and clutter. This project aims to build an NLP-based machine learning model to classify SMS as Spam or Ham, using text preprocessing, feature engineering, and classification algorithms for efficient spam detection.
## Tools & Libraries Used

- **Data Handling:**
  - `pandas` – For data manipulation
  - `numpy` – For numerical operations
- **Text Preprocessing:**
  - `nltk` – For stopword removal and tokenization
  - `re` – For regex-based text cleaning
- **Machine Learning Models:**
  - `Naïve Bayes`
  - `Logistic Regression`
  - `Support Vector Machine (SVM)`

## Steps Followed  

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


