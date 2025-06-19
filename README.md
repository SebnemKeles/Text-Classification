# 📝 Topic Modelling and Classification


## 🧠 Project Summary

This project performs topic classification of news articles into 5 categories: business, entertainment, politics, sport, and tech. It leverages classical text processing and machine learning methods to build topic labellers that classify documents based on their content. The work is based on a simplified version of the BBC News dataset from Kaggle.


## 🔧 Tools & Libraries

- Python
- Numpy / pandas / NLTK / Scikit-learn
- Matplotlib / Seaborn
  

## 🚀 Workflow

1. **Preprocessing**
   - Tokenize, Lemmatize, Normalize
   - Histogram equalisation, Edge dedection

2. **Feature Extraction**
   - TF-IDF vectorization 
   - BoW vectorization 
     
3. **Model Training**
   - Logistic Regression
  
4. **Hyperparameter tuning**
   - GridSearchCV

5. **Evaluation**
   - Accuracy, Precision, Recall
   - Confusion Matrix 


## 🧪 Results

| Model                            | Accuracy 
|----------------------------------|----------
| Logistic Regression with TF-IDF  | 97%    
| Logistic Regression with BoW     | 95%    


## 📷 Visual Samples

![Confusion Matrix-tfidf](https://github.com/user-attachments/assets/9394fdc0-32c0-4f84-9c9b-40ef3bcb0ce5)
![Confusion Matrix-bow](https://github.com/user-attachments/assets/db4ab04c-4b1f-4ed7-b310-b04d7e091cd1)


## 💡 Future Improvements

Experiment with deep learning models for better feature representation.
Use more advanced preprocessing.
Explore ensemble methods combining multiple classifiers.


## ✅ Status

✔️ Completed (Academic Project)
This project was completed as part of the Image and Text Processing module in my MSc Data Science program.
