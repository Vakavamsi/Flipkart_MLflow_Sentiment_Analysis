# 🚀 Flipkart Sentiment Analysis – MLOps Project

## 📌 Overview
This project implements an end-to-end **Sentiment Analysis** pipeline on Flipkart product reviews, focusing on **real-world MLOps practices**. It integrates **MLflow** for experiment tracking and model management, and **Prefect** for workflow automation, with a **Streamlit** web app for predictions.

## 🎯 Key Features
- MLflow experiment tracking (params, metrics, artifacts)
- Model comparison and visualization
- Model Registry with versioning
- Automated pipelines using Prefect
- Streamlit-based sentiment analysis app

## 🧠 Tech Stack
- Python  
- Scikit-learn  
- MLflow  
- Prefect  
- Streamlit  
- Pandas, NumPy  
- TF-IDF Vectorizer  
- Logistic Regression  

## 📂 Project Structure
```
flipkart-mlflow-sentiment-analysis/
│
├── app.py                 # Streamlit application
├── train_mlflow.py        # MLflow experiment training pipeline
├── prefect_flow.py        # Prefect workflow automation
├── cleaned_data.csv       # Processed dataset
├── notebook.ipynb         # Model development notebook
├── requirements.txt
├── .gitignore
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository
```
git clone <your-github-repo-link>
cd flipkart-mlflow-sentiment-analysis
```

### 2️⃣ Create Virtual Environment
```
python -m venv myenv
myenv\Scripts\activate
```

### 3️⃣ Install Dependencies
```
pip install -r requirements.txt
```

---

## 🧪 Run MLflow Experiment Tracking

Start MLflow UI:
```
mlflow ui
```

Open in browser:
```
http://127.0.0.1:5000
```

Run training pipeline:
```
python train_mlflow.py
```

---

## 🔄 Run Prefect Workflow

Start Prefect Server:
```
prefect server start
```

Open Dashboard:
```
http://127.0.0.1:4200
```

Run workflow:
```
python prefect_flow.py
```

---

## 🖥️ Run Streamlit App
```
streamlit run app.py
```

Enter a Flipkart review and the system predicts:

- ✅ Positive Review
- ❌ Negative Review

---

## 📊 MLflow Capabilities Demonstrated
- Experiment Tracking
- Parameter & Metric Logging
- Artifact Storage
- Hyperparameter Visualization
- Model Versioning
- Model Tagging

---

## 💡 Learning Outcomes
This project helped me understand real-world **MLOps practices**, including:

- Hands-on experience with MLflow & Prefect
- Experiment tracking and model lifecycle management
- Automating ML workflows using MLOps tools
- Organizing model lifecycle using MLflow Registry

---

## 📸 Screenshots
### 🔬 MLflow 
![MLflow Experiment](workflow.png)

### ⚙️ Prefect Dashboard
![Prefect Dashboard](dashboard.png)

### 🖥️ Streamlit App
![Streamlit App](streamlit.png)

---

## 🔗 Connect With Me
If you find this project useful, feel free to connect and collaborate!

---

## ⭐ Acknowledgements
Thanks to the internship program for hands-on exposure to modern MLOps workflows.
