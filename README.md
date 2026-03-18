# Mortgage Default Risk Modeling

I built a Probability of Default (PD) model using mortgage loan data to estimate the likelihood of borrowers becoming **90+ days delinquent**.

The analysis reflects a typical credit risk workflow, where loan-level performance data is transformed into a **portfolio-level risk model** to support lending decisions and risk monitoring.

---

## Scope of Work

- Constructed a **loan-level dataset** from raw mortgage performance data using DuckDB SQL  
- Defined default as **90+ days past due (DPD)**  
- Built a **logistic regression PD model** using origination characteristics  
- Evaluated model discrimination using **ROC-AUC**  
- Segmented the portfolio into **risk deciles**  
- Identified key drivers of mortgage default risk  

---

## Model Performance

**ROC-AUC: 0.817**

The model demonstrates strong discriminatory power, correctly ranking defaulted loans above non-defaulted loans approximately **81.7% of the time**.

---

## Key Insight

Default rates increase consistently across risk deciles, indicating that the model effectively differentiates between low-risk and high-risk borrowers.

---

## Tools

Python  
DuckDB SQL  
Pandas  
Scikit-learn  

---

## Notebook

Full analysis and implementation:

`mortgage_default_risk_model.ipynb`

---

## Author

Naomi Wanjiru  
Credit Risk Analytics | Economics & Statistics
