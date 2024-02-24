# Sleep Quality Analysis

This repository contains code for analyzing sleep quality based on various criteria such as sleep duration, deep sleep percentage, light sleep percentage, awakenings, and sleep efficiency. The analysis involves grading each criterion and computing an aggregated sleep quality score for each entry in the dataset.

## Grading Criteria

The grading criteria for assessing sleep quality are defined as follows:

- `grade_sleep_duration`: Grades sleep duration based on whether it's greater than or equal to 7 hours.
- `grade_deep_sleep_percentage`: Grades deep sleep percentage based on whether it falls within the range of 13% to 23%.
- `grade_light_sleep_percentage`: Grades light sleep percentage based on whether it falls within the range of 45% to 55%.
- `grade_awakenings`: Grades awakenings based on whether they are less than or equal to 1.
- `grade_sleep_efficiency`: Grades sleep efficiency based on whether it's greater than or equal to 0.85.

## Tools Used

The analysis is performed using the following tools:

- **Python**: Python programming language is used for data manipulation, analysis, and visualization.
- **Pandas**: Pandas is used for data manipulation, including loading the dataset, handling missing values, and performing calculations.
- **NumPy**: NumPy is used for numerical computing and handling arrays, which is useful for various data manipulation tasks.
- **Matplotlib**: Matplotlib is used for creating visualizations, such as histograms, to understand the distribution of sleep quality scores.
- **Seaborn**: Seaborn is used for creating more visually appealing and informative statistical visualizations.

## Applying Grading Functions

The grading functions are applied to the respective columns in the dataset to create grade columns for each criterion. These grade columns contain binary values (0 or 1) indicating whether each criterion meets the specified grading criteria.

## Computing Sleep Quality Score

A sleep quality score is computed by summing up the grades for each criterion. This provides an overall assessment of sleep quality for each entry in the dataset.

## Visualization

A histogram is plotted using Matplotlib and Seaborn to visualize the distribution of sleep quality scores across the dataset. This visualization helps in understanding the distribution of sleep quality and identifying patterns within the data.

### Happy Learning !
