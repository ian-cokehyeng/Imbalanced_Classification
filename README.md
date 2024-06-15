# Imbalanced Classification Prediction

Traditional machine learning models often struggle with imbalanced datasets, where one class is vastly outnumbered by another. This imbalance can lead to models that perform poorly at detecting the minority class due to bias towards the majority class. To enhance a model's ability to identify the minority class accurately, this projects levarages `imbalanced-learn` resamplers, notably; RandomOverSampler, RandomUnderSampler, TomekLinks, SMOTE, SMOTETomek, and ADASYN. These were tested on three models: Logistic Regression (L1), Logistic Regression (L2), and RandomForestClassifier. The best model was identified for each model-resampler was identified and evaluated against each other on the basis of Average Precision (PR-AUC), and ROC-AUC. 

--
Machine Learning Group - ULB, "Credit Card Fraud Detection Dataset." Kaggle. Available at: [https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud). Accessed on June 15, 2024.

## Prerequisites

Before you begin, ensure you have met the following requirements:
- You have installed the latest version of [Conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html).

## Installation

To install this project, follow these steps:

```bash
conda env create -f environment.yml -n custom_env_name
```

This command will create a new Conda environment that includes the dependencies needed for the project.

## Usage

To use this project, follow these steps:

```bash
conda activate <env_name>
jupyter notebook
```

Replace `<env_name>` with the name of the Conda environment specified above. This will activate the environment and start Jupyter Notebook, where you can open and run the notebook file.

## Contributors

The following individuals who have contributed to this project:

- Ian CoKehyeng