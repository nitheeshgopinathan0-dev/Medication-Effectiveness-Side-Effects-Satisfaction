# Project Documentation

## Project Title

### An Exploratory Data Analysis of Medication Effectiveness, Side Effects, and Patient Satisfaction Using Drug Reviews

## 1. Project Overview

This project analyzes **3,107 patient drug reviews** to understand medication effectiveness, side-effect severity, patient ratings, and overall satisfaction.

The project follows a structured data analytics workflow, including data cleaning, feature engineering, outlier detection, exploratory data analysis, statistical analysis, and visualization.

---

## 2. Dataset Information

- **Dataset:** Drug Reviews (Druglib.com)
- **File:** `drugLibTrain_raw_dataset.csv`
- **Source:** UCI Machine Learning Repository

The dataset includes:

- Drug names
- Medical conditions
- Patient ratings
- Medication effectiveness
- Side effects
- Patient review text

---

## 3. Project Objectives

- Analyze the distribution of patient ratings.
- Examine medication effectiveness and side-effect severity.
- Identify factors associated with patient satisfaction.
- Analyze patient review patterns and medical conditions.
- Apply univariate, bivariate, and multivariate analysis.
- Generate meaningful insights through visualization.

---

## 4. Data Processing

The following steps were performed:

- Missing values were identified and handled.
- The irrelevant `reviewID` column was removed.
- New analytical features were created.
- Outliers were detected using the IQR method.
- Outliers in review-length features were identified and retained because they represented genuine long patient reviews.

---

## 5. Feature Engineering

The following features were created:

- Review character and word counts
- `total_review_word_count`
- `sideEffect_severity_score`
- `effectiveness_score`
- `is_high_satisfaction`

These engineered features enabled deeper analysis of patient feedback.

---

## 6. Key Findings

- **2,130 patients (68.55%)** reported high satisfaction.
- Medication effectiveness showed a strong positive relationship with patient ratings.
- Increasing side-effect severity was strongly associated with lower ratings.
- The highest average ratings were associated with highly effective medications.
- The most positive experiences generally involved high medication effectiveness and minimal side effects.
- Review length showed only a weak relationship with patient ratings.

---

## 7. Conclusion

The analysis demonstrates that medication effectiveness and side-effect severity are important factors associated with patient ratings and satisfaction.

Overall, this project shows how a structured data analytics workflow can transform real-world patient drug reviews into meaningful insights about medication experiences and patient satisfaction.

---

## 8. Learning Takeaway

This project provided practical experience in:

**Data Cleaning → Feature Engineering → Outlier Detection → EDA → Visualization → Data Interpretation**

It also strengthened my understanding of **univariate, bivariate, and multivariate analysis** using real-world healthcare review data.
