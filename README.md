# HSE 751 Reproducibility Exercise

## Diabetes Risk Factor Analysis

This repository contains the completed Reproducibility Exercise for HSE 751: Programming for Health Data Science. The purpose of this project is to demonstrate a transparent, organized, and reproducible computational workflow that can be executed by another user with minimal additional setup.

The analysis uses a diabetes dataset containing 768 patient observations to explore relationships between patient characteristics and diabetes outcome. The workflow includes data validation, descriptive statistics, data visualization, correlation analysis, inferential statistical testing, and discussion of how the dataset can be represented within a supervised machine learning framework.

## Google Colab Notebook

The completed notebook can be opened and executed in Google Colab:

**[Open the completed notebook in Google Colab]((https://colab.research.google.com/drive/1PfmCpnsmJQPpSQLWm4Ki8W-Vsc734w8A?usp=sharing))**

A downloaded `.ipynb` copy of the completed notebook is also included in this repository.

## Dataset

The analysis uses `Example Dataset_Diabetes.csv`, which was provided for this project.

The dataset contains the following eight patient characteristics:

- `Pregnancies`
- `Glucose`
- `D_BP`
- `Skin_Thickness`
- `Insulin`
- `BMI`
- `Pedigree`
- `Age`

The binary target variable is:

- `Outcome` — diabetes outcome, where `0` represents no diabetes and `1` represents diabetes.

The notebook retrieves the dataset directly from the HSE 751 project repository. Therefore, an internet connection is required when executing the notebook using the documented data source.

## Software and Dependencies

The analysis was developed and tested in Google Colab using Python.

The following Python packages and versions were used:

- `pandas==2.2.3`
- `numpy==2.1.3`
- `matplotlib==3.10.0`
- `seaborn==0.13.2`
- `scipy==1.16.3`

These dependencies are also documented in the included `requirements.txt` file.

To install the required packages in another Python environment, run:

```bash
pip install -r requirements.txt
