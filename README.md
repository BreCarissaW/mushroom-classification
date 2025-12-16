# Mushroom Classification

This project focuses on predicting whether a mushroom is **edible or poisonous** based on physical characteristics. It applies supervised classification techniques to evaluate model performance and feature importance in a binary classification setting.

## Structure

- `notebooks/` — Jupyter notebook containing exploratory analysis, preprocessing, and modeling
- `data/` — local dataset files (not tracked in GitHub)
- `.gitignore` — excludes datasets and environment-specific files

## Data

The project is based on the **Mushroom Classification dataset**, originally sourced from the UCI Machine Learning Repository.  
The version used in this analysis may have been modified for coursework and preprocessing purposes.

The raw dataset is **not included** in this repository.

## How to Run

This repository is intended to demonstrate methodology and modeling decisions rather than exact numerical replication.

To run locally:
1. Place the dataset CSV file in the `data/` directory
2. Open the notebook in `notebooks/`
3. Run the notebook top to bottom

Example local data path:
```python
pd.read_csv("../data/mushroom.csv")
