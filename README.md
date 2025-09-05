# 📰 Fake News Detection with Machine Learning  

## 📌 Project Overview  
This project explores how machine learning can help identify fake news circulating on social media platforms. Using **natural language processing (NLP)** techniques and a **Support Vector Machine (SVM) classifier**, the model classifies articles as either *factual* or *fake*.  

The notebook walks through:  
- Data cleaning and preprocessing  
- Exploratory data analysis (EDA)  
- Feature extraction using text vectorization  
- Training and evaluating an SVM classifier  
- Visualizing model performance  
- Discussing how these findings could be communicated to stakeholders  

---

## 📊 Results  
The trained model achieved:  

- **Accuracy:** ~80%  
- **F1 Score:** ~0.80  
- **Precision/Recall balance:**  
  - Factual News → Precision: 0.81 | Recall: 0.76  
  - Fake News → Precision: 0.79 | Recall: 0.84  

Example classification report:  
               precision    recall  f1-score   
Factual News   0.81         0.76    0.79
Fake News      0.79         0.84    0.81

accuracy                           0.80



Key takeaway: The model is slightly better at detecting fake news than confirming factual news.  

---

## 📈 Visualizations  
The notebook includes plots and metrics such as:  
- **Confusion Matrix** to visualize classification errors  
- **Precision/Recall/F1 bar charts**  
- **Word frequency distributions** for fake vs factual news  

---




