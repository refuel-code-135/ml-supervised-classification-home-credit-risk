# ml-supervised-classification-home-credit-risk

![image](https://github.com/user-attachments/assets/96002c03-e051-4cd4-a626-9f20f26ab351)

## Project Overview

This project predicts if a loan client will default or not.

We use data from a real financial company which is provided by Kaggle.

The notebook includes:  
- Data cleaning and simple EDA
- Feature engineering
- Model training with LightGBM
- Evaluation using AUC score


## Notebook
https://github.com/refuel-code-135/ml-supervised-classification-home-credit-risk/blob/main/notebooks/notebook.ipynb

## Data

https://www.kaggle.com/competitions/home-credit-default-risk/data

## Set Up Analysis environment
```bash
export CONDA_ENV=ml-supervised-classification-home-credit-risk

# Create and activate a new conda environment
conda create -n $CONDA_ENV python=3.12
conda activate $CONDA_ENV

# Install required Python packages
pip install -r requirements.txt

# Start notebook
jupyter lab
```



