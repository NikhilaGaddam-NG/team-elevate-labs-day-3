
# House Price Prediction using Linear Regression

This project demonstrates a simple Linear Regression model to predict house prices based on area.  
It includes data preprocessing, model training, evaluation, and visualization.


## Project Structure
- `Housing.csv` → Dataset containing house area and price.
- `house_price_prediction.py` → Python code for building and evaluating the model.


## 🚀 Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn


## 📈 How it Works
1. Load Dataset 
   Import data from `Housing.csv`.

2. Preprocessing
   Select `area` as the feature and `price` as the target variable.

3. Train-Test Split
   Split the dataset into 80% training and 20% testing sets.

4. Model Training  
   Train a `LinearRegression` model using scikit-learn.

5. Prediction and Evaluation  
   Predict house prices and evaluate model performance using:
   - Mean Absolute Error (MAE)
   - Mean Squared Error (MSE)
   - R² Score

6. Visualization  
   Plot the scatter plot of area vs price with the fitted regression line.

## Example Output


MAE: 24567.89
MSE: 123456789.12
R² Score: 0.84

