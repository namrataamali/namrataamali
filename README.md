# Namrata Mali | Data Science & Analytics

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=21&duration=3000&pause=1000&color=38BDF8&center=true&vCenter=true&width=750&lines=Data+Science+%26+Analytics;Machine+Learning+%7C+Predictive+Modeling;Turning+Data+Into+Decisions;Building+Intelligent+Applications" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://github.com/namrataamali">
    <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="https://www.linkedin.com/in/namratamali1308/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://medium.com/@namratam074">
    <img src="https://img.shields.io/badge/Medium-000000?style=flat-square&logo=medium&logoColor=white" alt="Medium" />
  </a>
</p>

---

## 01 — ABOUT ME

I am a **Data Science and Analytics enthusiast** with a Bachelor of Computer Applications (BCA) background, passionate about turning complex data into meaningful insights and intelligent solutions.

My interests span the complete data lifecycle — from data cleaning and exploratory analysis to statistical modeling, machine learning, and interactive application development.

I enjoy solving practical problems through analytical thinking, experimentation, and technology.

- Building machine learning and predictive analytics applications.
- Exploring data patterns through Python, SQL, and statistics.
- Developing interactive dashboards and analytical solutions.
- Learning how data can support smarter business decisions.
- Open to Data Scientist and Data Analyst opportunities.

---

## 02 — TECHNOLOGIES & TOOLS

**Programming & Databases**

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="SQL" />
</p>

**Data Analysis & Visualization**

<p>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy" />
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge" alt="Matplotlib" />
  <img src="https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white" alt="Plotly" />
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI" />
  <img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white" alt="Excel" />
</p>

**Machine Learning & Development**

<p>
  <img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="Scikit-learn" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter" />
</p>

**Development Tools**

<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  <img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" alt="VS Code" />
</p>

---

### 01. FloodGuard

**Flood Risk Prediction & Early Warning Intelligence**

`Python` `Random Forest` `Scikit-learn` `Pandas` `NumPy` `Plotly` `Streamlit`

A machine learning research prototype that analyzes historical Indian river-station observations to classify next-day water-level risk and identify potential transitions into High Risk.

**Key Highlights**

- Worked with approximately **3.86 million consecutive-day labelled examples** across **932 river monitoring stations**.
- Developed a Random Forest classifier to predict Low, Medium, and High water-level risk categories.
- Achieved **97.91% accuracy** and **0.85 High-Risk F1-score** on chronological test data.
- Evaluated the classifier against a persistence baseline, which achieved 98.59% accuracy.
- Developed a separate Random Forest escalation model to identify potential transitions into High Risk.
- Achieved **34.3% recall, 24.9% precision, and 0.288 F1-score** on historical validation data.
- Built an interactive Streamlit dashboard featuring station monitoring, historical trends, risk predictions, and batch CSV analysis.

**Model Evaluation:** Accuracy 97.91% | High-Risk F1 0.85 | Escalation F1 0.288

*Research prototype using historical observations and threshold-derived labels. It is not an official flood warning system and does not provide live measurements or verified flood-event predictions.*

[Explore FloodGuard on GitHub →](https://github.com/namrataamali/FloodGuard)

### 02. EnergyWatch AI
**Electricity Consumption Analytics & Anomaly Detection**

`Python` `Isolation Forest` `Scikit-learn` `Pandas` `Plotly` `Streamlit`

An intelligent electricity monitoring application that analyzes household consumption patterns, identifies unusual usage, and generates risk-based energy insights.

**Key Highlights**
- Analyzed **34,168 hourly electricity records** from the UCI Household Electric Power Consumption dataset.
- Implemented Isolation Forest for unsupervised anomaly detection.
- Identified **1,709 statistical anomalies**.
- Achieved a **0.5853 Silhouette Score** for predicted-group separation.
- Developed Low, Medium, and High anomaly risk classifications.
- Created an interactive dashboard with consumption trends, anomaly visualizations, CSV upload, and downloadable reports.

**Evaluation:** Silhouette Score 0.5853 | Anomaly Rate 5.00%

*Anomalies indicate unusual consumption patterns, not confirmed electrical faults.*

[Explore EnergyWatch on GitHub →](https://github.com/namrataamali/EnergyWatch-AI)

---

### 03. MachineGuard AI
**Predictive Maintenance & Equipment Failure Assessment**

`Python` `Random Forest` `Scikit-learn` `Pandas` `Streamlit`

A machine learning-based predictive maintenance system designed to identify potential equipment failures, assess operational risk, and support preventive maintenance decisions.

**Key Highlights**
- Used the UCI AI4I 2020 dataset containing **10,000 equipment records**.
- Developed a Random Forest classifier for machine failure prediction.
- Improved failure detection recall from **40% to 74%** through threshold optimization.
- Achieved approximately **68% precision and 70% F1-score** for failure detection.
- Implemented risk assessment and rule-based maintenance recommendations.
- Developed an interactive Streamlit dashboard for equipment monitoring and predictions.

**Evaluation:** Precision 68% | Recall 74% | F1-score 70%

*The AI4I dataset contains synthetic predictive-maintenance observations.*

[Explore MachineGuard on GitHub →](https://github.com/namrataamali/MachineGuard-AI)

---

### 4. DiaSense AI

**Diabetes Prediction & Interactive Health Analytics**

`Python` `Logistic Regression` `Scikit-learn` `Pandas` `NumPy` `Matplotlib` `Seaborn` `Streamlit`

An interactive machine learning application that analyses diabetes-related health indicators and generates model-based predictions using Logistic Regression.

**Key Highlights**

- Developed a diabetes prediction model using eight health-related input features.
- Integrated the trained machine learning model into a multi-page Streamlit application.
- Implemented interactive health inputs and probability-based prediction results.
- Built an analytics dashboard for dataset exploration, health indicator comparisons, and correlation analysis.
- Visualised model performance through confusion matrices and classification reports.
- Added session-based prediction history with CSV download functionality.
- Designed a modern, responsive interface with interactive visualisations.

[Explore DiaSense AI on GitHub →](https://github.com/namrataamali/Diabetes_Streamlit)

*Educational machine learning project. Predictions are not medical diagnoses.*

---

## 04 — AREAS OF INTEREST

| Domain | Focus |
|:---|:---|
| Data Science | Predictive Modeling, Machine Learning |
| Data Analytics | Data Cleaning, EDA, Statistical Analysis |
| Business Intelligence | Dashboard Development, Business Insights |
| Data Visualization | Interactive Charts, Data Storytelling |
| Applied AI | Classification, Anomaly Detection |

---

## 05 — EDUCATION & LEARNING

**Bachelor of Computer Applications (BCA)**

**Professional Training:** Postgraduate Program in Data Science & Analytics with GenAI — Imarticus Learning.

**Current Learning Focus**
- Advanced Python and SQL.
- Statistical analysis and machine learning.
- Feature engineering and model evaluation.
- Power BI and business intelligence.
- Real-world data science application development.

---

## 06 — GITHUB STATISTICS

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=namrataamali&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github" alt="GitHub Statistics" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=namrataamali&layout=compact&theme=tokyonight&hide_border=true" alt="Most Used Languages" />
</p>

## CONTRIBUTION ACTIVITY

<p align="center">
  <img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=namrataamali&theme=tokyo-night&hide_border=true" alt="GitHub Contribution Activity" />
</p>

---

## 07 — LET'S CONNECT

I am always interested in connecting with people who enjoy working with data, building intelligent applications, and solving meaningful problems.

<p align="center">
  <a href="https://www.linkedin.com/in/namratamali1308/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://github.com/namrataamali">
    <img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="https://medium.com/@namratam074">
    <img src="https://img.shields.io/badge/Medium-Read_Articles-000000?style=for-the-badge&logo=medium&logoColor=white" alt="Medium" />
  </a>
</p>

<p align="center">
  <i>Think analytically. Build intelligently. Create impact through data.</i>
</p>
