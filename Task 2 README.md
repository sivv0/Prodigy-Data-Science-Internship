Task 2 – Data Cleaning & Exploratory Data Analysis (EDA)

Objective-
To perform **data cleaning and exploratory data analysis (EDA)** on the given dataset and explore relationships between variables to identify patterns, insights, and correlations.

---
# Dataset Used

The following files were provided for analysis:

* `train.csv` – Training dataset containing passenger details
* `test.csv` – Test dataset (for model evaluation in future tasks)
* `gender_submission.csv` – Example submission file

---
# Data Cleaning Steps

1. **Handled Missing Values:**
   * Filled or dropped `NaN` values for columns like `Age`, `Cabin`, and `Embarked`.
2. **Removed Duplicates:**
   * Verified no duplicate rows.
3. **Converted Categorical Data:**
   * `Sex` converted to numeric (0 = male, 1 = female)
   * `Embarked` encoded as numeric values (S=0, C=1, Q=2)
5. **Checked Data Types:**
   * Ensured all features are in correct format (int/float/object).

---
# Exploratory Data Analysis (EDA)

1. **Univariate Analysis:**

   * Visualized Age and Fare distributions using histograms.
   * Count plots for Gender and Embarked locations.

2. **Bivariate Analysis:**

   * Compared `Survived` vs `Sex`, `Pclass`, and `Age`.
   * Found clear survival differences across gender and passenger class.

3. **Correlation Heatmap:**

   * Identified relationships between numeric variables.
   * Noted that `Sex`, `Pclass`, and `Fare` were most correlated with `Survival`.

---
# Key Insights

* **Females** had a higher survival rate than males.
* Passengers from **higher classes (Pclass = 1)** had better survival chances.
* **Younger passengers** tended to survive more often.
* **Higher fare** also showed a positive correlation with survival.

---
# Tools & Libraries Used

* Python (Pandas, NumPy, Matplotlib, Seaborn)
* Jupyter Notebook

---
# Outcome

Cleaned and analyzed the dataset successfully, extracted meaningful insights, and visualized relationships between key features.
This analysis will serve as the foundation for predictive modeling in upcoming tasks.

- Distribution of Passenger Ages -
![Output 1](https://github.com/user-attachments/assets/8c7101f7-f89b-4d0c-8b8e-ade1063a112a)

- Survival Count by Gender -
![Output 2](https://github.com/user-attachments/assets/1c614080-fb95-4b48-a361-9d090ed998b9)

- Survival Count by Passengers Class -
![Output 3](https://github.com/user-attachments/assets/3b005f31-241b-407c-ad78-fce8486a548c)

- Correlation between Numerical Features -
![Output 4](https://github.com/user-attachments/assets/ee284fe4-dffb-452d-a00e-acba58c72679)

---

### 🏢 Internship Info

This task is part of my **Data Science Internship** at [Prodigy InfoTech](https://github.com/Prodigy-InfoTech).

---
