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
![Survival Count]<img width="640" height="480" alt="Figure_2" src="https://github.com/user-attachments/assets/3670ed3e-f70d-4cb6-8e1e-31bd7978aebe" />
**Survival by Sex**
![Survival by Sex]<img width="640" height="480" alt="Figure_1" src="https://github.com/user-attachments/assets/8fbc6ad5-b754-4977-b2c7-53fca85d52a2" />

**Survival by Passenger Class**
![Survival by Pclass]<img width="640" height="480" alt="Figure_3" src="https://github.com/user-attachments/assets/e124bedd-e645-4cf8-b659-c514f53e4e51" />


**Age Distribution**
![Age Distribution]<img width="640" height="480" alt="Figure_4" src="https://github.com/user-attachments/assets/e949ad4b-6318-44ef-906a-6f47551ccc61" />



## How to Run:

1. Clone repo
2. Install dependencies: `pip install -r requirements.txt`
3. Run notebook: `notebooks/titanic_analysis.ipynb`  
   OR run script: `python scripts/train_model.py`
