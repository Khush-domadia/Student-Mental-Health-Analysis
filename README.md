# 🧠 Student Mental Health Analytics Project

## 📋 Project Overview

This project analyzes student mental health patterns using machine learning and statistical techniques to identify at-risk students and provide actionable insights for university intervention programs.

### 🎯 Key Findings
- **60.8% of students** are at high risk for mental health issues
- **Random Forest model** achieves 89.4% recall for identifying at-risk students
- **Course-specific vulnerabilities** identified across different academic programs
- **4 distinct student clusters** discovered for targeted interventions

## 🔬 Methodology

### Dataset
- **7,022 student records** with 20 comprehensive features
- **Mental health outcomes**: Depression, Anxiety, and Stress scores (0-5 scale)
- **Predictive factors**: Demographics, academic performance, lifestyle, and support systems

### Analysis Pipeline
1. **Exploratory Data Analysis** - Comprehensive data quality assessment and pattern identification
2. **Data Preprocessing** - Missing value imputation, feature encoding, and scaling
3. **Predictive Modeling** - Random Forest and Logistic Regression with cross-validation
4. **Clustering Analysis** - K-means segmentation of student mental health profiles
5. **Statistical Validation** - Chi-square tests and correlation analysis

## 📊 Model Performance

| Model | Accuracy | Precision | Recall | F1-Score |
|-------|----------|-----------|--------|----------|
| **Random Forest** | 61.4% | 62.9% | **89.4%** | 73.8% |
| **Logistic Regression** | 61.4% | 66.9% | 72.2% | 69.4% |

> The **Random Forest model's 89.4% recall** is particularly valuable for mental health screening, successfully identifying 9 out of 10 high-risk students.

## 🎓 Key Insights

### Course-Specific Risk Patterns
- **Computer Science**: Highest depression scores (3.30 average)
- **Law Students**: Highest anxiety levels (3.23 average)  
- **Medical Students**: Highest stress levels (3.21 average)

### Critical Risk Factors
1. **Sleep Quality** - Strong predictor of mental health outcomes
2. **Financial Stress** - Significant correlation with overall risk
3. **Social Support** - Low support associated with higher risk profiles
4. **Academic Program** - Course-specific vulnerability patterns identified

### Student Segmentation
- **4 distinct mental health clusters** identified through K-means analysis
- Each cluster represents different risk profiles requiring tailored interventions
- Enables targeted resource allocation and personalized support strategies

## 🏛️ University Recommendations

### Immediate Actions
1. **Implement Predictive Screening** - Deploy ML models during orientation and semester transitions
2. **Program-Specific Interventions** - Target high-risk academic programs with specialized support
3. **Sleep Hygiene Programs** - Campus-wide education given sleep quality's predictive power
4. **Financial Counseling Integration** - Combine financial and mental health services

### Implementation Roadmap
- **Phase 1**: Pilot screening with incoming students
- **Phase 2**: Deploy targeted interventions by cluster
- **Phase 3**: Evaluate effectiveness and refine models
- **Phase 4**: Scale successful programs university-wide

## 🛠️ Technical Stack

### Libraries & Tools
```python
# Data Analysis
pandas, numpy, matplotlib, seaborn

# Machine Learning  
scikit-learn (RandomForest, LogisticRegression, KMeans)
- Model validation and performance metrics
- Feature importance analysis
- Clustering with silhouette analysis

# Statistical Analysis
scipy.stats (chi-square tests, correlations)
```

### Files Structure
```
📁 Student-Mental-Health-Analytics/
├── 📊 Data_Analytics_Project.ipynb     # Complete analysis notebook
├── 📈 students_mental_health_survey.xlsx  # Dataset (7,022 records)
├── 📄 Student-Mental-Health-Final-Report.docx  # Comprehensive report
└── 📖 README.md                        # This file
```

## 🎯 Project Impact

### Academic Excellence
- **Comprehensive Analysis**: 7,022+ student records across 20 mental health factors
- **Multiple Methodologies**: Combines supervised learning, unsupervised learning, and statistical validation
- **Real-World Application**: Addresses critical student mental health crisis with actionable insights

### Statistical Rigor
- **Chi-square validation** of categorical associations (p < 0.001 for course relationships)
- **Train-test validation** with stratified sampling
- **Feature importance analysis** identifying key intervention targets
- **Silhouette analysis** for optimal cluster determination

## 🚀 How to Run

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/student-mental-health-analytics
cd student-mental-health-analytics
```

2. **Install dependencies**
```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy openpyxl
```

3. **Open Jupyter notebook**
```bash
jupyter notebook Data_Analytics_Project.ipynb
```

4. **Run all cells** to reproduce the complete analysis

## 🔍 Key Results Summary

- **Mental Health Crisis**: 60.8% of students require intervention
- **Predictive Success**: 89.4% recall rate for identifying at-risk students  
- **Actionable Insights**: Course-specific patterns and lifestyle predictors identified
- **Scalable Solution**: Framework ready for university-wide implementation

## 📚 Academic Context

This project was developed as part of a comprehensive data analytics course, demonstrating:
- **Advanced statistical modeling** techniques
- **Real-world problem solving** with social impact
- **Professional data science workflow** from EDA to recommendations
- **Academic rigor** with proper validation and interpretation

## 🤝 Contributing

This project represents academic coursework showcasing data analytics capabilities. For educational purposes, suggestions and discussions about methodology are welcome through GitHub issues.

## 📄 Citation

If using this analysis for academic purposes, please cite:
```
Student Mental Health Analytics: A Multi-Factor Analysis for Early Intervention
[Your Name], 2025 - Data Analytics Course Project
```

---

*This project demonstrates the power of data analytics in addressing critical social issues, specifically the student mental health crisis affecting universities worldwide.*
