# Gamer and Anxiety Project

## Team Members

- [Max](https://github.com/midniteclub)
- [Joe](https://github.com/binaryplatitude)
- [Miko](https://github.com/bluemaw)

## Project Description

A machine learning project focusing on the relationships between gaming habits and anxiety.

## Data

Data was downloaded from Kaggle:
To run the eda code, place the dataset in the `data` folder. Make sure it's named `gaming_anxiety.csv`. This step has been performed for submission criteria. Data is cleaned in `eda.ipynb`. Cleaned data is named `cleaned_gamer_data.csv`, this file is used by `modeling.ipynb`
Contains:
`gaming_anxiety.csv`
`cleaned_gamer_data.csv`

## Code

All code scripts along with EDA notebooks are in the repository. Modeling is the desired content for evaluation, followed by EDA.
`modeling.ipynb`
`eda.ipynb`

## Docs

Multiple files are produced by `modeling.ipynb` which contain the performance metrics of the models.
- `BeforeTuned_ModelAccuracy.png`
- `BestLogReg_CalibrationCurve.png`
- `BestLogReg_ConfusionMatrix.png`
- `BestLogReg_FeatureImportance.png`
- `BestLogReg_SHAP_test.png`
- `BestLogReg_SHAP_val.png`
- `BestModels_Results.csv`
- `BestRF_FeatureImportance.png`
- `TargetBySource.png`
- `TESTSET_BestLogReg_Results.csv`