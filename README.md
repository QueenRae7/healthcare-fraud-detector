# healthcare-fraud-detector
healthcare-fraud-detector/
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
│   ├── 01_eda.ipynb
│   ├── 02_model_training.ipynb
│   └── 03_model_evaluation.ipynb
├── src/
│   ├── preprocessing.py
│   ├── train_model.py
│   └── predict.py
├── app/
│   └── streamlit_app.py
├── requirements.txt
├── README.md
└── .gitignore
# Healthcare Fraud Detector 🕵️‍♂️

A machine learning pipeline to detect fraudulent insurance claims using healthcare data.

## 🚀 Features
- Exploratory Data Analysis (EDA)
- Machine Learning models for fraud detection
- Streamlit-based interactive dashboard
- Model performance metrics

## 📊 Tech Stack
- Python, Pandas, Scikit-learn, XGBoost
- Streamlit for dashboard
- Jupyter Notebooks for analysis

## 📁 Structure
- `data/`: Raw and processed claim datasets
- `notebooks/`: EDA and modeling experiments
- `src/`: Python scripts for model training and prediction
- `app/`: Streamlit app

## ▶️ Run Streamlit App
```bash
streamlit run app/streamlit_app.py
