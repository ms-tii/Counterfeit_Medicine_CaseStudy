# Counterfeit_Medicine_CaseStudy

## Overview

Counterfeit medicines are a serious worldwide issue that harm both public health and the economy. This project uses machine learning to predict sales for operations that sell fake medicines. With better sales predictions, law enforcement and regulatory agencies can focus their efforts and resources on the most profitable illegal networks, helping to reduce the impact of counterfeit drugs.

## Problem Statement

It is estimated that around 10% of the world’s medicine supply is counterfeit, and the percentage is even higher in many developing countries. Organized criminal groups earn large profits by selling fake drugs. Organizations like the World Health Organization (WHO) and Interpol work together to fight this problem, but new counterfeit operations keep appearing. Because of this, it is difficult to decide where to allocate limited resources most effectively.

## Datasets

The project provides two datasets for analysis:

- `counterfeit_train.csv`: This dataset is meant for training your predictive model. It contains various features related to counterfeit medicine selling operations, including attributes that characterize the operations.
 https://drive.google.com/file/d/1N_Chixa3BB9t4lACzCvOK3hMRlIG8UsY/view?usp=sharing 

- `counterfeit_test.csv`: This dataset is meant for evaluating your model's performance. It lacks the response column, and your task is to predict the sales figures for these operations. You will need to submit your predictions in a CSV file format.
https://drive.google.com/file/d/1yV1whAvD9SnahLXi7sCwaOtcBYkkag8p/view?usp=sharing

## Approach

To tackle this problem, you can follow these steps:

1. **Data Preprocessing**: Explore the provided datasets, handle missing values, and perform feature engineering if necessary.

2. **Feature Selection**: Select relevant features that can contribute to predicting sales figures effectively.

3. **Model Selection**: Choose appropriate machine learning algorithms for regression tasks. Consider algorithms like Linear Regression, Random Forest, Gradient Boosting, etc.

4. **Model Training**: Train your selected models on the training dataset and tune hyperparameters for optimal performance.

5. **Model Evaluation**: Evaluate your models using appropriate metrics (e.g., RMSE, MAE) on the test dataset to understand their predictive capabilities.

6. **Submission**: Use the trained model to predict sales figures for the test dataset. Create a CSV file with your predictions and submit it.

## Getting Started

1. Clone this repository to your local machine.

```bash
git clone https://github.com/ms-tii/Counterfeit_Medicine_CaseStudy.git
```

2. Install the required dependencies by running:

```bash
pip install -r requirements.txt
```

3. Start working on the project by following the approach outlined above.
