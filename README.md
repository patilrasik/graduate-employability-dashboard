# 🎓 Graduate Employability Analyzer

A data analytics and machine learning project that predicts **graduate employability** and visualizes the key factors influencing placement outcomes using **Python** and **Power BI**.

---

## 🚀 Project Overview
The goal of this project is to identify **what factors most influence a graduate’s chance of getting placed** — such as CGPA, communication skills, academic performance, and internship experience.

The project combines:
- 🧠 Machine Learning (Random Forest Classifier)
- 🧹 Data Cleaning and Preprocessing in Python
- 📊 Interactive Power BI Dashboard for Insights

---

## 🧩 Tech Stack
| Tool | Purpose |
|------|----------|
| **Python (Pandas, Scikit-learn, Matplotlib, Seaborn)** | Data cleaning, model building, evaluation |
| **Power BI** | Dashboard creation and visualization |
| **GitHub** | Version control and project hosting |

---

## 📁 Project Structure
graduate-employability-analyzer/
│
├── data/ # Raw and processed data (local only)
│ ├── CollegePlacement.csv # Raw dataset (not uploaded)
│ ├── Cleaned_CollegePlacement.csv # Cleaned dataset for Power BI
│ ├── Feature_Importance.csv # ML model output
│ └── Predictions_vs_Actual.csv # Actual vs Predicted results
│
├── scripts/
│ └── placement_pipeline.py # Main Python script
│
├── powerbi/
│ └── README_POWERBI.md # Power BI setup guide
│
├── requirements.txt
├── .gitignore
├── LICENSE
└── README.md



---

## 🧮 Machine Learning Workflow

1. **Data Cleaning & Encoding**  
   - Removed nulls, standardized categorical columns (Yes/No → 1/0)
2. **Feature Selection**  
   - CGPA, Academic Performance, Communication Skills, etc.
3. **Model Training (Random Forest Classifier)**  
   - 80/20 train-test split  
   - Accuracy and feature importance calculated
4. **Outputs Generated for Power BI**  
   - `Cleaned_CollegePlacement.csv` → Dashboard base data  
   - `Feature_Importance.csv` → Model insight visualization  
   - `Predictions_vs_Actual.csv` → Model performance charts  

---

## 📊 Power BI Dashboard Highlights
**Dashboard Title:** *Graduate Employability Analyzer*  

### Key Insights:
- Students with internship experience have **35% higher placement rates**
- **CGPA** and **Communication Skills** are top predictors of employability  
- Model achieved **~87% accuracy** in predicting placement outcomes

### Dashboard Sections:
1. KPI cards → Total Students, Placement Rate, Avg CGPA, Prediction Accuracy  
2. Charts → CGPA vs Placement, Internship Impact, Feature Importance, Tree Map  
3. Model Results → Actual vs Predicted Placement  
4. Interactive Slicers → Internship, CGPA Range, Academic Performance  

---

## 📈 Results Snapshot
| Metric | Value |
|--------|--------|
| **Model Accuracy** | 0.87 |
| **Top Feature** | CGPA |
| **Dashboard Tool** | Power BI |
| **Language** | Python 3.11 |

---

## 🧠 Insights Summary
- **Internships** and **soft skills** are critical drivers of employability  
- Students with **CGPA above 8.0** have a higher placement probability  
- **Data-driven dashboards** help universities identify improvement areas  

---

## ⚙️ How to Run
### 1️⃣ Clone Repo
```bash
git clone https://github.com/<your-username>/graduate-employability-analyzer.git
cd graduate-employability-analyzer
