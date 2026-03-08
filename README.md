# Laptop Price Prediction using Machine Learning

##  Project Overview
As an engineering student, I developed this project to demonstrate a complete Machine Learning pipeline. The goal is to predict laptop prices based on hardware specifications, moving from raw data to a functional predictive model.

##  Dataset
The dataset was sourced from **Kaggle** and contains 1,300+ entries of laptop hardware details.
 **Source:** [Laptop Price Dataset](https://www.kaggle.com/datasets/muhammetvarl/laptop-price)
 **Status:** Includes `laptop_data_cleaned.csv` with units removed and data types optimized.
 All rights to the raw data belong to the original authors and Kaggle.

## 🛠 Tech Stack
 **Language:** Python 3.x
 **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib
 **Environment:** Google Colab

## Key Features
 **Data Cleaning:** Stripped 'GB' and 'kg' from columns and converted them to `int` and `float` types.
 **Feature Selection:** Analyzed hardware features like RAM and Weight for price correlation.
 **Modeling:** Implemented a **Linear Regression** algorithm.
 **Results:** Achieved an **R-squared ($R^2$) score of 0.54**.

##  File Structure
- laptop_price_analysis.ipynb`: The main notebook containing the data cleaning and model training code.
- laptop_data_cleaned.csv`: The processed dataset used for training.

  This project is under MIT LICENSE.

