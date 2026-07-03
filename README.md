# Faculty Development Program (FDP) Post-Training Survey Analysis

A comprehensive data analysis project evaluating participant feedback from the **Wadhwani Entrepreneurship Network (WEN) Philippines Faculty Development Program (FDP)**. This study combines statistical analysis and qualitative text mining to assess participant satisfaction, evaluate the reliability of the survey instrument, compare training cohorts, and generate evidence-based recommendations for program improvement.

---

## Project Overview

This project analyzes post-training evaluation survey responses collected from faculty members who completed the Faculty Development Program between **2024 and 2026**.

The primary objectives are to:

- Measure participant satisfaction across key evaluation dimensions
- Assess the reliability of the survey instrument
- Compare satisfaction between the 2025 and 2026 training cohorts
- Analyze open-ended responses to identify recurring themes
- Provide actionable recommendations for future program improvements

---

## Dataset

The analysis utilizes two datasets:

### 1. FDP Post-Training Evaluation Survey
- 23 Likert-scale evaluation questions
- 3 open-ended feedback questions
- 671 valid survey responses
- Responses collected from 38 FDP batches

### 2. Consolidated Faculty Master List
- 1,820 faculty records
- 263 institutions nationwide
- Used for year classification and data validation

---

## Research Questions

This project aims to answer the following questions:

1. What is the overall participant satisfaction with the FDP?
2. Is the survey instrument reliable?
3. Are there significant differences between the 2025 and 2026 cohorts?
4. What recurring themes emerge from participant feedback?
5. What recommendations can improve future FDP implementations?

---

## Methodology

### Data Cleaning

- Removed unnecessary columns
- Standardized survey responses
- Converted timestamps
- Cross-referenced survey batches with faculty records
- Classified training year
- Handled missing values

---

### Quantitative Analysis

- Descriptive Statistics
- Category-Level Analysis
- Item-Level Analysis
- Cronbach's Alpha
- Welch's Independent Samples t-test
- Pearson Correlation

---

### Qualitative Analysis

- Text preprocessing
- Keyword frequency analysis
- Word cloud generation
- Theme identification

---

## Tools & Technologies

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- WordCloud
- OpenPyXL
  
## Key Findings

### Survey Reliability

- Overall Cronbach's Alpha: **0.9691**
- All evaluation categories demonstrated excellent internal consistency.

### Overall Satisfaction

Participants reported consistently high satisfaction across all evaluation dimensions.

Highest-rated category:

- Overall Satisfaction

Lowest-rated category:

- Student Engagement

### Cohort Comparison

- Compared the 2025 and 2026 training cohorts using Welch's t-test.
- Although slight decreases were observed across several categories, none were statistically significant (p > 0.05).

### Qualitative Insights

Common strengths identified:

- Hands-on learning
- Venture creation activities
- Facilitator support
- Practical teaching applications

Common improvement areas:

- Platform navigation
- Localization of examples
- Scheduling flexibility
- Communication during online sessions

---

## Visualizations

The notebook automatically generates:

- Category score bar charts
- Survey item rankings
- Year-over-year comparison charts
- Correlation heatmaps
- Word clouds
- Frequency tables
- Summary reports

---

## Recommendations

Based on the analysis, several evidence-based recommendations were proposed, including:

- Improve platform navigation
- Localize learning materials for the Philippine context
- Enhance participant engagement strategies
- Improve communication for online cohorts
- Introduce additional survey questions to capture teaching confidence and online learning experiences

---

## Skills Demonstrated

This project demonstrates proficiency in:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Statistical Analysis
- Survey Analytics
- Reliability Testing
- Data Visualization
- Text Mining
- Natural Language Processing (Basic)
- Research Reporting
- Program Evaluation
- Python for Data Science

---

## Future Improvements

Potential enhancements include:

- Interactive dashboards using Plotly or Power BI
- Automated report generation
- Topic modeling (LDA)
- Sentiment analysis
- Predictive models for participant satisfaction
- Deployment as a Streamlit dashboard

---

## Disclaimer

This repository is intended for educational and portfolio purposes. The findings and recommendations are based solely on the analyzed survey responses and are presented to demonstrate data analysis and program evaluation techniques.

---

## Author

**Lady Jean Y. Geverola**

BS Data Science  
University of the Philippines Mindanao

```
Python • Data Analysis • Statistics • Survey Analytics • Data Visualization
```
