# 🩺 Breast Cancer Diagnosis Predictor

A **machine learning web app** built with **Streamlit** that predicts whether a breast mass is **benign** or **malignant** based on cell nuclei measurements from the **Breast Cancer Wisconsin dataset**.  
It uses a **Logistic Regression model** trained on the dataset to assist medical professionals in preliminary diagnosis.

---

## 🚀 Live Demo
👉 [View on Streamlit Cloud](https://mobahr98-breast-cancer-diagnosis.streamlit.app/)

---

## 📊 Features
- Interactive sliders for **30 cell nuclei features**  
- **Real-time ML predictions** (Benign vs. Malignant)  
- **Radar chart visualization** using Plotly  
- Custom **diagnosis color indicator**  
- Styled layout with CSS customization  

---

## Model Overview
- **Algorithm:** Logistic Regression  
- **Libraries:** scikit-learn, pandas, numpy  
- **Accuracy:** ~97% on test data  
- **Preprocessing:** StandardScaler normalization  

Trained on the [UCI Breast Cancer Wisconsin Dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data).

---

## To install & run locally:
```bash
git clone https://github.com/MoBahr98/streamlit-breast-cancer-predictor.git
cd breast-cancer-predictor
pip install -r requirements.txt
streamlit run app/main.py
```
