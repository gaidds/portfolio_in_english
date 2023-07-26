# Evaluation of A/B test results by various methods
Project link:
[ipynb](https://github.com/gaidds/portfolio/blob/main/Analysing%20AB%20test/project_a_b_test.ipynb)

## Description of the project

- **Goal:**
    - prioritization of 9 hypotheses to increase the revenue of an online store using the `ICE` and `RICE` frameworks,
    - analysis of A/B test results.
## Data
- The file `hypothesis` contains 9 hypotheses for increasing the revenue of an online store with the specified parameters Reach, Impact, Confidence, Effort.
- The files `orders` and `visitors` describe the results of the A/B test that will need to be analyzed.

## Skills and Tools
- Python
- Pandas
- Matplotlib
- SciPy
- A/B testing
- Testing of statistical hypotheses

## Conclusion

- Calculated cumulative characteristics for both segments of the A / B test,
- Conducted Mann-Whitney statistic tests:
     - segment B performs better in the average number of orders per visitor,
     - no statistically significant differences were found in the average check for the segments,
     - It was decided to stop the A / B test.
