# NHANES Analysis Project

## Project Description

This project analyzes data from the National Health and Nutrition Examination Survey (NHANES) 2021-2023. The analysis focuses on inferential statistics to investigate relationships between demographic, behavioral, and health-related variables. The findings aim to contribute insights into public health trends and risk factors.

## Requirements

To run this project, you need the following:

- Python (3.7+)
- Libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scipy
  - statsmodels

Install the required packages using:

```bash
pip install -r requirements.txt
```

## How to Run

1. Clone the repository.
2. Open and run the provided Python script `nhanes_2021_2023.py`.
3. Review the outputs for each question in the console or Jupyter Notebook.

## Analyses Performed

This project addresses the following health-related research questions:

### Question 1: Is there an association between marital status (married or not married) and education level (bachelor’s degree or higher vs. less than a bachelor’s degree)?

- **Objective:** Determine if marital status is associated with education level.
- **Methodology:**
  - Recode marital status and education level into simplified categories.
  - Create a contingency table to observe the distribution of education levels across marital status groups.
  - Perform a chi-square test to assess the statistical significance of the association.
- **Outcome:** The analysis revealed a statistically significant association between marital status and education level.

### Question 2: Is there a difference in the mean sedentary behavior time between those who are married and those who are not married?

- **Objective:** Compare the mean sedentary behavior time between married and not married individuals.
- **Methodology:**
  - Clean sedentary behavior data by removing invalid or extreme values.
  - Calculate mean sedentary behavior time for each marital status group.
  - Perform an independent t-test to compare means.
- **Outcome:** A statistically significant difference was found, with married individuals spending less time in sedentary behavior compared to those who are not married.

### Question 3: How do age and marital status affect systolic blood pressure?

- **Objective:** Assess the combined effects of age and marital status on systolic blood pressure.
- **Methodology:**
  - Clean and merge datasets for age, marital status, and systolic blood pressure.
  - Perform regression analysis to quantify the effects of age and marital status on systolic blood pressure.
- **Outcome:** Age significantly increased systolic blood pressure, and being not married was associated with a slight but significant increase in systolic blood pressure.

### Question 4: Is there a correlation between self-reported weight and minutes of sedentary behavior?

- **Objective:** Investigate the relationship between self-reported weight and sedentary behavior.
- **Methodology:**
  - Clean the data by removing invalid or extreme values for both variables.
  - Compute Pearson’s correlation coefficient to measure the strength and direction of the relationship.
- **Outcome:** A weak positive correlation was observed, indicating a slight tendency for higher weights to be associated with more sedentary behavior.

### Question 5: Does the level of education influence Vitamin D levels in adults aged 20 and older?

- **Objective:** Evaluate whether education level impacts Vitamin D status.
- **Methodology:**
  - Recode education levels and Vitamin D levels into simplified categories.
  - Create a contingency table to observe the distribution of Vitamin D levels across education levels.
  - Perform a chi-square test to assess the statistical significance of the association.
- **Outcome:** A statistically significant relationship was found, with individuals holding a bachelor’s degree or higher more likely to have sufficient Vitamin D levels.

## Key Features

- Data cleaning and preprocessing of NHANES datasets.
- Exploratory data analysis and visualizations.
- Statistical testing and hypothesis evaluation for each question.

## Results

The analysis highlights important relationships between demographic, behavioral, and health-related factors, including:
- The influence of marital status on education and health behaviors.
- Correlations between sedentary behavior and other health indicators.

## Acknowledgements

Data is sourced from the National Health and Nutrition Examination Survey (NHANES) 2021-2023.

