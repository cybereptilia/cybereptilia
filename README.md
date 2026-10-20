<h1 align="center" style="color:#FF8FAB;">Rosaliz Garcia / cybereptilia</h1>
<h3 align="center" style="color:#C77DFF;">
CS graduate & master's student · I build data pipelines, analytics dashboards, and web apps
</h3>

<p align="center">
 <img src="https://img.shields.io/badge/Python-Data%20%26%20Tooling-2b2b2b?logo=python&logoColor=white" alt="Python: data and tooling">
<img src="https://img.shields.io/badge/SQL-PostgreSQL-2b2b2b?logo=postgresql&logoColor=white" alt="SQL: PostgreSQL">
<img src="https://img.shields.io/badge/pandas-Data%20Analysis-2b2b2b?logo=pandas&logoColor=white" alt="pandas: data analysis">
<img src="https://img.shields.io/badge/Streamlit-Dashboards-2b2b2b?logo=streamlit&logoColor=white" alt="Streamlit: dashboards">
<img src="https://img.shields.io/badge/React-Web%20Apps-2b2b2b?logo=react&logoColor=white" alt="React: web apps">
<img src="https://img.shields.io/badge/Git-Version%20Control-2b2b2b?logo=git&logoColor=white" alt="Git: version control">
<img src="https://img.shields.io/badge/Linux-Rocky%20%2F%20Ubuntu-2b2b2b?logo=linux&logoColor=white" alt="Linux: Rocky and Ubuntu">
<img src="https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-2b2b2b?logo=scikitlearn&logoColor=white" alt="Scikit-Learn: machine learning">
<img src="https://img.shields.io/badge/TensorFlow-Deep%20Learning-2b2b2b?logo=tensorflow&logoColor=white" alt="TensorFlow: deep learning">
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

- **Healthcare Claims Fraud Detection** — evaluating baseline models on the pipeline's synthetic claims
- **MedTracker Frontend** — React + Tailwind integration for the front end
- **ML Study Series** — implementing algorithms from *Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow*
- **Master's coursework** — Knowledge Discovery and Data Mining (Big Data), Polytechnic University of Puerto Rico

---

# Self-Study & Practice Projects

## Iris Project — From-Scratch Classifier

<div align="center">
  <img src="https://raw.githubusercontent.com/cybereptilia/cybereptilia/main/assets/EpochLoss_IrisProj.png" width="35%" alt="Training loss by epoch, from 1.095 at epoch 0 to 0.5755 at epoch 900">
</div>

<p align="center"><b>Final cross-entropy loss:</b> 0.290 · <b>Validation accuracy:</b> 96.67%</p>

<p align="center"><sub>Manual softmax classifier trained with gradient descent and cross-entropy loss. The loss spike at epoch 100 comes from a high learning rate; training recovers and converges by epoch 900.</sub></p>

---

## Real Estate Price Prediction — Regression Pipeline

<div align="center">
  <img src="https://raw.githubusercontent.com/cybereptilia/cybereptilia/main/assets/Feature_CorrelationsRealEstate.png" width="40%" alt="Feature correlation heatmap">
</div>

<p align="center"><sub>Complete regression pipeline including EDA, feature engineering, model training, and evaluation.</sub></p>

---

## Evaluation Metrics — MNIST Digit Classifier

<div align="center">
  <img src="https://raw.githubusercontent.com/cybereptilia/cybereptilia/main/assets/PrecisionvsRecallCurve.png" height="260" alt="Precision vs. recall curve">
  <img src="https://raw.githubusercontent.com/cybereptilia/cybereptilia/main/assets/PrecvsRecallvsThreshold.png" height="260" alt="Precision and recall vs. decision threshold"> 
</div>

<p align="center"><sub>Binary classification evaluation including precision-recall tradeoffs and ROC analysis (AUC ≈ 0.99).</sub></p>

---

# Toolchain

**Languages**  
Python • SQL • JavaScript • C++ • Java

**Libraries & ML Frameworks**  
NumPy • pandas • Scikit-Learn • TensorFlow • Keras • Matplotlib • Seaborn

**Data Tools**  
PostgreSQL • SQLAlchemy • Streamlit • Altair • JupyterLab • Google Colab • Excel

**Web**  
React • Tailwind CSS

**Workflow**  
Git • GitHub • Virtual Environments

**Operating Systems**  
Rocky Linux • Ubuntu • Windows
