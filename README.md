# 🫁 Lung Cancer Prediction using Machine Learning

This project aims to predict the risk of lung cancer using a medical survey dataset and machine learning models. The analysis includes preprocessing, visualization, training multiple classifiers, and testing predictions with new user input.

---

## 🔍 Project Overview

- **Dataset**: `survey lung cancer.csv` (Kaggle)
- **Objective**: Predict if a person is likely to have lung cancer based on health and lifestyle factors.
- **Tech Stack**: Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **ML Models Used**: Logistic Regression, Decision Tree, Random Forest
- **Evaluation Metric**: Accuracy Score
- **Custom Testing**: Accepts new user data for prediction testing

---

## 📁 Dataset Information

Key columns in the dataset include:

| Column Name         | Description                                  |
|---------------------|----------------------------------------------|
| `AGE`               | Age of the individual                        |
| `GENDER`            | Male or Female                               |
| `SMOKING`           | Whether the person smokes                    |
| `ANXIETY`           | Presence of anxiety                          |
| `ALCOHOL CONSUMING` | Alcohol consumption habit                    |
| `LUNG_CANCER`       | Target column — YES or NO                    |
| ...                 | Other features related to health and habits |

---

## 📊 Exploratory Data Analysis (EDA)

- Average age of male and female patients
- Gender distribution
- Lung cancer frequency by lifestyle habits
- Minimum and maximum age among affected patients (male and female)
- Visualization using Seaborn & Matplotlib

---

## 🧠 Machine Learning Workflow

```mermaid
graph TD
A[Dataset] --> B[Data Cleaning & Encoding]
B --> C[EDA & Visualization]
C --> D[Train/Test Split]
D --> E[Model Training]
E --> F[Accuracy Evaluation]
F --> G[New Data Prediction]
## 🧠 How to Run
# Step 1: Clone the repository
git clone https://github.com/yourusername/lung-cancer-prediction.git
cd lung-cancer-prediction

# Step 2: Install the required libraries
pip install pandas numpy matplotlib seaborn scikit-learn

# Step 3: Run the Jupyter notebook or Python script
jupyter notebook Lung_Cancer_Prediction.ipynb
📷 Sample Visuals
Gender-wise age distribution

Count of lung cancer patients by gender

Smokers vs. Non-smokers cancer frequency

Min/Max ages for male and female patients with cancer

🙋‍♂️ About Me
I'm a data science enthusiast from Bangladesh 🇧🇩
📧 Email: iftakharahmadrafi@gmail.com
🌐 GitHub: (https://github.com/IftakharAhmadRafi)

🤝 Contributions
Contributions, issues, and feature requests are welcome!
Feel free to fork this repository and submit a pull request.







