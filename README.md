# Student Scores Analysis 
## Project Overview
This repository contains two related portfolio projects based on the same dataset of student scores in **Math, Science, and English**.  

- **Portfolio Project 1 (Analysis & Cleaning):**  
  Focused on handling missing values, creating new performance categories, calculating averages, and performing correlation analysis between subjects.  

- **Portfolio Project 2 (Visualization with Seaborn):**  
  Expanded on the cleaned dataset to create multiple visualizations that explore distributions, group comparisons, and relationships between subjects.

---

## Objectives
- Handle missing values and clean data.  
- Create new columns for performance categories.  
- Perform correlation analysis between subjects.  
- Visualize score distributions and averages.  
- Compare student groups by performance and subject.  
- Explore relationships between subjects using scatter plots and box plots.  

---

## Skills & Tools Used
- **Python**  
- **pandas** → Data cleaning & manipulation  
- **NumPy** → Numerical operations  
- **Matplotlib & Seaborn** → Data visualization  
- **Jupyter Notebook** → Interactive coding  

---

## Key Insights
- Students with `"Excellent"` performance consistently scored highest across all subjects.  
- **Math and Science scores** show the strongest positive correlation.  
- **English scores** are moderately correlated with Math, less so with Science.  
- Visualizations revealed:
  - Clear performance group differences in subject scores.  
  - Score distributions and outliers via histograms and box plots.  
  - Relationship between Math & English strengthened when average score was added as a visual dimension.  

---

## Project Structure
student-scores-analysis/
│
├── student_scores_analysis.ipynb # Portfolio Project 1: Cleaning & Correlation
├── student_scores_visualization.ipynb # Portfolio Project 2: Seaborn Visualizations
├── student_scores.csv # Dataset used
└── README.md # Project description

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/student-scores-analysis.git
2. Open Jupyter Notebook:
   jupyter notebook
3. Run either notebook (student_scores_analysis.ipynb or student_scores_visualization.ipynb) to reproduce results.

## Future Improvements
- Add more subjects or demographic variables.
- Explore predictive modeling for student performance.
- Compare performance across schools or regions.
- Build interactive dashboards with Plotly or Tableau.

Author: Sara Barbour
GitHub:https://github.com/Sa00ra
