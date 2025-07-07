# Alzheimer's Disease Classification & Explainable AI
This repository showcases a machine learning project to classify stages of Alzheimer's Disease using demographic, lifestyle, medical, and cognitive data.  
The project focuses not only on prediction accuracy, but also on explaining model decisions using multiple state-of-the-art explainability methods: **SHAP, LIME, Anchor, and QLattice**.

---

## Project Overview
- **Goal**: Predict Alzheimer's Disease diagnosis stage from patient data.
- **Methods**:
  - Data cleaning and exploration (EDA)
  - Model training (e.g., XGBoost, Random Forest, etc.)
  - Model explainability: SHAP, LIME, Anchor explanations, QLattice modeling
- **Dataset**: Alzheimer's Disease Dataset by Rabie El Kharoua (2024) on Kaggle (2,149 patients aged 60–90).

This project demonstrates:
✅ Transfer learning & ensemble models  
✅ Multiple explainability techniques  
✅ Professional, modular project structure for reproducibility


## 📂 Project Structure
```plaintext
alzheimers-xai-ml/
├── data/                    # (empty or small sample CSVs only)
├── notebooks/
│   └── alzxai.ipynb         # 📓 Main notebook: full EDA, modeling, explainability
├── src/                     # 🛠 Reusable helper modules
│   ├── data_utils.py
│   ├── eda_utils.py
│   ├── model_utils.py
│   └── explainability_utils.py                
├── requirements.txt         # Python dependencies
├── README.md                # 📖 This file
└── .gitignore
