# Sonar Rock vs Mine Classification

This project uses machine learning to classify sonar signals as either **Rock (R)** or **Mine (M)** based on reflected signal strengths.

## Dataset
- Sonar dataset with 208 samples
- 60 numerical features representing sonar frequency reflections
- Binary target: Rock or Mine

## Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## Workflow
1. Data loading and preprocessing
2. Exploratory Data Analysis (EDA)
3. Feature scaling
4. Model training (Logistic Regression, Random Forest)
5. Model evaluation

## Results
- Achieved up to **85% accuracy**
- Logistic Regression used as baseline model

## How to Run
```bash
pip install -r requirements.txt
python src/train_model.py
