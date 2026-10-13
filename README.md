# Credit Risk Modeling & Explainability

An exploratory Logistic Regression analysis of the German Credit Risk dataset using PDP, ICE, ALE, and permutation importance.

## Business value
Show how an analyst can inspect relationships between applicant attributes and model predictions, and communicate global and individual effects.

## Technical strengths
Python, Pandas, scikit-learn, Matplotlib, Seaborn, and ALEPython.
Missing account categories are filled as unknown, categorical fields are one-hot encoded, and the data is divided into an 80/20 training/test split.

## Target definition
The implemented mapping is good=1 and bad=0. A prediction for class 1 therefore refers to good credit status, not greater default risk.

## Explore and run
Open [the notebook](Assignment6modifications.ipynb) in Colab. Provide the German credit CSV, update the personal Drive path and course-template paths, and install the imported dependencies.

## Limitations and next steps
- Add the original dataset citation and access instructions.
- Report class balance, a majority-class baseline, bad-credit recall, F1, ROC-AUC, and calibration.
- The notebook does not currently report a full predictive-performance evaluation.
- For classifier ALE, verify the prediction function explains the intended class probability.
- Assess subgroup performance and document limitations before suggesting operational lending use.

## Project context
Developed by Yiren Shen for Duke's AIPI 590 Explainable AI course. This is a separate credit-risk project, not a duplicate of the housing-price analysis.
