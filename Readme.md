# MATH5470_Han_Liu_Liu_Chu Project 1: Home Credit Default Risk

**Team Members:**  
HAN Shi, LIU Fengming, LIU Hailin, CHU He

---

## Project Overview

This project tackles the **Home Credit Default Risk** prediction problem. Our workflow includes data preprocessing, feature engineering, model training with LightGBM and XGBoost, and ensemble modeling.

All code is written in **Jupyter Notebooks**, and you can run it **cell by cell** to reproduce our results.

---

## File Structure

### 1.Codes

- `code_1_data_preprocessing_feature_engineering.ipynb`  
  Data cleaning, missing value handling, feature engineering, and GRU score calculation.

- `code_2_LGBM.ipynb`  
  Training LightGBM models on the prepared dataset, including hyperparameter tuning and cross-validation.

- `code_2_XGB.ipynb`  
  Training XGBoost models on the prepared dataset, similar workflow to LightGBM.

- `code_3_Ensemble.ipynb`  
  Combining predictions from LGBM and XGB models via ensemble methods.

### 2.Data

- `raw/`  
  Original data downloaded from the Kaggle competition. Includes all CSV files provided by the competition.

- `prepared/`  
  Preprocessed data and calculated GRU scores ready for modeling.

### 3.Output

- `output/`  
  Figures and visualizations generated during analysis, such as feature importance plots.

### 4.Submission

- `submission/`  
  CSV file of our final submission to Kaggle.

---

## Kaggle Submission Results

- **AUC:** XXXX  
- **Rank:** XXXX  

---

## How to Use

1. Install the required packages by running:
   ```bash
   pip install -r requirements.txt
2. Open each Jupyter Notebook and run the cells sequentially.  
3. Make sure the `data/raw` and `data/prepared` folders are correctly placed.  
4. After running all notebooks, the final predictions and figures will be generated in the `submission` and `output` folders.

---
## Our Workflow Overview
![Overview](Fig/pipeline_overview.png)
