# Study Concentration Behavior Modeling (Design of Experiments)

This project applies statistical design of experiments (DOE) techniques to identify how study habits—like location, method, and social interaction—impact the concentration span of students. The analysis is based on a 2³ full-factorial design using manually collected data from 108 participants.

---

## 🎯 Objectives

- Investigate three key factors: study location, study method, and social interaction
- Use a full-factorial 2³ Completely Randomized Design (CRD)
- Measure and model impact on concentration span (in minutes)
- Interpret main effects and interactions using ANOVA and post-hoc tests

---

## 🧪 Experimental Factors

| Factor              | Levels                                     |
|---------------------|---------------------------------------------|
| Study Location (A)  | Home Desk (0) vs. Outdoor Space (1)         |
| Study Method (B)    | Written Notes (0) vs. Digital Notes (1)     |
| Social Interaction (C) | Alone (0) vs. With Peer/Group (1)       |

---

## 📊 Analysis Summary

- Used **2³ factorial model** and ANOVA to examine main effects and interactions
- **Significant main effects**: Study Method (p < 0.001), Social Interaction (p < 0.01)
- **Non-significant**: Study Location (p = 0.159)
- **Significant interactions**:
  - Study Location × Social Interaction (p < 0.001)
  - Study Method × Social Interaction (p < 0.01)
  - 3-way Interaction A×B×C (p < 0.001)
- **Model R² = 35.8%**, Adjusted R² = 30.6%

---

## 🛠️ Tools & Techniques

- Statistical Design: Full-factorial 2³ CRD
- ANOVA & F-Tests (between-subjects)
- Pairwise comparison (Tukey HSD)
- Data visualization (bar plots, error bars)
- Software: MS Excel, SPSS, manual calculations

---

## 📎 Key Files

| File | Description |
|------|-------------|
| `DOE_project_report.pdf` | Full project report with introduction, methods, results, and discussion |
| `concentration_data.xlsx` (link in report) | Original dataset (108 responses) |
| `model_outputs.xlsx` | Summary tables, ANOVA results, interaction plots |

---

## 📌 Key Insights

- **Digital notes** led to significantly longer concentration spans than written notes  
- **Studying in groups** can improve or reduce span depending on location and method  
- **Outdoor group study using digital tools** may reduce focus vs. solo indoor study

---

## 👨‍🎓 Authors

- Dhruv Goel  
- Pratham, Gargi, Upali, Samridhi  
- Supervisor: Prof. Vandana Sarin Walia (Dept. of Statistics, Kirori Mal College)

---

## 📚 References

1. Montgomery, D.C. – *Design and Analysis of Experiments*  
2. Das & Giri – *Design and Analysis of Experiments*  
3. IIT Kanpur DOE Notes (Dr. Shalabh)

---


