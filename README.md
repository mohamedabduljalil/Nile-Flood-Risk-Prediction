# 🌍 AI for Climate Change

## Flood Risk Prediction in the Nile Basin

A machine learning-based early warning system designed to predict **extreme flood risk events** in the **Nile Basin**, with a focus on **Egypt**, using high-resolution climate datasets and advanced machine learning models.

---

# 📌 Project Overview

Climate change is increasing the frequency and intensity of extreme weather events such as **heavy rainfall and floods**. Predicting these events early can significantly help governments and infrastructure planners mitigate risks.

This project develops a **Machine Learning classification system** capable of predicting **flood risk levels** based on climate variables including precipitation and temperature.

The system analyzes historical and projected climate data under different **climate change scenarios** and classifies flood risk into:

* 🟢 Low Risk
* 🟡 Medium Risk
* 🔴 High Risk

The final model will be deployed through an **interactive web application** that allows users to input climate conditions and receive **real-time flood risk predictions**.

---

# 🌊 Data Source

The project uses **CORDEX Climate Data** provided by the **Nile Basin Initiative (NBI)**.

Dataset includes:

* Daily precipitation (`pr`)
* Maximum temperature (`tasmax`)
* Minimum temperature (`tasmin`)

Climate projections are analyzed under the following scenarios:

* **RCP 4.5** – Moderate climate change scenario
* **RCP 8.5** – High emission scenario

These datasets allow the model to study the potential impact of **future climate conditions on flood risks**.

---

# 🧠 Machine Learning Approach

The problem is formulated as a **classification problem**.

The model predicts flood risk level based on climate indicators derived from the dataset.

### Target Classes

| Risk Level | Description                                                  |
| ---------- | ------------------------------------------------------------ |
| Low        | Normal rainfall conditions                                   |
| Medium     | Elevated rainfall levels                                     |
| High       | Potential extreme precipitation approaching flood thresholds |

### Algorithms Considered

* Random Forest
* XGBoost
* Gradient Boosting

Evaluation Metrics:

* Accuracy
* Precision
* Recall
* F1 Score

Special attention is given to minimizing **False Negatives**, since missing an extreme flood event can have serious consequences.

---

# ⚙️ Tech Stack

### Data Processing

* Python
* Pandas
* NumPy

### Data Visualization

* Matplotlib
* Seaborn

### Machine Learning

* Scikit-Learn
* XGBoost

### MLOps

* MLflow (experiment tracking)

### Deployment

* Streamlit / Gradio
* Hugging Face Spaces

---

# 📊 Project Workflow

```
Climate Data (CORDEX)
        │
        ▼
Data Extraction & Cleaning
        │
        ▼
Exploratory Data Analysis (EDA)
        │
        ▼
Feature Engineering
        │
        ▼
Machine Learning Model Training
        │
        ▼
Model Evaluation
        │
        ▼
Experiment Tracking (MLflow)
        │
        ▼
Web Application Deployment
```

---

# 📂 Project Structure

```
AI-Climate-Flood-Prediction
│
├── data
│   ├── raw
│   ├── processed
│
├── notebooks
│   ├── EDA.ipynb
│   ├── feature_engineering.ipynb
│   ├── model_training.ipynb
│
├── src
│   ├── data_processing.py
│   ├── feature_engineering.py
│   ├── train_model.py
│   ├── predict.py
│
├── app
│   ├── streamlit_app.py
│
├── models
│
├── proposal
│   └── project_proposal.pdf
│
├── requirements.txt
└── README.md
```

---

# 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/AI-Climate-Flood-Prediction.git
```

Navigate to the project folder:

```bash
cd AI-Climate-Flood-Prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

# 🖥️ Running the Project

To start the Streamlit application:

```bash
streamlit run app/streamlit_app.py
```

The application will open in your browser and allow users to input climate conditions to receive a **flood risk prediction**.

---

# 📈 Key Performance Indicators (KPIs)

### Data Quality

* 100% missing values handled
* ≥95% data consistency after preprocessing

### Model Performance

* Accuracy / F1 Score > 85%
* Prediction latency < 500 ms
* Error rate < 15%

### Deployment

* API uptime ≥ 99%
* Response time < 800 ms

---

# 👨‍💻 Team Members

| Name                    | Role                                |
| ----------------------- | ----------------------------------- |
| **Muhammad Abduljalil** | Team Leader & ML Engineer           |
| Karim Saber             | Data Engineer                       |
| Saied Ayad              | Data Analyst                        |
| Mostafa Maher           | Feature Engineering Specialist      |
| Abdelrahman Saber       | MLOps Engineer                      |
| Ammar Kroush            | Visualization & Deployment Engineer |

---

# 🌍 Impact

This project aims to demonstrate how **Artificial Intelligence can help address climate change challenges** by improving early warning systems for extreme weather events.

Potential benefits include:

* Supporting disaster preparedness
* Helping infrastructure planning
* Improving climate risk awareness

---

# 📜 License

This project is licensed under the **MIT License**.

---

# ⭐ Acknowledgments

* Nile Basin Initiative (NBI)
* CORDEX Climate Data Program
* eyouth & DEPI Program
