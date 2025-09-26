# 🗂️ Project: Analysis & Prediction of US Accidents

This notebook contains the full pipeline for analyzing and modeling traffic accidents in the United States. The goal is to understand patterns, correlations, and risk factors, while also applying Machine Learning models to predict the severity or nature of accidents.

Each code block corresponds to a specific script or use case, covering data cleaning, analysis, modeling, and visualization.

---

## 🚀 Project Objective

This Jupyter notebook centralizes all scripts required for the project.  
Each section can be executed independently to trigger specific tasks such as:

- Data cleaning and preparation  
- Statistical and visual analysis  
- Machine Learning modeling  
- Interactive dashboarding (using Dash/Plotly)  

The focus is on both **data exploration** and **predictive modeling**.

---

## 📥 Dataset

The dataset used is from **Kaggle**, available at the following link:

🔗 [US Accidents (Kaggle)](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents?resource=download)

After downloading, please place the file inside the `/data` folder at the root of the project.

---

## 🛠️ Environment & Dependencies

Before running the notebook, make sure all necessary Python libraries are installed.

### ✅ `requirements.txt`

```txt
fastapi==0.104.1
uvicorn==0.24.0
psycopg2-binary==2.9.9
PyJWT==2.8.0
scikit-learn==1.3.0
pandas==2.1.0
matplotlib==3.8.0
seaborn==0.12.2
pydantic==2.7.2
numpy==1.26.4
dash==2.14.0
plotly==5.16.0
nest_asyncio==1.5.6
basemodels==1.0.2  # ← validate if used in your project
```

---

## 📦 Installation

You can install the dependencies via:
```
pip install -r requirements.txt
```

---

## 📂 Notebook Structure

The notebook is divided into clearly defined sections.

Each script is modular, and you can run the cells in order or individually, depending on your needs.

---

## 🧠 Included Use Cases:

- Descriptive analysis of US accidents

- Correlation with weather, time, and location

- Severity classification using ML models

- Interactive dashboards and visual summaries

---

## 👥 Team & Roles

This project was built as a collaborative effort. Below are the roles and responsibilities:

- Saad: Data preparation and cleaning, handling missing values

- Thomas Y: Exploratory data analysis, statistical visualizations

- Thomas C: Machine Learning modeling, model comparison

- Noam: Project coordination, notebook integration, result synthesis

---

## 📌 Notes

The dataset must be placed in the /data folder before executing the notebook.

Additional visualizations or analyses can be added based on user needs or project expansion.