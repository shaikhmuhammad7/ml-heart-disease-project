# Heart Disease Classification - To be updated soon

Given clinical parameters about a patient, build predictive models using machine learning classifiers that can predict whether a patient has heart disease or not.
---


<h2>Overview</h2>

A concise walkthrough of my project on the classic Heart Disease dataset 


## This project consists:  

- ML models with cross-validated metrics and feature explanations 

- Power BI dashboard with clean KPIs, readable labels, and insights that tie features to clinical intuition (cholesterol, BP, chest pain). (To be uploaded)

= ML models with cross validated metrics and exploratory data analysis.

## Overview of insights 

Class balance: roughly even (slightly more positive cases), so rates are comparable across groups.

Age: cases cluster in the mid-40s to early-60s.

Sex: more male cases in absolute terms; rates are shown so the comparison is fair.

Chest pain type (cp): strong signal — Non-anginal pain tends to have higher disease rate, Asymptomatic the lowest (in this sample).

Cholesterol & Resting BP: positive class skews higher; reference lines highlight typical thresholds (200 mg/dL, 130/140 mmHg).

Stress response: higher ST depression (oldpeak) and lower max heart rate (thalach) associate with positive cases.

These patterns motivated the final feature set used in modeling.

## Model performance:

Best model: K Nearest Neighbor

Validation: stratified k-fold CV

## Limitations & next steps

Sample size (n=303) — results are indicative; external validation is planned.

