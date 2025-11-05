# DashSense_Model

## DashSense: DoorDash Best Zone Prediction

**DashSense** is an end-to-end data science project that predicts the best zones for DoorDash drivers to work in — based on the day of the week and shift duration.  
The project simulates realistic delivery data, builds a complete ML pipeline, and identifies the most profitable or efficient delivery zones.

---

##  Project Overview

This notebook builds a reproducible machine learning workflow that:
- Synthesizes realistic 4-week DoorDash activity data (≈ 16,800 rows × 13 columns)
- Explores patterns across **zones**, **days**, and **shift durations**
- Preprocesses and encodes categorical + numeric features
- Trains and tunes a **Random Forest Classifier**
- Evaluates performance using **ROC-AUC**, **accuracy**, and **classification metrics**
- Recommends top zones per shift/day using model predictions

---

##  Key Insights

- **Random Forest** achieved strong ROC-AUC performance after tuning.
- **Time-based features** (start time, end time, day of week) were the strongest predictors.
- **Top-performing zones** were consistently:
  - Scottsdale Arcadia  
  - Downtown Phoenix  
  - North Phoenix  
  - Kierland

These results reflect realistic delivery dynamics where timing impacts demand and pay more than geography alone.

---

## Tech Stack

| Category | Tools |
|-----------|-------|
| Language | Python 3.x |
| Libraries | pandas, numpy, scikit-learn, seaborn, matplotlib, scipy |
| Modeling | Random Forest Classifier (with Grid/Random Search tuning) |
| Evaluation | ROC-AUC, Confusion Matrix, Classification Report |
| Visualization | Seaborn & Matplotlib |
| Environment | Jupyter Notebook |
