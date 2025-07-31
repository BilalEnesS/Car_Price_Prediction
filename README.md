# 🚗 Car Price Prediction - ML Model Comparison

This project analyzes and compares the performance of various machine learning algorithms for predicting car prices using the **Car Price Prediction** dataset from Kaggle.

## 📊 About the Dataset

The dataset includes information such as car make, model, production year, fuel type, mileage, and other key features. The goal is to predict car prices based on these attributes.

## 🔍 Data Preprocessing

- Categorical variables were converted to numerical values using **Label Encoding**.
- Production year was transformed into **Car Age**.
- **Outliers** in mileage and price were removed using the IQR method.
- Features were standardized using **StandardScaler**.

## 🧠 Applied Models and Their Performances

Four different models were trained and evaluated using R² score:

| Model                 | R² Score |
|----------------------|----------|
| Linear Regression     | 0.8422   |
| Random Forest         | 0.8096   |
| XGBoost               | 0.7894   |
| Polynomial Regression | 0.8391   |

## 📌 Key Insights

- **Linear Regression** achieved the highest R² score, performing very well on this dataset.
- **Polynomial Regression** also showed strong performance, especially in capturing more complex relationships.
- **Random Forest** and **XGBoost** performed slightly worse, possibly due to the dataset's simplicity and lower risk of overfitting.
- Feature engineering steps like calculating car age and removing outliers significantly improved model performance.

## 🔚 Conclusion

Due to the clean and structured nature of the dataset, **simpler models** performed better. This project demonstrates that classical algorithms like Linear and Polynomial Regression can outperform more complex models in certain scenarios. In this case, they provided more accurate and reliable predictions.

---
