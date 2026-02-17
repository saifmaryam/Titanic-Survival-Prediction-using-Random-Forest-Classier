# Titanic-Survival-Prediction

**Objective:** Predict which passengers survived the Titanic disaster using Machine Learning.

**Dataset:** [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)

**Technologies Used:** Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn

---

## Workflow:

1. **Exploratory Data Analysis (EDA)**
   - Visualized survival rates by gender, passenger class, and age
2. **Data Preprocessing**
   - Filled missing Age & Embarked values
   - Encoded categorical features
3. **Modeling**
   - Random Forest Classifier
   - Achieved ~85% accuracy
4. **Visualizations**
   - Gender vs Survival
   - Passenger Class vs Survival
   - Age Distribution
### Exploratory Data Analysis Visuals

**Survival Count**
![Survival Count](<img width="640" height="480" alt="Figure_1" src="https://github.com/user-attachments/assets/5ca68dcc-f7ca-4c56-9064-7485d0e7dd14" />
.png)

**Survival by Sex**
![Survival by Sex](visuals/survival_by_sex.png)

**Survival by Passenger Class**
![Survival by Pclass](visuals/survival_by_pclass.png)

**Age Distribution**
![Age Distribution](visuals/age_distribution.png)


## How to Run:

1. Clone repo
2. Install dependencies: `pip install -r requirements.txt`
3. Run notebook: `notebooks/titanic_analysis.ipynb`  
   OR run script: `python scripts/train_model.py`
