## 🏠 House Price Prediction

A simple Machine Learning project that predicts house prices using **Linear Regression** on the California Housing dataset.

---

## 📌 Overview
- End-to-end ML workflow  
- Data loading and preprocessing  
- Model training and evaluation  
- Prediction on new data  

---

## 🔗 Colab Notebook
https://colab.research.google.com/https://colab.research.google.com/drive/1KEznTUqeMxk1LT6xyuxm5Ajdjm_0Dfb9#scrollTo=c5cAG9foUWD_

---

## ⚙️ Tech Stack
- Python  
- Pandas  
- Scikit-learn  

---

## 📊 Dataset
- California Housing Dataset  

### Features
- MedInc (Median Income)  
- HouseAge  
- AveRooms  
- AveBedrms  
- Population  
- AveOccup  
- Latitude  
- Longitude  

### Target
- Price  

---

## 🚀 Workflow
- Load dataset using `fetch_california_housing`  
- Convert to Pandas DataFrame  
- Train-test split  
- Train Linear Regression model  
- Predict on test data  
- Compare actual vs predicted  
- Predict for new input  

---

## 🧠 Model
- Linear Regression  

---

## 📈 Evaluation
- Mean Squared Error (MSE)  

---

## 🔮 Prediction Example
```python
new_house = [[8.0, 20.0, 6.0, 1.0, 1000, 3.0, 34.0, -118.0]]
