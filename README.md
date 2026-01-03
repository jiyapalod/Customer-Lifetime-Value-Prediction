
# Customer Lifetime Value (CLV) Prediction

## Overview
Customer Lifetime Value (CLV) is a critical metric that estimates the total value a customer contributes over their relationship with a business. This project focuses on predicting CLV using regression-based machine learning models to support data-driven decision-making in customer retention and marketing optimization.

## Dataset
- Source: Subscription-based customer dataset
- Target Variable: Customer Lifetime Value (CLV)
- Features: Customer demographics, subscription behavior, and usage metrics

## Methodology
- Data cleaning and preprocessing
- Feature selection and scaling
- Train-test split for model evaluation
- Training and comparison of multiple regression models
- Performance evaluation using error-based and goodness-of-fit metrics

## Models Implemented
- Linear Regression
- Regularized Regression (Ridge, Lasso)
- Tree-based Models (Random Forest, Gradient Boosting, CatBoost)

## Evaluation Metrics
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)
- R² Score

Models were compared across these metrics to evaluate generalization performance and robustness.

## Results
Tree-based ensemble models outperformed linear approaches, highlighting the importance of capturing non-linear relationships in customer behavior data. Regularization improved linear model stability but showed limited expressiveness.

## Key Learnings
- Importance of feature scaling in linear models
- Bias–variance tradeoff in regression
- Model interpretability vs performance considerations
- Practical application of evaluation metrics in business contexts

## Limitations
- Temporal dynamics of customer behavior not modeled
- Dataset limited to structured numerical features

## Future Improvements
- Time-series based CLV modeling
- Customer segmentation prior to regression
- Deep learning-based regression approaches
