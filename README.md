# Credit Scoring Model

This repository contains a comprehensive analysis and model building for predicting credit scores. The dataset used is `step_2_modified_df_credit_train.csv`, which includes various features related to customer credit behavior.

## Project Overview

The goal of this project is to build and evaluate various machine learning models to predict credit scores. The analysis involves preprocessing the data, applying different classification algorithms, and evaluating their performance.

## Table of Contents

1. [Data Preprocessing](#data-preprocessing)
2. [Model Training and Evaluation](#model-training-and-evaluation)
3. [Results](#results)
4. [Model Saving](#model-saving)
5. [Files](#files)

## Data Preprocessing

### Reading Data

The dataset is loaded from `step_2_modified_df_credit_train.csv`:

```python
import pandas as pd
df_credit = pd.read_csv('./step_2_modified_df_credit_train.csv')
