# 🌊 NileGuard AI: Flood Risk Prediction in the Nile Basin

![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg)
![Scikit-Learn](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange.svg)
![MLflow](https://img.shields.io/badge/MLOps-MLflow-blue)
![Streamlit](https://img.shields.io/badge/Deployment-Streamlit-red.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

## 📌 Project Overview
[cite_start]This project aims to develop a machine learning-based early warning system to predict the risk level of extreme flooding events across the Nile Basin, with a specific focus on Egypt[cite: 582]. 

[cite_start]By analyzing high-resolution climate data under different global warming scenarios (RCP 4.5 and RCP 8.5), the system classifies the risk of upcoming weather events into **Low, Medium, or High Risk** based on Probable Maximum Precipitation (PMP) thresholds[cite: 584, 585]. [cite_start]The final deliverable is an interactive web application that provides real-time flood risk predictions[cite: 586].

---

## 📊 The Dataset
[cite_start]The project leverages high-resolution **CORDEX climate data** provided by the **Nile Basin Initiative (NBI)**[cite: 583]. The dataset includes historical and projected climate variables (1971–2095) such as:
* [cite_start]**`pr`**: Daily precipitation[cite: 584].
* [cite_start]**`tasmax` & `tasmin`**: Maximum and minimum daily temperatures[cite: 584].
* [cite_start]**`IDF` & `PMP`**: Intensity-Duration-Frequency curves and Probable Maximum Precipitation thresholds used for risk classification[cite: 585].

---

## 🛠️ Tools & Technologies
* [cite_start]**Data Engineering & Processing:** SQL, Python, Pandas, NumPy[cite: 602, 603].
* [cite_start]**Exploratory Data Analysis (EDA):** Matplotlib, Seaborn[cite: 604].
* [cite_start]**Machine Learning:** Scikit-Learn, Random Forest, XGBoost[cite: 605].
* [cite_start]**MLOps & Tracking:** MLflow[cite: 605].
* [cite_start]**Deployment:** Streamlit / Gradio, Hugging Face Spaces[cite: 606].

---

## 🚀 Project Pipeline & Milestones
1.  [cite_start]**Data Extraction:** Querying and structuring CORDEX climate datasets via SQL[cite: 608].
2.  [cite_start]**Data Cleaning & EDA:** Handling missing values, analyzing rainfall distributions, and finding climate correlations[cite: 609].
3.  [cite_start]**Feature Engineering:** Creating derived climate indicators and setting up the target variable (`Flood_Risk`)[cite: 610].
4.  [cite_start]**Modeling & Evaluation:** Training Classification models and tracking experiments with MLflow[cite: 611].
5.  [cite_start]**Deployment:** Building the dashboard and deploying it to production[cite: 612].

---

## 👥 Meet the Team
This project is developed by a dedicated team of data professionals:
* [cite_start]**Muhammad Abduljalil** - *Team Leader & ML Engineer* (ML Pipeline, Model Training, Hyperparameter Tuning)[cite: 588].
* [cite_start]**Karim Saber** - *Data Engineer* (Data Extraction, SQL Queries, Data Pipelines)[cite: 589].
* [cite_start]**Saied Ayad** - *Data Analyst* (EDA, Anomaly Detection, Correlation Mapping)[cite: 590].
* [cite_start]**Mostafa Maher** - *Feature Engineering Specialist* (Derived Features, Data Scaling)[cite: 591].
* [cite_start]**Abdelrahman Saber** - *MLOps Engineer* (MLflow Tracking, Model Versioning)[cite: 592].
* [cite_start]**Ammar Kroush** - *Visualization & Deployment Engineer* (Dashboard Design, Streamlit/Gradio App)[cite: 593].

---

## ⚙️ How to Run the Project (Local Setup)
*(Instructions will be updated as the project progresses)*

1. Clone the repository:
   ```bash
   git clone [https://github.com/mohamedabduljalil/Nile-Flood-Risk-Prediction.git](https://github.com/mohamedabduljalil/Nile-Flood-Risk-Prediction.git)
   cd Nile-Flood-Risk-Prediction
