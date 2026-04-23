Steam Game Engagement Thesis
Joshua Cochran | INFO-I 492 | Advisor: Dr. Sridhar Ramachandran
April 2026

============================================================
OVERVIEW
============================================================
This folder contains the Jupyter notebook for the thesis:
"Early Indicators of Long-Term Player Engagement in Steam Games"

The notebook includes all data loading, cleaning, exploratory 
analysis, feature engineering, regression modeling, robustness 
checks, and residual diagnostics used in the study.

============================================================
FILES
============================================================
Code_notebook.ipynb   — Main analysis notebook (7 weeks of work)
games.csv             — Steam Games Dataset (source: Kaggle, 
                        compiled by Martin Bustos from Steam/SteamDB)
                        URL: https://www.kaggle.com/datasets/
                             fronkongames/steam-games-dataset

============================================================
ENVIRONMENT
============================================================
Python version: 3.x (tested with 3.10+)

Required libraries:
  pandas
  numpy
  matplotlib
  seaborn
  scikit-learn
  statsmodels
  graphviz (for workflow diagram only)

Install all dependencies:
  pip install pandas numpy matplotlib seaborn scikit-learn 
              statsmodels graphviz

============================================================
HOW TO RUN
============================================================
1. Place games.csv in the same directory as Code_notebook.ipynb
2. Create the following output folders if they do not exist:
      ../Graphs/
      ../Illustrations/
3. Open Code_notebook.ipynb in Jupyter Lab or Jupyter Notebook
4. Run all cells in order (Kernel → Restart & Run All)
5. Figures will be saved to ../Graphs/ and ../Illustrations/

============================================================
OUTPUT FILES
============================================================
All figures are saved as .png files at 300 DPI.
Output locations:
  ../Graphs/     — All data and model visualization figures
  ../Illustrations/ — Analytical workflow diagram

Figure-to-paper mapping:
  Notebook Fig 1  → Paper Fig 1  (Raw early playtime distribution)
  Notebook Fig 5  → Paper Fig 2  (Log-transformed distribution)
  Notebook Fig 8  → Paper Fig 3  (Log-log early vs. lifetime scatter)
  Heatmap (Week 7) → Paper Heatmap 1 (Correlation matrix)
  Notebook Fig 13 → Paper Fig 4  (Top model predictors)
  Notebook Fig 14 → Paper Fig 5  (Genre interaction effects)
  Graphviz output → Paper Fig 6  (Analytical workflow)

============================================================
NOTES
============================================================
- The dataset contains 122,611 games across 39 variables.
- 96.82% of games record zero early playtime (structural zero-inflation).
- All modeling uses log1p transformation for continuous engagement vars.
- Time-based validation uses pre-2022 training / 2022+ test split.
- Random seed is set to 42 for all sklearn splits.
============================================================