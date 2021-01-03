# LGD-models

This notebook was created using the database from the book: Deep Credit Risk - Machine Learning in Python, Harald Scheule, Daniel Rösch (2020).
The theoretical framework was based on the book: IFRS 9 and CECL Credit Risk Modelling and Validation, Tiziano Bellini (2019).

In this study Loss given default (LGD) is defined as a ratio of losses to an exposure at default. The LGD explored in this notebook was based on workout LGDs and assumed no discounting of cash flows. The periods have been deidentified.

The modelling approach follows order given below:
1. Exploratory Data Analysis 
2. Prinicpal Component Analysis
3. Microstructure-approach with Probability of Cure
4. Microstructure-approach with Loss Severity
5. Conditional Evaluation of Loss Severity given time since default
6. Conditional Evaluation of Loss Severity given Probability of Cure
7. Microstructure-approach with macroeconomic variables
8. Tobit Regression
9. Beta Regression
10. Mixture-model approach
11. Machine Learning Models(Regression Tree, Random Forest, Generalized Boosted Regression)
