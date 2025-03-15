

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
    
