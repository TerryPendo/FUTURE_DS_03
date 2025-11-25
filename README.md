# Student Feedback Sentiment & Rating Analysis

**Project:** Student Feedback Survey — Sentiment and Rating Analysis  

---

## Overview
This project analyzes student feedback ratings to identify strengths and improvement areas in course delivery. The dataset contains ratings for instructor knowledge, clarity, use of presentations, assignment difficulty, student support, course structuring, and course recommendations.

The deliverables:
- A Jupyter/Colab notebook containing full analysis and visuals.
- This README summarizing findings and recommendations.

---

## Data
- Source: Kaggle — *Student Feedback Survey Responses* 
- Key fields: `student_id`, `well_versed_with_subject`, `explains_concept_well`, `use_of_presentations`, `degree_of_difficulty_of_assignments`, `solves_doubts_willingly`, `structuring_of_course`, `provides_support_for_students`, `course_recommendations`

---

## Key Findings
- **Top strengths**
  - *Well versed with the subject*
  - *Explains concepts in an understandable way*
  - *Use of presentations*
- **Main weakness**
  - *Degree of difficulty of assignments* — lowest average rating and high consensus that assignments are difficult.
- **Correlation analysis**
  - Overall correlations between items are weak; *explains_concept_well* shows the strongest positive relationship with course recommendations.
- **Sentiment summary (scaled from numeric ratings)**
  - Positive: **17.4%**
  - Neutral: **81.8%**
  - Negative: **0.8%**

---

## Visualizations Included
1. Average Ratings per Category (bar chart)  
2. Distribution of Ratings (histograms)  
3. Correlation Heatmap  
4. Boxplots (variability across categories)  
5. Sentiment Distribution (pie + bar charts)  

> **Preview images:** (include screenshots below or link to `/images` folder)
- `images/avg_ratings.png`
- `images/heatmap.png`
- `images/boxplots.png`
- `images/sentiment_pie.png`

---

## Recommendations
1. **Revise assignment design** — provide clearer rubrics, examples, and scaffolded tasks.  
2. **Standardize presentation materials** — adopt a template and share best practices among instructors.  
3. **Improve course structure** — ensure clear alignment between lectures, materials, and assessment.  
4. **Expand student support channels** — scheduled office hours, Q&A sessions, or peer tutoring.  
5. **Collect qualitative feedback** — add open-ended comment fields in future surveys for richer insight.

---

## How to reproduce
1. Open the notebook `student_feedback_analysis.ipynb` in Google Colab or Jupyter.  
2. Install required libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn` (optional).  
3. Place the dataset CSV in the notebook directory or link to the Kaggle dataset.  
4. Run the cells in order (data cleaning → EDA → visuals → sentiment conversion → insights).

---

## Contact
- Teresia Pendo — terry.mwagona@gmail.com  
- GitHub: `https://github.com/TerryPendo/FUTURE_DS_03`


