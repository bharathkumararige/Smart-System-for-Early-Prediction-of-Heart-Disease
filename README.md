
# ❤️ Smart System for Early Prediction of Heart Disease

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Random_Forest-228B22?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"/>
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
</p>

> A machine learning-based system that predicts whether a person is likely to develop heart disease based on clinical and demographic information, using a Random Forest Classifier trained on the UCI Heart Disease dataset.

---

## 📌 Project Objective

The goal is to assist in the **early detection of heart disease** using a smart, data-driven system. Early predictions can help initiate timely medical treatment and lifestyle changes — potentially saving lives.

---

## 🎯 Result

| Metric | Score |
|--------|-------|
| Model | Random Forest Classifier |
| Dataset | UCI Heart Disease |
| Train/Test Split | 80% / 20% |
| Output | Binary (0 = No Disease, 1 = Disease Detected) |

> ✅ **1 → ❌ Heart Disease Detected** &nbsp;&nbsp; **0 → ✅ No Heart Disease Detected**

---

## 🧠 Technologies Used

| Category | Tools |
|----------|-------|
| Language | Python 3.x |
| ML Model | Random Forest Classifier |
| Data Handling | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| ML Framework | Scikit-learn |
| Environment | Jupyter Notebook |

---

## 📁 Dataset Information

- **Source:** UCI Heart Disease Repository
- **File:** `Heart diis.csv`

| Feature | Description |
|---------|-------------|
| `age` | Age of the patient |
| `sex` | Sex (1 = male, 0 = female) |
| `cp` | Chest pain type (0–3) |
| `trestbps` | Resting blood pressure |
| `chol` | Serum cholesterol (mg/dl) |
| `fbs` | Fasting blood sugar > 120 mg/dl |
| `restecg` | Resting ECG results |
| `thalach` | Maximum heart rate achieved |
| `exang` | Exercise-induced angina |
| `oldpeak` | ST depression |
| `slope, ca, thal` | Other clinical measurements |
| `target` | Heart disease presence (1 = yes, 0 = no) |

---

## 🔄 Workflow

```
Raw Data (Heart diis.csv)
     ↓
Data Preprocessing
(Missing values, encoding, feature selection)
     ↓
Exploratory Data Analysis
(Visualizations, correlations)
     ↓
Random Forest Model Training (80/20 split)
     ↓
Evaluation (Accuracy, Precision, Recall, F1, Confusion Matrix)
     ↓
Feature Importance Analysis
     ↓
Prediction Output (Heart Disease: Yes / No)
```

---

## 📊 Key Insights

- 🫀 **Chest pain type** is the strongest predictor of heart disease
- 💓 **Maximum heart rate** and **ST depression** are highly correlated with disease
- 🧪 **Cholesterol levels** and **fasting blood sugar** play supporting roles
- 👨 **Age and sex** show significant impact on heart disease probability

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/bharathkumararige/Smart-System-for-Early-Prediction-of-Heart-Disease.git
cd Smart-System-for-Early-Prediction-of-Heart-Disease
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Open the Notebook
```bash
jupyter notebook "ML project.ipynb"
```

### 4. Run All Cells
Execute all cells to see the full pipeline from data loading to prediction! ✅

---

## 📁 Project Structure

```
Smart-System-for-Early-Prediction-of-Heart-Disease/
│
├── ML project.ipynb      # Main Jupyter notebook
├── Heart diis.csv        # Dataset
├── requirements.txt      # Dependencies
└── README.md
```

---

## 👨‍💻 Author

**Arige Bharath Kumar**
- 🎓 B.Tech CSE (Data Science) — Graduating July 2026
- 📧 [arigebharathkumar@gmail.com](mailto:arigebharathkumar@gmail.com)
- 🔗 [LinkedIn](https://linkedin.com/in/arigebharath)
- 🐙 [GitHub](https://github.com/bharathkumararige)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<p align="center">⭐ <b>If you found this project helpful, please give it a star!</b> ⭐</p>
