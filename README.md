# Data Cleaning with AI Support

## Student Information
- Name: Joshua Radz T. Adlaon
- Course Year: BSCS 4
- Date: 2025-09-29

## Dataset
- Source: (https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data)
- Name: House Prices - Advanced Regression Techniques

## Steps Performed

1. Loaded the dataset and performed exploratory checks:

   * `df.info()`
   * `df.describe()`
   * Missing values check
   * Duplicate check
2. Cleaning steps applied:

   * Missing value handling:

     * Numerical → filled with median
     * Categorical → filled with mode
   * Duplicate removal
   * Standardized categorical formats (e.g., capitalization, trimmed spaces)
   * Outlier treatment (capped at 1st and 99th percentile)
3. Saved cleaned dataset to `data/cleaned_dataset.csv`.

## Before and After Snapshots

* **Shape before:** (1460, 81)
* **Shape after:** (1460, 81)
* **Missing values before:** Several (e.g., `LotFrontage: 259`, `Alley: 1369`)
* **Missing values after:** 0
* **Duplicates before/after:** 0

## AI Assistant Usage

As required, I used an AI assistant (ChatGPT) to guide the cleaning pipeline.

**Prompt given:**

```
Use Python (Pandas). Use an AI assistant at least once and include the prompt & response in README.

Load the raw dataset and perform exploratory checks 
df.info()
df.describe() 
missing values
duplicates
Apply cleaning steps: 
missing value handling
duplicate removal
standardize formats
detect/treat outliers
Include before and after snapshots of the following:
shapes
sample rows
summary statistics
Save cleaned dataset as data/cleaned_dataset.csv.

do all these to csv file
```

Video: 