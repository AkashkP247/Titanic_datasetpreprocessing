
## Objectives

- Explore the dataset (missing values, data types)
- Handle null values using median/mode
- Encode categorical variables (`Sex`, `Embarked`, `Title`)
- Normalize/standardize numerical features
- Extract meaningful features from raw data

## Files

- `DataPreprocessing.ipynb`: Main notebook with all preprocessing steps.
- `titanic.csv`: Titanic dataset (source: [Kaggle](https://www.kaggle.com/datasets/yasserh/titanic-dataset))

## Key Features Engineered

- One-hot encoded `Sex` and `Embarked`
- Extracted `Title` from `Name` (e.g., Mr, Mrs, Miss)
- Converted boolean columns to numerical

## Tools Used

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn

## Dataset

- [Kaggle Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)

##  How to Run

1. Clone the repo
2. Open `DataPreprocessing.ipynb` in Jupyter
3. Install requirements if needed (`pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`)
4. Run all cells

