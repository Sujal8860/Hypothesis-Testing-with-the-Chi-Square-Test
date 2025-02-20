# Hypothesis-Testing-with-the-Chi-Square-Test

This repository demonstrates how to perform hypothesis testing using the Chi-Square Test of Independence with two real-world examples.

## Example 1: Fair Die Test
- **Objective:** Test if a die is fair.
- **Data:** Observed frequencies: [22, 17, 20, 26, 22, 13]
- **Method:** Compare the chi-square statistic to the critical value at 5% significance.
- **Result:** With a chi-square value of ~5.10 (critical value ~11.07), we fail to reject the null hypothesis. The die is fair.

## Example 2: Gender and Music Preference
- **Objective:** Test if there is an association between gender and music preference.
- **Data:**  
  | Genre     | Male | Female |
  | --------- | ---- | ------ |
  | Pop       | 40   | 35     |
  | Hip Hop   | 45   | 30     |
  | Classical | 25   | 20     |
  | Rock      | 10   | 30     |
- **Method:** Create a contingency table, compute the chi-square statistic, and compare it with the critical value.
- **Result:** With a chi-square statistic of ~13.79 (critical value ~7.81), we reject the null hypothesis. There is a significant association between gender and music preference.

## Code
The repository includes Jupyter Notebook files with complete code for both examples.
