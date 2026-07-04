# 📊 Digital Distraction and Academic Performance

<img width="512" height="268" alt="Image" src="https://github.com/user-attachments/assets/920389fc-b084-4e17-af31-c18dbfa13b40" />

### An Excel-Based Data Analysis Project

## 📌 Project Overview

This project investigates the relationship between **digital distraction and academic performance** using Microsoft Excel, Power Query, Pivot Tables, and Power BI. The analysis explores how behavioral, health, psychological, and socioeconomic factors influence students' final examination performance.

The project answers five key business questions:

- 📱 Does excessive smartphone usage impact academic performance?
- 😴 How does sleep affect exam scores?
- 🏃 Does exercise improve student productivity?
- 🧠 Do motivation and mental health influence academic outcomes?
- 🌍 Do environmental and socioeconomic factors play a role?

---

# 🎯 Business Objectives

The primary objective is to identify the factors that significantly influence students' academic performance and provide data-driven recommendations that can help educational institutions improve student outcomes.

---

# 📂 Dataset Information

The dataset contains approximately **15,000 student records** with the following variables:

| Variable |
|-----------|
| student_id |
| age |
| gender |
| study_hours_per_day |
| smartphone_usage_hours |
| social_media_hours |
| gaming_hours |
| streaming_hours |
| sleep_hours |
| exercise_hours |
| class_attendance_percent |
| assignment_completion_percent |
| caffeine_intake_cups |
| mental_health_status |
| parent_education_level |
| internet_quality |
| motivation_level |
| final_exam_score |

---

# 🛠 Tools Used

- Microsoft Excel
- Power Query
- Pivot Tables
- Excel Statistical Analysis ToolPak
- Power BI

---

# 🔄 Data Preparation

The dataset was cleaned and transformed using **Power Query**.

Data preparation included:

- Removing duplicates
- Handling missing values
- Correcting data types
- Creating calculated fields
- Categorizing variables

### Engineered Features

**Digital Distraction Score**

```
Social Media Hours
+ Gaming Hours
+ Streaming Hours
```

**Productivity Index**

```
Study Hours
+ Class Attendance
+ Assignment Completion
-----------------------------
                3
```

Categorical variables created:

- Smartphone Category
- Sleep Category
- Exercise Category

---

# 📈 Exploratory Data Analysis (EDA)

Pivot Tables and descriptive statistics were used to summarize the dataset.

Key descriptive statistics included:

- Mean
- Median
- Mode
- Standard Deviation
- Variance
- Range
- Skewness
- Kurtosis

### Final Exam Score Summary

| Statistic | Value |
|------------|-------|
| Mean | 80.34 |
| Median | 83.75 |
| Mode | 100 |
| Standard Deviation | 18.43 |
| Minimum | 2.63 |
| Maximum | 100 |

The descriptive analysis showed that students generally performed well, with scores concentrated toward the higher end of the grading scale.

---

# 📊 Business Question Analysis

## 1️⃣ Does excessive smartphone usage impact academic performance?

### Findings

| Smartphone Category | Average Exam Score |
|---------------------|-------------------|
| Moderate | 82.06 |
| Low | 80.28 |
| High | 78.14 |

### Interpretation

Students with excessive smartphone usage obtained the lowest average examination scores, suggesting that prolonged smartphone use may negatively affect academic performance.

---

## 2️⃣ How does sleep affect exam scores?

### Findings

| Sleep Category | Average Exam Score |
|----------------|-------------------|
| Optimal | 81.91 |
| Excess | 80.18 |
| Poor | 77.53 |

### Correlation

Pearson Correlation

```
r = 0.073
```

### Interpretation

Sleep demonstrates a positive but weak relationship with academic performance. Students with optimal sleep achieved the highest examination scores.

---

## 3️⃣ Does exercise improve student productivity?

### Correlation

```
Exercise Hours vs Productivity Index

r = 0.003
```

### Interpretation

The relationship between exercise and productivity is extremely weak. Exercise alone does not appear to significantly influence productivity in this dataset.

---

## 4️⃣ Do motivation and mental health influence outcomes?

### Multiple Linear Regression

Dependent Variable

```
Final Exam Score
```

Independent Variables

- Study Hours
- Motivation Level
- Mental Health Status

### Model Performance

| Metric | Value |
|----------|--------|
| Multiple R | 0.697 |
| R² | 0.486 |
| Adjusted R² | 0.486 |
| F Statistic | 4725.46 |
| Significance | <0.001 |

### Regression Coefficients

| Variable | Coefficient |
|------------|------------|
| Study Hours | 5.98 |
| Motivation Level | 1.48 |
| Mental Health Status | 5.55 |

### Interpretation

The regression model explains approximately **48.6%** of the variation in students' academic performance.

Among the variables analyzed:

- Study hours produced the strongest positive influence.
- Mental health demonstrated a substantial positive effect.
- Motivation significantly improved examination performance.

---

## 5️⃣ Do environmental and socioeconomic factors play a role?

Average Final Exam Scores

| Parent Education | Average Score |
|------------------|---------------|
| High School | 78.57 |
| Bachelor's | 81.24 |
| Master's | 81.86 |
| PhD | 82.55 |

### Interpretation

Students whose parents possessed higher educational qualifications generally achieved higher academic performance, suggesting that socioeconomic background contributes positively to educational outcomes.

---

# 📉 Statistical Techniques Used

- Descriptive Statistics
- Pivot Table Analysis
- Correlation Analysis
- Multiple Linear Regression
- Data Visualization
- Dashboard Design

---

# 📊 Power BI Dashboard

The dashboard consists of:

### Executive Overview

- Average Exam Score
- Average Sleep Hours
- Average Smartphone Usage
- Productivity Index

### Digital Distraction

- Smartphone Usage vs Exam Score
- Smartphone Usage Categories

### Health & Lifestyle

- Sleep vs Exam Performance
- Exercise vs Productivity

### Mental Health & Motivation

- Regression Findings
- Academic Performance Comparison

### Socioeconomic Factors

- Parent Education
- Internet Quality
- Academic Performance

---

# 💡 Key Findings

- Excessive smartphone usage is associated with lower academic performance.
- Students with optimal sleep achieved the highest examination scores.
- Exercise showed minimal direct influence on productivity.
- Mental health and motivation significantly improve academic outcomes.
- Parent education positively influences student performance.
- Academic success is influenced by multiple behavioral, psychological, and environmental factors rather than digital distraction alone.

---

# ✅ Recommendations

- Encourage responsible smartphone usage among students.
- Promote healthy sleep habits to improve academic outcomes.
- Strengthen student mental health support services.
- Develop programs that increase student motivation and engagement.
- Provide additional academic support for students from less advantaged educational backgrounds.
- Adopt a holistic approach to improving student performance by addressing behavioral, psychological, and socioeconomic factors.

---

# 📌 Conclusion

The analysis demonstrates that academic performance is not determined by digital distraction alone. Although excessive smartphone use is associated with lower examination scores, the strongest predictors of academic success are study habits, mental health, motivation, and supportive home environments.

The findings emphasize that improving student outcomes requires an integrated strategy that combines academic support, healthy lifestyle practices, psychological well-being, and balanced technology use.

---

## 👤 Author

**Titi Ikimi**

Data Analytics Project

Microsoft Excel | Power Query | Pivot Tables | Power BI
I am open for collaborate on data analysis,statistical analysis, and visualization related projects.You can reah me via email (ofizwop@gmail.com)
