# Customer Churn Prediction | Machine Learning & Deep Learning

## Project Overview

This project focuses on predicting customer churn in the telecommunications industry using Machine Learning and Deep Learning techniques.

The main objective is to identify customers who are likely to cancel their subscriptions, allowing companies to improve customer retention strategies.

## Dataset

**Telco Customer Churn Dataset**

The dataset contains customer information, including:
- Demographic characteristics
- Subscription services
- Contract information
- Monthly and total charges
- Customer tenure
- Churn status

## Technologies & Tools

- **Language:** Python
- **Data Analysis:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn
- **Class Imbalance:** SMOTE (Imbalanced-learn)
- **Deep Learning:** TensorFlow / Keras
- **Environment:** Jupyter Notebook

## Project Workflow

### 1. Data Preprocessing
- Data cleaning and missing value handling
- Encoding categorical variables
- Feature preparation
- Class imbalance analysis

### 2. Exploratory Data Analysis (EDA)
- Customer churn distribution
- Analysis of tenure and customer charges
- Correlation analysis
- Identification of potential churn-related factors

### 3. Machine Learning Models
Comparison of several classification algorithms:
- Random Forest
- Extra Trees
- HistGradientBoosting
- Support Vector Classifier (RBF)

### 4. Model Optimization
- Feature selection experiments
- Hyperparameter tuning
- Cross-validation
- Classification threshold analysis

### 5. Deep Learning
Development of a neural network using TensorFlow/Keras, with regularization techniques and training monitoring.

## Final Results

| Model | Accuracy | Churn Recall | Churn F1-score |
|---|---|---|---|
| Random Forest (Final) | 77.47% | 64% | 0.60 |
| Neural Network (Final) | **79.53%** | 59% | **0.61** |

## Key Findings

The neural network achieved the best overall classification performance, with an accuracy of approximately 79.5%.

However, the optimized Random Forest achieved higher recall for churned customers (64% versus 59%).

This highlights an important business trade-off between overall predictive performance and the ability to detect customers at risk of leaving.

## Conclusion

The neural network was selected as the best overall model based on the evaluated metrics.

However, Random Forest remains a relevant alternative when the primary business objective is to identify as many potential churners as possible.

The project demonstrates the importance of considering business objectives when evaluating classification models.
