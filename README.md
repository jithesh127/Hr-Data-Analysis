# HR Analytics | Employee Attrition & Workforce Insights

A Python exploratory data analysis project investigating employee attrition, satisfaction, compensation, and workforce patterns.

## Project Objectives
- Understand workforce composition across departments and salary groups.
- Explore how attrition relates to satisfaction and other recorded employee attributes.
- Review data quality before interpreting results.

## Dataset
- 14,999 records and 10 columns, as reported in the analysis.
- Duplicate records were identified during data-quality checks; validate totals against the cleaned data before reuse.

## Tools & Methods
**Python · Pandas · NumPy · Matplotlib · Seaborn · Jupyter Notebook**

Data inspection, cleaning, duplicate review, filtering, grouping, aggregation, and visualization.

## Key Observations
- 3,571 employees were recorded as having left before duplicate removal.
- Lower-salary groups had higher attrition counts.
- Employees who left had lower average satisfaction scores.
- Sales had the largest employee count.
- Promotion history and work accidents were also explored.

> These are descriptive patterns, not evidence of causation. Counts can be affected by group size; compare cleaned-data attrition rates for a fairer assessment.

## How to Explore
Open the notebook(s) in this repository to follow the cleaning steps, analysis, and visualizations.

## Further Analysis
- Recalculate metrics after duplicate handling.
- Compare attrition rates by group, not counts alone.
- Test whether observed relationships remain after controlling for other factors.

---
Created by **Jithesh D** · [GitHub](https://github.com/jithesh127)