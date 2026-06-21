# Smart Parking Waiting Prediction and Simulation Using XGBoost and SimPy 🚗🅿️

Official repository and comprehensive documentation for the empirical research paper published in the **International Journal of Innovative Science and Research Technology (IJISRT)** under **Paper ID: IJISRT25DEC222**.

---

## 📌 Research Overview
Urban environments continuously suffer from heavy traffic congestion and inefficient spatial asset utilization. This research introduces a rigorous hybrid framework combining advanced **Machine Learning (ML)** predictions with **Discrete-Event Simulation (DES)** to accurately classify driver waiting behaviors and simulate queue dynamics within intelligent parking infrastructures.

### Key Contributions:
- **Predictive Intelligence:** Implementing optimized boosting trees to evaluate localized feature constraints and predict instantaneous waiting probability.
- **Stochastic Simulation:** Modeling sequential vehicle arrivals, operational bottlenecks, and facility utilization rates under capacity constraints.
- **System Synchronization:** Bridging static predictive classifiers with empirical environmental simulation parameters to provide actionable metrics for operations research.

---

## 🛠️ Tech Stack & Experimental Dependencies
- **Core Environment:** Python 3.9+
- **Predictive Engine:** XGBoost (Extreme Gradient Boosting Classifier)
- **Simulation Suite:** SimPy Framework
- **Data Engineering Frameworks:** Pandas, NumPy, Scikit-Learn

---

## ⚙️ Methodology & Pipeline Execution

### 1. Classification Model (XGBoost)
The predictive subsystem operates on targeted multi-dimensional structural attributes to forecast binary waiting outcomes (`Is_Waiting`: True/False).
- **Evaluated Features:** `Parking Duration`, `Available Slots`, `Cars in Queue`, and `Time of Day`.
- **Experimental Performance:** The hyperparameter-tuned XGBoost architecture achieved complete convergence, yielding optimized validation performance metrics: **100% Accuracy, 100% Precision, 100% Recall, and an F1-Score of 1.00** with zero misclassifications.

### 2. Operational System Simulation (SimPy)
The simulation model maps concrete environment operational limits to recreate live vehicle routing actions.
- **Core Parameters:**
  - **Facility Capacity:** 9 baseline slots
  - **Mean Processing Interval:** 66.3 minutes
  - **Stochastic Arrival Rate:** 0.2 vehicles/minute
  - **Continuous Run Interval:** 200 minutes
- **Empirical Findings:** The system stabilized around a historical facility waiting rate of **4.3%**, mathematically confirming model structural validity under active load testing.

---

## 📝 Publication & Official Citation
If you implement this framework, leverage the dataset configuration, or build upon this methodology, please credit the official publication:

```text
Norah Hadi Al Saleem, Remas Hadi Al Sulaie, Dr. Ahmed Mohammed Al Masabi (2025). 
Smart Parking Waiting Prediction and Simulation Using XGBoost and SimPy. 
International Journal of Innovative Science and Research Technology (IJISRT), Volume 10, Issue 12.
Digital No: IJISRT25DEC222
