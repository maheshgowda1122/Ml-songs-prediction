# 🎵 Song Popularity Prediction using Machine Learning
### Using Supervised & Unsupervised Learning (Jupyter Notebook Based)

---

## 📌 Project Overview
This project analyzes a Spotify tracks dataset to understand and predict song popularity using machine learning techniques.  
The workflow is implemented using multiple Jupyter Notebooks, each focusing on a specific research question.

---

## 📂 Dataset

| Field | Details |
|------|--------|
| **Dataset** | Spotify Tracks Dataset |
| **File** | tracks.csv |
| **Rows** | ~10,000 |
| **Features** | energy, tempo, valence, danceability, speechiness, liveness |
| **Target Variable** | popularity |

---

## 🧪 Research Questions

| Notebook | Research Question |
|----------|------------------|
| `RQ_1_assignment_ML.ipynb` | How important are different features in predicting popularity? |
| `RQ_2_ML_assignment.ipynb` | Which regression model performs best? |
| `RQ_3.ipynb` | How do emotional features affect popularity? |
| `RQ_4.ipynb` | Can we classify hit vs non-hit songs? |
| `RQ_5.ipynb` | Additional analysis / evaluation |
| `RQ_6.ipynb` | Can songs be grouped into clusters? |

---

## 🤖 Models Used
- Linear Regression  
- Random Forest Regressor  
- Random Forest Classifier  
- K-Means Clustering  

---

## 📊 Evaluation Metrics
- RMSE (Root Mean Squared Error)  
- R² Score  
- ROC Curve  
- AUC Score  

---

## 📁 Project Structure

```
project/
│── tracks.csv
│── RQ_1_assignment_ML.ipynb
│── RQ_2_ML_assignment.ipynb
│── RQ_3.ipynb
│── RQ_4.ipynb
│── RQ_5.ipynb
│── README.md
```

---

## 🚀 How to Run

### 1. Install dependencies
```
pip install pandas numpy matplotlib seaborn scikit-learn
```

### 2. Start Jupyter
```
jupyter notebook
```

### 3. Run notebooks in order
1. RQ1  
2. RQ2  
3. RQ3  
4. RQ4  
5. RQ5  

---

## 📁 Outputs
- RQ2_model_results.csv  
- RQ3_emotional.pdf  
- RQ4_roc.pdf  
- RQ6_clusters.pdf  

---

## 📈 Key Insights
- Predicting song popularity is challenging  
- Emotional features alone are weak predictors  
- Random Forest performs slightly better than Linear Regression  
- Clustering reveals hidden patterns  

---

## 📌 Conclusion
Machine learning models help uncover patterns in music data, but popularity depends on multiple external factors beyond audio features.

---


