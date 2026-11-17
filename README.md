# **Traffic Prediction Using Machine Learning**

## **Project Overview**

This project focuses on predicting traffic conditions using Machine Learning regression techniques. It explores traffic-related data, applies data preprocessing and feature engineering, and evaluates multiple regression models to identify the most accurate and reliable approach.

## **Objectives**

* Analyze traffic data and identify important patterns and relationships.  
* Perform data cleaning and preprocessing.  
* Apply feature engineering to improve model performance.  
* Train and evaluate multiple Machine Learning regression models.  
* Compare model performance using MAE, RMSE, and R² Score.  
* Apply ensemble learning techniques to improve prediction accuracy.

## **Machine Learning Models**

The following models were implemented and evaluated:

* Linear Regression  
* Random Forest Regressor  
* K-Nearest Neighbors (KNN)  
* Decision Tree Regressor  
* Support Vector Regression (SVR)  
* AdaBoost Regressor  
* Stacking Regressor

## **Model Evaluation**

Models were evaluated using three main regression metrics:

* **MAE (Mean Absolute Error):** Measures the average absolute prediction error.  
* **RMSE (Root Mean Squared Error):** Measures prediction errors while giving more weight to larger errors.  
* **R² Score:** Measures how well the model explains the variance in the target variable.

### **Test Results**

| Model | MAE | RMSE | R² Score |
| ----- | ----- | ----- | ----- |
| Linear Regression | 1553.97 | 1772.59 | 0.1980 |
| Random Forest | 249.98 | 392.97 | 0.9606 |
| KNN | 462.15 | 702.07 | 0.8742 |
| Decision Tree | 319.77 | 539.13 | 0.9258 |
| SVR | 1720.70 | 1969.83 | 0.0095 |
| AdaBoost | 595.68 | 791.77 | 0.8400 |
| Stacking Regressor | 227.90 | 380.81 | 0.9630 |

## **Key Findings**

* Random Forest demonstrated consistent performance across training, validation, and testing datasets.  
* Stacking Regressor achieved the best test performance, with an R² Score of 0.9630.  
* Random Forest showed strong stability across the three datasets.  
* Ensemble learning techniques, particularly Stacking, improved predictive performance.

## **Technologies Used**

* Python  
* Pandas  
* NumPy  
* Matplotlib  
* Seaborn  
* Scikit-learn  
* Jupyter Notebook

## **Conclusion**

The project demonstrates how Machine Learning regression algorithms and ensemble learning techniques can be used for traffic prediction. Random Forest provided highly consistent results, while Stacking Regressor achieved the lowest test error and highest R² Score among the evaluated models.

