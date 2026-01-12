Diabetes Project
==============================

A data science project examining the association between demographic and lifestyle factors and diagnosed diabetes.

Project Overview
------------

This repository contains code, data, notebooks, and reports for analyzing and modeling diagnosed diabetes using non-clinical predictors, including demographic characteristics (e.g., age, gender) and lifestyle behaviors (e.g., physical activity, screen time, sleep duration, alcohol consumption, and smoking status).

The primary objective is to identify key lifestyle-related risk factors and develop interpretable predictive models that estimate the probability of a diabetes diagnosis without relying on laboratory or clinical measurements.

Modeling Approach
----------------

Two modeling approaches are implemented:
- Logistic Regression, used as the primary model for interpretability and risk factor analysis
- XGBoost, used as a complementary model to capture non-linear relationships and interactions

Model performance is evaluated using classification metrics appropriate for imbalanced health outcomes, with particular attention to recall.

Project Organization
------------

    ├── .idea               <- IDE configuration files
    ├── README.md           <- The top-level README for developers using this project.
    ├── data
    │   ├── raw             <- Original, immutable data files
    │   └── processed       <- Final datasets used for analysis and modeling
    │
    ├── models              <- Trained and serialized models
    │
    ├── notebooks           <- Jupyter notebooks for EDA and modeling
    │                         
    │
    ├── reports             <- Generated analysis outputs
    │   └── figures         <- Generated graphics and figures for reporting
    │
    ├── requirements.txt    <- The requirements file for reproducing the analysis environment
    │
    └── .gitignore          <- Files and folders ignored by git

--------

<p><small>
Project structure inspired by the
<a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">
cookiecutter data science project template</a>.
</small></p>
