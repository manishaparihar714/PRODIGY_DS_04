# PRODIGY_DS_04  
Task 4: **Sentiment Analysis on Social Media Data**  

This project analyzes and visualizes sentiment patterns in **Twitter social media data** to understand public opinion and attitudes towards specific topics or brands.  
The project demonstrates **data preprocessing, visualization, model training (Naive Bayes)**, and **evaluation with accuracy & confusion matrix**.  

---

## 🚀 Project Workflow
1. **Data Preprocessing**  
   - Loaded Twitter dataset (`twitter_training.csv`) from Prodigy InfoTech  
   - Removed missing/empty text values  
   - Selected relevant columns (sentiment, text)  
   - Split into training and testing sets  

2. **Exploratory Data Analysis (EDA)**  
   - Visualized sentiment distribution using bar charts  
   - Checked common patterns in text  

3. **Model Building**  
   - Converted text into numerical features using **Bag of Words (CountVectorizer)**  
   - Implemented **Naive Bayes Classifier (MultinomialNB)**  
   - Trained the model on training data  

4. **Evaluation**  
   - Generated **classification report** (precision, recall, F1-score)  
   - Plotted **confusion matrix heatmap**  
   - Visualized **per-class accuracy (bar chart)**  

---

## 📊 Visualizations
- **Sentiment Distribution Plot**  
  Shows the number of tweets for each sentiment (Positive, Negative, Neutral, Mixed).  

- **Confusion Matrix Heatmap**  
  Displays correct vs incorrect predictions of the model.  

- **Per-Class Accuracy Bar Plot**  
  Compares precision scores across different sentiment classes.  

---

## ⚙️ Tech Stack
- Python 🐍  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  

---

## 📈 Results
- The Naive Bayes classifier achieved a reasonable accuracy on the dataset.  
- **Insights:**  
  - Positive and Negative sentiments were predicted fairly well  
  - Neutral and Mixed sentiments were more challenging (class imbalance)  

---

