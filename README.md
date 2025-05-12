# Smart-System-for-Early-Prediction-of-Heart-Disease
This project aims to build a machine learning-based system that predicts whether a person is likely to develop heart disease based on clinical and demographic information. The model leverages a Random Forest Classifier, trained on the UCI Heart Disease dataset, to provide accurate and interpretable results.

📌 Project Objective
The goal is to assist in the early detection of heart disease using a smart, data-driven system. Early predictions can help in initiating timely medical treatment and lifestyle changes, potentially saving lives.

🧠 Technologies Used
Python
. Pandas & NumPy – for data handling
. Matplotlib & Seaborn – for data visualization
. scikit-learn – for machine learning (Random Forest)

Jupyter Notebook 
📁 Dataset Information
The dataset used in this project is sourced from the Heart_Disease Repository, which includes features like:
| Feature         | Description                              |
| --------------- | ---------------------------------------- |
| age             | Age of the patient                       |
| sex             | Sex (1 = male, 0 = female)               |
| cp              | Chest pain type (0–3)                    |
| trestbps        | Resting blood pressure                   |
| chol            | Serum cholesterol (mg/dl)                |
| fbs             | Fasting blood sugar > 120 mg/dl          |
| restecg         | Resting ECG results                      |
| thalach         | Maximum heart rate achieved              |
| exang           | Exercise-induced angina                  |
| oldpeak         | ST depression                            |
| slope, ca, thal | Other clinical measurements              |
| target          | Heart disease presence (1 = yes, 0 = no) |

🔄 Workflow
>> Data Preprocessing
. Handled missing values
. Encoded categorical variables
. Performed feature selection

>> Model Training
. Random Forest Classifier used due to its high accuracy and interpretability
. Trained on 80% of the data and tested on 20%

>> Evaluation Metrics
. Accuracy, Precision, Recall, F1-Score
. Confusion Matrix for classification results
. Feature importance visualization

> Visualizations were created to understand which features influence the prediction the most (e.g., chest pain type, cholesterol, max heart rate, etc.).

✅ Result
The model achieved high accuracy and successfully predicts whether a patient has heart disease based on input data. The output is binary (0 or 1), where:
. 1 → ❌ Heart Disease Detected
. 0 → ✅ No Heart Disease Detected



