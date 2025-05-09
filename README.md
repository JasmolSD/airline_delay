# ✈️ Weather & Flight Performance Prediction

**DATASCI 261 – Machine Learning at Scale | Team 1_3**  
Ahsin Saleem · Anshul Zutshi · Cat Weiss · **Jasmol Dhesi** · Umesh Kant  

Predict whether a flight will be delayed by **15 minutes or more** using
historical flight, weather, and airport data (2015–2019).  
The project maximizes **recall** to avoid missing potential delays and
empowers travelers, airlines, and airports with actionable insights.

---

## 📊 Key Results
| Metric | Single‑Layer MLP |
|--------|-----------------|
| **Precision** | 0.8232 |
| **Recall** | 0.6961 |
| **AUC** | 0.8992 |
| **F1** | 0.7544 |

*Data leakage issues were investigated and resolved, ensuring reliable
evaluation.*

---

## 🔍 Highlights
- Implemented Logistic Regression, Random Forest, and Multilayer Perceptron  
- Extensive hyperparameter tuning + Bayes‑rule calibration for
  down‑sampling bias  
- **Feature engineering:** rolling three‑month delay counts, holiday flags,
  weather condition indicators  
- Handled **~31 M** flight rows & **~630 M** weather rows with **PySpark** on
  **Databricks**  

---

## 📁 Repository Structure
📦 project-root
├── Phase 3 – Final Report‑Team‑1‑3.ipynb # EDA + early modeling
├── Phase 3 – Final ‑ Team‑1‑3.ipynb # Final modeling notebook
├── 261 Team 1_3 Project Report Final.pptx # Slide deck
└── README.md

---

## 🛠 Tech Stack
Python · PySpark · Spark MLlib · Databricks · AWS  
NumPy · Pandas · Matplotlib · Seaborn  

---

## 🚀 Next Steps
1. Add Decision Trees for interpretability  
2. Explore ensemble methods (boosting, stacking)  
3. Further hyperparameter sweeps for marginal gains  

---

## 🤝 Contributing
Pull requests are welcome. Please open an issue to discuss proposed
changes before submitting.

---

## 📜 License
Distributed under the MIT License. See `LICENSE` for details.

