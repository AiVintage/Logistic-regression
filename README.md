# 🌸 Iris Dataset – Logistic Regression Classifier

## 📌 Project Overview
This project applies **Logistic Regression** to classify whether a flower is **Iris-setosa** or **another Iris species**.  
We evaluate the model using **confusion matrix, accuracy, precision, and recall**, computed via both scikit-learn and manual calculations for reliability.  

---

## 📂 Dataset
- **Source:** Iris dataset (classic machine learning dataset)  
- **Features:** Sepal Length, Sepal Width, Petal Length, Petal Width  
- **Target:** Binary classification  
  - 0 = Iris-setosa  
  - 1 = Other Iris species  

**Sample data:**
| SepalLengthCm | SepalWidthCm | PetalLengthCm | PetalWidthCm | Species       |
|---------------|--------------|---------------|--------------|---------------|
| 5.1           | 3.5          | 1.4           | 0.2          | Iris-setosa   |
| 6.3           | 2.7          | 4.9           | 1.8          | Iris-virginica |

---

## ⚙️ Approach
1. **Data Preprocessing**
   - Converted categorical `Species` column into binary target.  
   - Split dataset: 75% training, 25% testing.  

2. **Model Training**
   - Logistic Regression classifier (`sklearn.linear_model.LogisticRegression`).  

3. **Evaluation**
   - Confusion matrix  
   - Accuracy, Precision, Recall (scikit-learn & manual)  

---

## 📊 Results
### Confusion Matrix
The confusion matrix shows perfect classification:  

![Confusion Matrix]  

### Performance Metrics
- **Accuracy:** 1.0  
- **Precision:** 1.0  
- **Recall:** 1.0  

✅ Both scikit-learn metrics and manual calculations matched, confirming model reliability.  

---

## ✅ Conclusion
- Logistic Regression achieved **perfect classification** on this dataset.  
- Results show the model can reliably distinguish **Iris-setosa** from other Iris species.  
- Metrics validation (manual vs sklearn) builds confidence in the evaluation pipeline.  

---

## 🚀 Future Improvements
- Extend to **multi-class classification** (Setosa, Versicolor, Virginica).  
- Compare with **Decision Trees** and **SVM** for performance benchmarking.  
- Visualize **decision boundaries** for better interpretability.  

---

## 🛠️ Tech Stack
- **Language:** Python  
- **Libraries:** pandas, scikit-learn, matplotlib, seaborn  

---

## 👨‍💻 Author
**AiVintage (Veli)**  
Data Science Graduate | Skilled in Python, Machine Learning, NLP, Data Analysis & Visualization, SQL  
[GitHub](https://github.com/AiVintage) | [LinkedIn](www.linkedin.com/in/veli-nhlapo-721351373)  
