# Exercise Frequency and BMI Among High School Students (YRBS 2007)

# Final Individual Project

## Student Information

Name: 吳婕綾

Student ID: 113370205


## 1. Research Question

**Question:** Does physical activity frequency affect BMI among high school students?

**Objective:** To investigate whether exercise frequency is associated with BMI percentile among high school students.

---

## 2. Variables Defined

**Independent Variable (IV):**
`PhysicalActivity5OrMoreDays`
(Number of days students engaged in physical activity)

**Dependent Variable (DV):**
`BMIPCT`
(BMI Percentile)

---

## 3. Data Cleaning

Utilized Python and pandas library to prepare the dataset.

- Selected the variables `PhysicalActivity5OrMoreDays` and `BMIPCT`
- Renamed the variables to `ExerciseDays` and `BMI`
- Applied `.dropna()` to remove missing values
- Retained only complete observations for regression analysis

Final sample size: **12,894 students**

---

## 4. Statistical Method

**Method:** Simple Linear Regression

The following regression model was used:

BMI = β₀ + β₁(ExerciseDays)

The purpose of this model is to examine whether exercise frequency significantly predicts BMI percentile.

---

## 5. Key Results & Interpretation

### Regression Results

- Coefficient (ExerciseDays) = **-0.139**
- p-value = **0.140**
- R² = **0.000**
- Sample Size = **12,894**

### Hypothesis Conclusion

Because **p = 0.140 > 0.05**, we fail to reject the null hypothesis.

### Interpretation

The regression coefficient is negative, suggesting that students who exercise more frequently tend to have slightly lower BMI percentiles.

However, the relationship is weak and not statistically significant.

---

## 6. Conclusion

Exercise frequency does not significantly affect BMI percentile among high school students in this dataset.

Although a slight negative trend was observed, the effect was not statistically significant.

---

## 7. Project Structure

```text
final-project/
│
├── README.md
├── FinalProject.ipynb
│
├── data
│   ├── YRBS_2007.csv
│   └── cleaned_data.csv
│
├── figures
│   ├── scatterplot.png
│   └── regressionplot.png
│
└── infographic_summary.pdf
```

---

## Project Repository

(Your GitHub Repository Link)

---

## Presentation Video

(Your YouTube Link)
