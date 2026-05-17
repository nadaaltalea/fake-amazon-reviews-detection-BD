# 🚀 Fake Amazon Reviews Detection using Big Data Analytics

## 📌 Project Overview
This project presents a scalable solution for detecting fake Amazon reviews using Big Data Analytics, Machine Learning, and Natural Language Processing (NLP). The system is implemented using PySpark to handle large-scale data efficiently.

The goal is to classify reviews as **Real (0)** or **Fake (1)** by combining textual, numerical, and behavioral features.

---

## 🎯 Objectives
- Automatically detect fake reviews in large datasets  
- Analyze patterns and relationships in review data  
- Compare multiple machine learning models  
- Build a scalable pipeline using PySpark  

---

## 📊 Dataset Description
- **Size:** 50,000 Amazon reviews  
- **Features:**
  - Rating  
  - Review text  
  - Helpful votes  
  - Verified purchase  
- **Label:**
  - `0 → Real Review`
  - `1 → Fake Review`

✅ The dataset is **balanced**, improving model reliability.

---

## ⚙️ Technologies Used
- 🐍 Python  
- ⚡ PySpark  
- 🤖 Machine Learning  
- 🧠 NLP (TF-IDF)  
- 📊 Matplotlib / Seaborn  

---

## 🧠 Methodology

### 1️⃣ Data Preprocessing
- Removed null values  
- Converted data types  
- Selected relevant features  

### 2️⃣ Feature Engineering
- Combined title + text  
- Calculated review length  
- Processed verified purchase  

### 3️⃣ NLP Pipeline
- Tokenization  
- Stop-word removal  
- TF-IDF transformation  

### 4️⃣ Model Training
- Logistic Regression  
- Decision Tree  
- Naive Bayes  
- Random Forest  

### 5️⃣ Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1-score  

---

## 📈 Model Performance

| Model | Accuracy | F1-score |
|------|--------|--------|
| Logistic Regression | 0.698 | 0.698 |
| Decision Tree ⭐ | 0.843 | 0.841 |
| Naive Bayes | 0.675 | 0.675 |
| Random Forest | 0.794 | 0.791 |

🏆 **Best Model: Decision Tree**

---

## 📊 Visualizations

### 🔹 Confusion Matrix
![Confusion Matrix](images/confusion_matrix.png)

### 🔹 Correlation Heatmap
![Heatmap](images/heatmap.png)

### 🔹 Model Comparison
![Model Comparison](images/model_comparison.png)

---

## 🔍 Key Insights
- Fake reviews are difficult to detect due to similarity with real reviews  
- No single feature is sufficient for classification  
- Combining features significantly improves performance  
- Decision Tree captured complex patterns effectively  

---

## 🧪 Live Demonstration
The model can classify new reviews using the trained PySpark pipeline.

Example:
- Input: New review text  
- Output:  
  - Prediction (Real / Fake)  
  - Probability score  

---

## ⚠️ Limitations
- Some fake reviews are misclassified due to realistic writing  
- Model performance depends on feature quality  
- Deep semantic understanding is limited  

---

## 🚀 Future Work
- Apply deep learning models (BERT, LSTM)  
- Implement real-time detection (Spark Streaming)  
- Improve feature engineering techniques  

---

## 📂 Project Structure
