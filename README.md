 House Price Prediction using Machine Learning

This project focuses on predicting house prices using the **Ames Housing Dataset** from Kaggle.  
It demonstrates the full machine learning pipeline including preprocessing, feature selection, modeling, and evaluation.



 Problem Statement

The goal is to build a predictive model that estimates the **SalePrice** of a house based on various attributes (e.g., number of rooms, area, neighborhood features, etc.).


  Machine Learning Approach

- Target Variable: `SalePrice`
- Features: Top correlated variables with `SalePrice` selected using a correlation matrix.
- Model: `RandomForestRegressor` built within a scikit-learn pipeline
- Evaluation Metric: Root Mean Squared Error (RMSE)



 Workflow Overview

1. **Load and explore data**
2. **Correlation analysis to select top features**
3. **Train-test split (80/20)**
4. **Preprocessing using pipelines**
   - Numeric: imputation + scaling
   - Categorical: imputation + one-hot encoding
5. **Model training with Random Forest**
6. **Evaluation on test data (RMSE)**
7. **Feature importance visualization**

---

 Model Results

The model achieved the following performance on the test data:

- **RMSE**: ~`{rmse}`

> *(Replace `{rmse}` with the actual printed value you got)*

Additionally, a bar chart was plotted to visualize the **top 10 most important features** influencing house price prediction.


 Tools & Libraries

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Pipeline & ColumnTransformer
- RandomForestRegressor



 Dataset Information

- **Dataset**: Ames Housing Dataset
- **Source**: [Kaggle Dataset Link](https://www.kaggle.com/datasets/prevek18/ames-housing-dataset?resource=download)
- **Note**: Dataset is not uploaded in this repository due to unknown license. Please download it manually from the link above.




## ✅ License

This project is provided for educational purposes. Dataset license is unknown — please refer to the original source on Kaggle.
