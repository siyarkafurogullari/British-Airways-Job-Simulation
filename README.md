# ✈️ British Airways | Data Science & Operational Analytics Portfolio

**Translating airline operations and passenger data into actionable business intelligence.**

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=flat-square&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML%20Modeling-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Wrangling-150458?style=flat-square&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Forage](https://img.shields.io/badge/Forage-Job%20Simulation-00A99D?style=flat-square)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-lightgrey?style=flat-square)

---

## 📊 Executive Summary

This repository showcases two applied data science projects completed as part of the **British Airways Data Science Job Simulation** on the Forage platform (August 2026). The portfolio demonstrates end-to-end capability across **operations analytics** and **predictive customer modeling** — from rule-based capacity design for airport lounge operations, to a supervised machine learning pipeline forecasting passenger booking conversion. Together, these projects illustrate the ability to translate raw operational and behavioral data into decisions that matter to commercial and operations stakeholders at scale.

---

## 🔍 Core Projects

### Project 01 — Heathrow Terminal 3 Lounge Capacity & Eligibility Modeling

#### Objective
Design a scalable, rule-based capacity demand framework for lounge operations at Heathrow Terminal 3, driven by flight schedules and passenger tier allocations, in order to reduce overcrowding risk and improve service-level predictability during peak travel periods.

#### Tech Stack
`Python` · `Pandas` · `NumPy` · `Jupyter Notebook` · Rule-Based Logic Design

#### Methodology / Approach
- Segmented incoming and outgoing flights into **short-haul** and **long-haul** distance categories to reflect differing passenger dwell-time and lounge-usage patterns.
- Mapped passenger tier allocations (e.g., loyalty status, cabin class) against flight schedules to model expected lounge demand.
- Identified **peak-hour operational bottlenecks** by aggregating expected arrivals against fixed lounge capacity thresholds.
- Structured eligibility logic as a reusable, rule-based framework capable of scaling across additional terminals or lounges.

#### Key Findings
- Long-haul arrivals concentrated in specific banked time windows, creating disproportionate capacity pressure relative to short-haul traffic.
- A small number of peak-hour windows accounted for the majority of projected capacity breaches, pointing to targeted scheduling or capacity interventions rather than blanket expansion.
- The rule-based structure generalizes cleanly, allowing the eligibility framework to be extended to other terminals or lounge tiers with minimal rework.



---

### Project 02 — Predictive Customer Conversion Modeling

#### Objective
Forecast passenger booking behavior and conversion probability using historical search and purchase data, enabling data-driven prioritization of marketing spend and customer targeting.

#### Tech Stack
`Python` · `Scikit-Learn` · `Random Forest Classifier` · `Pandas` · `NumPy` · `Seaborn`

#### Methodology / Approach
- Cleaned and engineered features from a dataset of **50,000+ historical search and purchase records**.
- Built a supervised classification pipeline using a **Random Forest Classifier** to predict booking conversion likelihood.
- Evaluated model performance using **ROC-AUC** as the primary metric, alongside standard classification diagnostics.
- Conducted **feature importance analysis** to identify which variables most strongly influenced conversion outcomes.
- Synthesized technical results into a stakeholder-facing **executive briefing deck**, reframing model outputs as concrete marketing and retargeting actions.

#### Key Findings
- The classification pipeline achieved a **solid baseline ROC-AUC of ~0.78**, indicating strong discriminative power between converting and non-converting search sessions.
- **Origin country** and **specific route vectors** emerged as the primary predictive drivers of conversion, outweighing other behavioral and demographic features.
- These findings directly informed a proposed **geo-marketing allocation strategy**, concentrating spend on high-propensity origin markets.
- A **high-intent retargeting framework** was recommended for route-level segments showing elevated conversion probability but incomplete purchase funnels.


---

## 🛠️ Technical Competencies & Tooling

| Category | Skills & Tools |
|---|---|
| **Machine Learning & Statistical Modeling** | Random Forest Classification, Feature Importance Analysis, ROC-AUC Evaluation, Train/Test Pipeline Design, Rule-Based Systems Design |
| **Python Data Stack** | Pandas, NumPy, Scikit-Learn, Seaborn, Jupyter Notebook |
| **Business & Presentation Design** | Executive Summary Construction, Stakeholder Communication, PowerPoint Deliverable Design, Insight-to-Action Translation |
| **Domain Expertise** | Airline Commercial Operations, Passenger Segmentation, Lounge Capacity Planning, Aviation Customer Behavior Analytics |

---

## ✅ Certification & Verification

> Both projects in this repository were completed as part of the **British Airways Data Science Job Simulation**, hosted on the **Forage** virtual experience platform.
>
> **Issued:** August 2026
> **Credential ID:** `6a6e6e6a1ebe2d46f8e6f198`

---

## 🤝 Connect

[LinkedIn](https://www.linkedin.com/in/siyarkfl) 
---

⭐ If you found this portfolio insightful, consider starring the repository.
