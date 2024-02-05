## Shift theft Analysis
The Shift theft Analysis project is a Python script designed to explore and analyze the distribution of theft for employees working different shifts (1st or 2nd) throughout the week. The script generates a simulated dataset, creates insightful visualizations, and conducts statistical tests to compare income distributions between shifts on each day.

## Project Overview
### Data Generation
The script generates a dataset representing daily income, taking into account factors such as the day of the week and the shift worked. The simulated income values incorporate variations influenced by different weekdays and shift types.

## Visualizations
1. Line Plot:

    - Presents a line plot depicting the income after potential stealing for both shifts, providing a visual comparison of income distributions.
2. KDE Plots:

     - Utilizes Kernel Density Estimate (KDE) plots to visualize the distribution of income for each day of the week.
    - Separates the plots based on the shift worked (1st or 2nd), offering insights into the differences in income patterns.
## Statistical Analysis
1. T-Test:

    - Conducts t-tests to statistically compare the means of income distributions between employees working different shifts on each day of the week.
    - Outputs t-statistic, p-value, and a decision on whether to reject or accept the null hypothesis.
2. Confidence Intervals:

    - Calculates and prints confidence intervals for the income difference between shifts with a 95% confidence level.
    - Provides additional insights into the range of potential income disparities.
## Getting Started
### To use the Shift Income Analysis project:

- Clone the repository.
- Navigate to the project directory.
- Run the script with python shift_analysis.py.
## Results
The Shift Income Analysis script yields a comprehensive understanding of income distribution patterns based on shifts and weekdays. The visualizations and statistical tests offer valuable insights for assessing potential differences in earnings for employees on different shifts.