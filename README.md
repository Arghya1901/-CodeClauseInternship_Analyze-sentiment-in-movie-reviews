<p align="center">
  <img src="SentimentAnalysis_image.jpg" alt="Sentiment Analysis Output" width="600"/>
</p>

# 🎬 **SENTIMENT ANALYSIS IN MOVIE REVIEWS**


## 🧾 **PROJECT DESCRIPTION**
*Perform sentiment analysis on a dataset of movie reviews to classify them as positive or negative.*

This project uses **Natural Language Processing (NLP)** techniques to clean the text, convert it into numerical format, and apply machine learning models for binary classification.

---


## 📚 **TABLE OF CONTENTS**
- 📌 **Project Title**
- 🧾 **Project Description**
- 📚 **Table of Contents**
- 📊 **Dataset Information**
- 🛠️ **Tech Stack Used**
- 🧠 **Workflow & Methodology**
- 📈 **Model Performance**
- 🧪 **How to Use**
- 🏁 **Results**
- 🚀 **Future Improvements**
- 👥 **Contributors**
- 📝 **License**

---


## 📊 **DATASET INFORMATION**
- **Name**: *IMDb Movie Reviews Dataset*
- **Source**: [Kaggle - IMDb Dataset of 50K Movie Reviews](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)
- **Format**: CSV  
- **Total Records**: 50,000 movie reviews  
- **Data Split**:
  - 25,000 reviews for training  
  - 25,000 reviews for testing  
- **Columns**:
  - `review`: The full text of the movie review.
  - `sentiment`: The sentiment label for the review — either `"positive"` or `"negative"`.

📌 This dataset is **balanced**, meaning it contains an equal number of positive and negative reviews.

---

## 🛠️ **TECH STACK USED**
- **Programming Language**: 🐍 *Python 3*
- **Libraries & Tools**:
  - `pandas`, `numpy`
  - `matplotlib`, `seaborn`
  - `nltk`, `re`
  - `scikit-learn`
  - `TfidfVectorizer`
  - `LogisticRegression`

---


## 🧠 **WORKFLOW & METHODOLOGY**
1. **Load and Inspect Data**
2. **Text Preprocessing**:
   - Lowercasing  
   - Removing special characters, numbers, punctuation  
   - Stopword removal  
   - Tokenization  
   - Lemmatization  
3. **Feature Extraction**: *TF-IDF Vectorization*
4. **Model Training**:
   - Logistic Regression  
   - Random Forest Classifier  
5. **Model Evaluation**:
   - Confusion Matrix  
   - Accuracy Score  
   - Classification Report

---


## 📈 **MODEL PERFORMANCE**
| Model                | Accuracy |
|---------------------|----------|
| Logistic Regression | ~90%     |


---


## 🧪 **HOW TO USE**
- Open the notebook: `Sentiment_Analysis_In_Movie_Reviews.ipynb`  
- Run the cells sequentially  
- Observe preprocessing, training, and evaluation steps  
- Test with custom phrases for prediction

---


## 🏁 **RESULTS**
- ✔️ Successfully classified movie reviews into *positive* and *negative* sentiments  
- ✔️ Achieved over **90% accuracy** with Logistic Regression  
- ✔️ Found **TF-IDF features** more effective than simple Bag of Words

---


## 👥 **AUTHOR**
- **Arghya Chakraborty** 

---
