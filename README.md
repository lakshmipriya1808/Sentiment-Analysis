# Sentiment Analysis on IMDB Reviews

## 📌 Overview
This project focuses on classifying movie reviews as positive or negative using Natural Language Processing (NLP) and Machine Learning techniques.

It explores how text data can be preprocessed, transformed, and used to train different classification models.

---

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- NLTK
- Matplotlib, Seaborn

---

## 🧠 Approach

### 1. Data Preparation
- Used IMDB dataset (~35,000 reviews)
- Created:
  - Imbalanced dataset (9000 positive, 1000 negative)
  - Balanced dataset using RandomUnderSampler

### 2. Text Preprocessing
- Removed stopwords using NLTK
- Cleaned and processed text data

### 3. Visualization
- Generated word clouds for:
  - All reviews
  - Positive reviews
  - Negative reviews

### 4. Feature Extraction
- Used TF-IDF Vectorizer to convert text into numerical features

### 5. Model Training
Trained multiple machine learning models:
- Support Vector Machine (SVM)
- Logistic Regression
- Decision Tree
- Naive Bayes

---

## 📈 Results

| Model                | Accuracy |
|---------------------|---------|
| SVM                 | 94%     |
| Logistic Regression | 91%     |
| Decision Tree       | 88%     |
| Naive Bayes         | 83%     |

- SVM performed the best among all models  
- Compared model performance on both balanced and imbalanced datasets  

---

## 📊 Evaluation
- Accuracy score
- Confusion Matrix

---

## 📂 Dataset
IMDB Movie Reviews Dataset  
(Dataset not included due to size. Can be downloaded from Kaggle)

---

## 💡 Example Prediction
Input: "I loved this movie"
Output: Positive

Input: "Worst movie ever"
Output: Negative

---

## ✏️ My Contribution
- Implemented full NLP pipeline from preprocessing to model evaluation  
- Handled class imbalance using undersampling techniques  
- Compared multiple ML models and analyzed their performance  
- Visualized text data using word clouds  

---

## 🔗 References
- Some parts of the implementation were adapted from online tutorials and learning resources
