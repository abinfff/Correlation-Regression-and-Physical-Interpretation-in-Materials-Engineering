
# Correlation, Regression, and Physical Interpretation in Materials Engineering

## Objective
This project demonstrates how basic data science tools can be used to analyze and interpret material behavior. The focus is on understanding correlation, applying simple linear regression, and validating results using physical reasoning rather than relying only on statistics.

---

## Problem Statement
In materials engineering, processing parameters such as temperature often influence mechanical properties like yield strength. This project studies the relationship between temperature and yield strength and answers the following questions:
- Are the variables correlated?
- How strongly does temperature affect yield strength?
- Does the statistical relationship make physical sense?

---

## Methodology
1. Simulated temperature and yield strength data
2. Visualized data using scatter plots
3. Calculated correlation to identify the relationship
4. Applied simple linear regression to quantify the effect
5. Interpreted results using materials science principles

---

## Code Explanation
Temperature is treated as the input (independent variable) and yield strength as the output (dependent variable).  
Simple linear regression is used to model their relationship because it provides clear physical interpretability.

The slope of the regression line represents how much yield strength changes per unit increase in temperature, while the intercept serves as a mathematical reference point. The results are analyzed in the context of known material behavior such as thermal softening.

---

## Key Results
- A negative correlation was observed between temperature and yield strength
- Regression slope: **−0.113 MPa/K**
- This indicates that yield strength decreases as temperature increases
- The trend is physically reasonable due to increased dislocation mobility at higher temperatures

---

## Important Concept
Correlation alone does not imply causation.  
Statistical relationships must be supported by physical mechanisms and engineering judgment before drawing conclusions.

---

## Tools Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## Conclusion
This project highlights the importance of combining data analysis with domain knowledge. Simple statistical models, when interpreted correctly, can provide valuable insights into material behavior while avoiding misleading conclusions.
