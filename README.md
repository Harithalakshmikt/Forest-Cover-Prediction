# 🌲 Forest Cover Type Prediction

This project predicts the type of forest cover (e.g., Spruce/Fir, Aspen, etc.) using cartographic and environmental data. The dataset comes from the **UCI Machine Learning Repository**, and various machine learning models were applied to evaluate prediction performance.

---

## 📌 Objective

To build a supervised classification system that predicts forest cover types based on terrain and soil features using models like:
- Logistic Regression
- Random Forest
- XGBoost


---

## 📁 Dataset

- Source: UCI Forest CoverType Dataset
- Samples: ~58,000
- Features: 54 (continuous and categorical)
- Target: `Cover_Type` (7 forest cover classes)

### Cover Type Classes:
1. Spruce/Fir  
2. Lodgepole Pine  
3. Ponderosa Pine  
4. Cottonwood/Willow  
5. Aspen  
6. Douglas-fir  
7. Krummholz

---

## 🛠️ Tools & Libraries

- Python, NumPy, Pandas
- scikit-learn
- XGBoost
- Matplotlib & Seaborn

---

## 📊 Model Performance (on test set)

| Model               | Accuracy |
|--------------------|----------|
| Logistic Regression| ~71%     |
| Random Forest      | ~88%     |
| XGBoost            | ~84%     |




