<h1 align="center" style="color:#FF8FAB;">Rosaliz Garcia / cybereptilia</h1>
<h3 align="center" style="color:#C77DFF;">
CS graduate & master's student · I build data pipelines, analytics dashboards, and web apps
</h3>

<p align="center">
  <img alt="Python" src="https://img.shields.io/badge/Python-ML/AI-303030?logo=python&logoColor=FFDD54&labelColor=202020">
  <img alt="Scikit-Learn" src="https://img.shields.io/badge/Scikit--Learn-ML%20Pipelines-303030?logo=scikitlearn&logoColor=FF8FAB&labelColor=202020">
  <img alt="TensorFlow" src="https://img.shields.io/badge/TensorFlow-Deep%20Learning-303030?logo=tensorflow&logoColor=FF6F00&labelColor=202020">
  <img alt="Pandas" src="https://img.shields.io/badge/Pandas-EDA/Feature%20Eng.-303030?logo=pandas&logoColor=FF8FAB&labelColor=202020">
  <img alt="Matplotlib" src="https://img.shields.io/badge/Matplotlib-Data%20Viz-303030?logo=plotly&logoColor=C77DFF&labelColor=202020">
  <img alt="SQL" src="https://img.shields.io/badge/SQL-Data%20Queries-303030?logo=postgresql&logoColor=00FFFF&labelColor=202020">
</p>

---

# About Me

B.S. in Computer Science (Data Science concentration) and master's student in Knowledge Discovery and Data Mining (Big Data) at Polytechnic University of Puerto Rico.

My focus is data: pipelines that validate and reconcile messy data, SQL analytics on PostgreSQL, and dashboards people can explore. I also build the software around it, from Python tooling to React front ends, and I'm growing toward machine learning.

Open to entry-level and internship roles in data analytics, data engineering, and software development in Puerto Rico.

| Area | Projects |
|---|---|
| Data engineering & analytics | [Healthcare Claims Data Pipeline](https://github.com/cybereptilia/healthcare-claims-pipeline) · [Predictive Maintenance SQL](https://github.com/cybereptilia/predictive-maintenance-sql) |
| Software & web | [MedTracker Frontend](https://github.com/cybereptilia/Medicine-Tracker-Front) (React + Tailwind) |
| Machine learning | [Iris classifier from scratch](https://github.com/cybereptilia/iris_project) · [Real estate regression](https://github.com/cybereptilia/real-estate-ml) · [Evaluation metrics](https://github.com/cybereptilia/Chapter-3-Evaluation-Metrics) |

---

# Featured Engineering Projects

### Healthcare Claims Data Pipeline

End-to-end pipeline that generates messy synthetic healthcare claims, validates and cleans them, loads them into PostgreSQL with run logging and row-level reconciliation, and serves the results in an interactive Streamlit dashboard.

<a href="https://github.com/cybereptilia/healthcare-claims-pipeline">
  <img src="https://raw.githubusercontent.com/cybereptilia/healthcare-claims-pipeline/main/docs/images/dashboard-overview.png" width="720" alt="Healthcare Claims Dashboard: KPI tiles and claims by status and member state">
</a>

**Concepts**
- ETL pipeline design with reject handling and raw = clean + rejected reconciliation
- auditable loads (pipeline run log and `run_id` lineage)
- PostgreSQL constraints, indexes, and analytics views
- interactive Streamlit dashboard (5 tabs) with parameterized SQL
- fraud-detection baseline models (in progress)

https://github.com/cybereptilia/healthcare-claims-pipeline

---

### Predictive Maintenance SQL Performance Study
Time-series database experiment (~600k rows) demonstrating PostgreSQL query planner behavior and index selectivity.

**Concepts**
- composite index design  
- cost-based query optimization  
- sequential vs index scan behavior  
- EXPLAIN ANALYZE benchmarking  

https://github.com/cybereptilia/predictive-maintenance-sql

---

# Current Work

- **MedTracker Frontend** — React + Tailwind integration for Front-end
- **ML Study Series** — Implementing algorithms from *Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow*  
- **Data Visualization Projects** — Interactive dashboards using Matplotlib, Seaborn, and Plotly  

---

# Self-Study & Practice Projects

## Iris Project — From-Scratch Classifier

<div align="center">
  <img src="https://raw.githubusercontent.com/cybereptilia/cybereptilia/main/assets/CrossEntropyLossIris_dataset.png" width="45%" alt="Cross Entropy Loss">
</div>

<div align="center">
  <img src="https://raw.githubusercontent.com/cybereptilia/cybereptilia/main/assets/EpochLoss_IrisProj.png" width="45%" alt="Epoch Loss Convergence">
</div>

<div align="center">
  <img src="https://raw.githubusercontent.com/cybereptilia/cybereptilia/main/assets/ValidationAccuracy_IrisProj.png" width="45%" alt="Validation Accuracy">
</div>

<p align="center"><sub style="color:#C77DFF;">Manual Softmax classifier using gradient descent and cross-entropy optimization achieving 96.67% accuracy.</sub></p>

---

## Real Estate Price Prediction — Regression Pipeline

<div align="center">
  <img src="https://raw.githubusercontent.com/cybereptilia/cybereptilia/main/assets/Feature_CorrelationsRealEstate.png" width="45%" alt="Feature Correlation Heatmap">
</div>

<p align="center"><sub style="color:#C77DFF;">Complete regression pipeline including EDA, feature engineering, model training, and evaluation.</sub></p>

---

## Evaluation Metrics — MNIST Digit Classifier

<div align="center">
  <img src="https://raw.githubusercontent.com/cybereptilia/cybereptilia/main/assets/PrecisionvsRecallCurve.png" width="45%" alt="Precision vs Recall Curve">
  <br>
  <img src="https://raw.githubusercontent.com/cybereptilia/cybereptilia/main/assets/PrecvsRecallvsThreshold.png" width="45%" alt="Precision Recall vs Threshold">
</div>

<p align="center"><sub style="color:#C77DFF;">Binary classification evaluation including precision-recall tradeoffs and ROC analysis (AUC ≈ 0.99).</sub></p>

---

# Toolchain

**Languages**  
Python • SQL • JavaScript • C++ • Java

**Libraries & ML Frameworks**  
NumPy • Pandas • Scikit-Learn • TensorFlow • Keras • Matplotlib • Seaborn

**Data Tools**  
PostgreSQL • JupyterLab • Google Colab • Excel

**Workflow**  
Git • GitHub • Virtual Environments

**Operating Systems**  
Rocky Linux • Ubuntu • Windows
