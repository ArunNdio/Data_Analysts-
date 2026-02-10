# Student Performance Analysis

This project analyzes student performance data from the "Student Performance" dataset, focusing on factors influencing final grades (G3). The analysis includes data cleaning, statistical summaries, correlations, and visualizations.

## Dataset

The dataset used is `student-mat.csv`, which contains information about students' demographics, study habits, and academic performance in mathematics.

## Analysis Overview

The Jupyter notebook (`student_analysis.ipynb`) performs the following steps:

1. **Data Loading and Exploration**:
   - Load the dataset using pandas.
   - Display basic information: shape, info, null values, and duplicates.
   - Remove duplicates if any.

2. **Statistical Analysis**:
   - Calculate the mean final grade (G3).
   - Count students with grades above 15.
   - Compute correlation between study time and final grade.
   - Group and calculate average grades by gender.

3. **Visualizations**:
   - Histogram of final grades distribution.
   - Scatter plot of study time vs. final grade.
   - Bar plot of average grade by gender.

## Requirements

- Python 3.x
- Libraries: pandas, matplotlib, seaborn

Install dependencies using:
```
pip install pandas matplotlib seaborn
```

## Usage

1. Ensure the `student-mat.csv` file is in the appropriate path (e.g., `C:\Users\akash\Downloads\student\`).
2. Open the `student_analysis.ipynb` notebook in Jupyter.
3. Run the cells sequentially to execute the analysis and view the plots.

## Results

- Mean final grade: [Insert value from notebook, e.g., calculated mean]
- Correlation between study time and G3: [Insert value]
- Average grades by gender: [Insert values]

## Visualizations

The notebook generates three plots:
- Distribution of Final Grades
- Study Time vs. Final Grade
- Average Grade by Gender

## Contributing

Feel free to contribute by improving the analysis or adding more features.

## License

This project is for educational purposes.
