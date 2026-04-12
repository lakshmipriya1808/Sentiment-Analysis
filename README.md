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
  Example -
  **Positive Reviews** - <img width="790" height="425" alt="image" src="https://github.com/user-attachments/assets/3aeead90-b064-4873-86bf-f489573f089d" />
  **Negative Reviews** - <img width="790" height="425" alt="image" src="https://github.com/user-attachments/assets/a16c23a9-9ab5-4570-b142-d1050fb3f521" />



### 4. Feature Extraction
- Used TF-IDF Vectorizer to convert text into numerical features

### 5. Model Training
Trained multiple machine learning models:
- Support Vector Machine (SVM)
- Logistic Regression
- Decision Tree
- Naive Bayes

---

## 📈 Results & Evaluation

| Model                | Accuracy |
|---------------------|---------|
| SVM                 | 94%     |
| Logistic Regression | 91%     |
| Decision Tree       | 88%     |
| Naive Bayes         | 83%     |

- SVM performed the best among all models  
- Compared model performance on both balanced and imbalanced datasets  
- Confusion Matrix
  <img width="532" height="449" alt="image" src="https://github.com/user-attachments/assets/5f4146ad-00f9-474c-ab80-58d8c1f8c9e8" />


---

## 📊 Key Insights

- The dataset showed a higher proportion of positive reviews, indicating overall favorable sentiment trends  
- Text analysis revealed distinct word patterns for positive and negative sentiments  
- Class imbalance significantly affected model performance, which was improved after applying undersampling  
- SVM achieved the highest accuracy (94%), making it the most suitable model for this task  
- This approach can be applied to analyze customer feedback and improve decision-making

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
