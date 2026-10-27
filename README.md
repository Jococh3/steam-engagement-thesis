# Steam Player Engagement Analysis

A data science thesis examining how early player activity, community response, and game characteristics relate to long-term playtime for games released on Steam.

## Research question

Which early signals are associated with sustained player engagement? The analysis considers early playtime, review activity, recommendations, peak concurrent players, genre, and game characteristics.

## Data

The project uses a Steam games, reviews, and player activity dataset described in the thesis materials as covering 2023–2024. The repository contains eight weekly progress notebooks and a thesis paper draft; the dataset itself is not included, and the current README does not identify a source URL or license. Add the exact dataset citation and usage terms before claiming that a fresh checkout is fully reproducible.

## Methods

The notebooks document exploratory analysis and modeling with Python, pandas, NumPy, scikit-learn, statsmodels, and matplotlib. Methods described in the project include:

- Linear regression
- Two-stage modeling (logistic regression followed by regression)
- Ridge and Lasso regularization
- Time-based validation
- Interaction analysis

## Findings summarized in the project

The current project summary identifies recommendations, review activity, and early playtime as important predictors of lifetime playtime. It also reports stronger relationships between early engagement and long-term playtime for Free-to-Play and Casual games.

These are associations in observational data; they do not establish that early engagement causes long-term engagement. The current summary does not include a compact table of numerical estimates or validation scores, so those should be added from the final analysis before using quantitative claims.

## Repository contents

- `Weekly Updates - Week 1.ipynb` through `Weekly Updates - Week 8.ipynb` — progress notebooks
- `Cochran_Thesis Paper Draft.docx` — thesis draft

## Reproducibility status

A fresh checkout does not include the source dataset or a dependency file, and the repository does not provide a single final run command. Reproducing the analysis requires obtaining the cited dataset and matching the analysis environment. A polished release should add the source and license citation, a pinned environment file, and a concise final notebook or script alongside the preserved weekly work.
