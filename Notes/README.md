## Supervised vs Unsupervised Learning

| Supervised Learning | Unsupervised learning | 
|---------------------|-----------------------|
| Supervised ML algorithms are guided by labelled examples. | Unsupervised algorithms are not guided by labelled examples. |
| Requires training data with independent variables and a dependent variable. (labelled data) | Requires training data with independent variables only. |
| Need labelled data that can 'supervise' the algorithm while learning from the data. | Do not need labelled data for learning. |
| E.g. Regression models, classification models | E.g. Clustering models, outlier detection models. |

## Regression vs Classification

| Regression | Classification | 
|------------|----------------|
|


### Regression performance metrices

#### 1. RSS
   - Residual Sum of Squares (RSS):
   - RSS = ∑(yi - ŷi)²
   - Sum of squared differences between actual (yi) and predicted (ŷi) values.
   - Lower RSS indicates a better model fit.

     
#### 2. MSE
   - Mean Squared Error (MSE):
   - MSE = (1/n) ∑(yi - ŷi)²
   - Average of squared residuals.
   - Penalizes larger errors more than smaller ones.

     
#### 3. RMSE
   - Root Mean Squared Error (RMSE):
   - RMSE = √(MSE) = √[(1/n) ∑(yi - ŷi)²]
   - Square root of MSE.
   - More interpretable as it has the same unit as the target variable.

     
#### 4. MAE
   - Mean Absolute Error (MAE):
   - MAE = (1/n) ∑ |yi - ŷi|
   - Average of absolute errors.
   - Less sensitive to large errors compared to MSE/RMSE.
    
