# Student Feedback Sentiment & Rating Analysis

**Project:** Student Feedback Survey — Sentiment and Rating Analysis  

---

## Overview
This project analyzes student feedback ratings to identify strengths and improvement areas in course delivery. The dataset contains ratings for instructor knowledge, clarity, use of presentations, assignment difficulty, student support, course structuring, and course recommendations.

The deliverables:
- A Jupyter/Colab notebook containing full analysis and visuals.
- This README summarizing findings and recommendations.

---
## Tools and Libraries
- Google Colab/Jupyter Notebook for Coding
- pandas- Data manipulation
- seaborn/matplotlib - visualization

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

> **Preview images:** 
- *Figure 1: Average ratings per feedback category.*
![Average Ratings](images/avg_ratings.png)

-*Figure 1: Distribution of ratings Histogram.*
-

-*Figure 2: Correlation Heatmap of Feedback Ratings.*
- `images/heatmap.png`

- *Figure 3: Boxplot of Student Feedback ratings.*
- `images/boxplots.png`

- *Figure 4: Piechart of Sentiment Analysis.*
- `images/sentiment_pie.png`

---

## Recommendations
1. **Revise assignments** — adjust scope or provide clearer rubrics and example solutions to reduce perceived difficulty.  
2. **Standardize presentations** — create a presentation template and best-practice guidelines for instructors to reduce variability.  
3. **Strengthen course structure** — review syllabus flow to ensure alignment between taught material and assignments.  
4. **Increase student support** — offer scheduled doubt-solving sessions or office hours to raise satisfaction and recommendations.  
5. **Collect open-text feedback next time** — qualitative comments will improve understanding of *why* students feel neutral.

## Next steps (for future cycles)
- Run targeted surveys about assignments and presentations.
- A/B test a revised assignment rubric with a small student group.
- Track changes in overall satisfaction and recommendation rate after interventions.
---

## How to reproduce
1. Open the notebook `student_feedback_analysis.ipynb` in Google Colab or Jupyter.  
2. Install required libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn` (optional).  
3. Place the dataset CSV in the notebook directory or link to the Kaggle dataset.  
4. Run the cells in order (data cleaning → EDA → visuals → sentiment conversion → insights).

---

## Contact
- Teresia Pendo — terry.mwagona@gmail.com  
- Linkedin: `(https://www.linkedin.com/in/teresiamwagonadata)`


