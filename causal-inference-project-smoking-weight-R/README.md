## Smoking and Weight Gain: A Causal Inference Study
Machine Learning and Causal Inference | MSc in Data Science Methodology | Barcelona School of Economics

Project idea borrowed from the book by Hernan and Robins (2021).

This project investigates the causal effect of smoking cessation on weight gain using advanced causal inference techniques. Utilizing data from the National Health and Nutrition Examination Survey Data I Epidemiologic Follow-up Study (NHEFS), the analysis explores the complex interplay between smoking behavior and weight change. By applying multiple methodological frameworks, the project provides actionable insights into the nuanced relationship between lifestyle factors and health outcomes.

### Research Objectives
To estimate the causal effect of smoking cessation on weight gain using observational data.
To assess the balance of covariates and mitigate potential confounding factors through robust statistical methodologies.
To explore the efficacy of different causal inference techniques in addressing health-related empirical questions.

### Methodologies and Findings
#### 1. Inverse Probability Weighting (IPW):
Applied stabilized and standard IP weighting to balance covariate distributions across treatment groups.
Demonstrated the effectiveness of stabilized weights in adjusting for individual propensities to receive treatment, providing a more balanced representation of quitters and non-quitters.

#### 2. Standardization:
Estimated that smoking cessation leads to an average weight gain of 3.46 kg, after adjusting for confounding variables.
Highlighted the utility of standardization in deriving causal estimates from observational studies.

#### 3. G-Estimation:
Used structural nested models to account for time-varying confounders, providing a dynamic and accurate estimate of the causal effect of smoking cessation on weight gain.
Explored the role of baseline characteristics and individual smoking intensity in weight change.

#### 4. Propensity Score Matching and Doubly-Robust Estimation:
Balanced treatment and control groups using propensity score matching to improve causal estimates.
Employed doubly-robust estimators, combining outcome and propensity score models, to enhance the reliability of results.

#### 5. Instrumental Variable Estimation:
Used cigarette price as an instrumental variable to isolate the causal effect of smoking cessation on weight gain.
Addressed the challenges of weak instruments and emphasized the importance of valid instruments in causal analysis.

### Key Contributions
Demonstrated the effectiveness of causal inference methods such as IPW, G-estimation, and propensity score matching in addressing confounding in observational studies.
Provided actionable insights into the health implications of smoking cessation, aiding public health strategies aimed at promoting healthy lifestyles.
Highlighted the importance of selecting appropriate statistical techniques tailored to the data's characteristics and research objectives.
