# Steam Player Engagement Analysis (Ongoing Thesis)

⚠️ This repository contains an **ongoing graduate thesis project**. Analysis and results will continue to be updated as the project progresses.

The goal of this project is to understand how early player activity, community response, and game characteristics relate to **lifetime playtime and sustained engagement**.

This thesis is **ongoing and will continue to evolve as additional modeling, validation, and interpretation are completed throughout the semester.**

---

# Research Question

What early indicators best predict long-term engagement for games released on Steam?

Specifically, this project investigates whether factors such as:

- Early player activity
- Review activity
- Player recommendations
- Game genre
- Launch traction (peak concurrent players)

can help explain **why some games maintain long-term engagement while others quickly decline.**

---

# Dataset

**Dataset:** Steam Games, Reviews, and Player Activity Dataset (2023–2024)

The dataset contains metadata and player engagement metrics for thousands of games available on Steam.

Key variables include:

- Estimated owners
- Peak concurrent players (CCU)
- Player reviews (positive and negative)
- Player recommendations
- Average playtime (two weeks and lifetime)
- Genre classifications
- Game pricing and release information

These variables allow us to analyze both **player behavior and game characteristics**.

---

# Current Project Status

This thesis is currently in progress. The work completed so far includes:

- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Feature engineering and log transformations
- Multicollinearity diagnostics
- Baseline regression modeling
- Two-stage engagement modeling
- Regularization testing (Ridge and Lasso)
- Time-aware validation
- Feature importance analysis
- Genre interaction analysis

Future work will focus on refining the modeling framework and synthesizing insights from the results.

---

# Key Early Findings

Initial modeling results suggest that **community engagement metrics are the strongest predictors of long-term playtime**.

Important predictors include:

- Player recommendations
- Total review activity
- Early playtime shortly after release

Early engagement also appears to influence some genres more strongly than others. For example, **Free-to-Play and Casual games show stronger relationships between early engagement and long-term playtime**.

---


# Methods Used

The analysis uses Python and standard data science tools including:

- pandas
- numpy
- scikit-learn
- statsmodels
- matplotlib

Modeling techniques include:

- Linear regression
- Two-stage modeling (logistic + regression)
- Regularized regression (Ridge / Lasso)
- Time-based validation
- Interaction analysis

---

# Reproducibility

All analysis is conducted in Jupyter notebooks and can be reproduced using the provided code.

The project is structured to document the **progression of the thesis week by week**.

---

# Author

Joshua Cochran  
INFO-I 492 – Data Science Capstone  
Indiana University  

