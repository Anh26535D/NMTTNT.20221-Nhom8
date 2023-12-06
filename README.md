# Customer Churn Prediction

## Overview
This project aims to address customer churn in a Direct to Home (DTH) service provider. The dataset includes information about customer accounts, and the goal is to predict which customers are likely to leave the service in the future. The project involves data exploration, preprocessing, model development, and evaluation.

**Dataset Link:** [Customer Churn Dataset](https://www.kaggle.com/code/vsridevi/capstone-project-churn-prediction/data?scriptVersionId=110749928)

## File Structure
- **description.csv**: CSV file describing the fields in the dataset.
- **train.csv**: Training set after being split.
- **test.csv**: Testing set after being split.
- **split_data.py**: Python script for splitting the dataset into train and test sets, handling inconsistent values.
- **exp** directory:
  - **EDA.ipynb**: Notebook for data exploration.
  - **Datapipeline.py**: Python script creating a data processing pipeline.
  - **OutlierHandling.py**: Python script handling outliers using scikit-learn's API.
  - **CrossValidation.ipynb**: Notebook for model experimentation, selection, and evaluation through cross-validation.
  - **Predict.ipynb**: Notebook for predicting on the test set.

## Team Members
- **Đàm Việt Anh** - 20204627 - anh.dv204627@sis.hust.edu.vn
- **Vũ Việt Anh** - 20200053 - anh.vv200053@sis.hust.edu.vn
- **Vũ Đức Quỳnh** - 20204684 - quynh.vd204684@sis.hust.edu.vn
- **Nguyễn Đăng Khoa** - 20204572 - khoa.nd@sis.hust.edu.vn
- **Trịnh Quang Quân** - 20200511 - quan.tq@sis.hust.edu.vn
