# Car Selling Price Prediction

This project predicts the selling price of used cars using machine learning models. It includes data cleaning, exploratory data analysis (EDA), feature engineering, and model training using Linear Regression, Random Forest, and XGBoost.

## Project Structure

```
car_selling_prediction.ipynb
car.csv
.gitignore
```

- **car_selling_prediction.ipynb**: Main Jupyter notebook with all code and analysis.
- **car.csv**: Dataset containing used car listings and features.

## Features Used

- Brand, Model, Year, Fuel type, Seller type, Transmission, Owner type
- Mileage, Engine capacity, Max power, Number of seats, Kilometres driven

## Workflow

1. **Data Cleaning**: Handles missing values and converts data types.
2. **EDA**: Visualizes distributions and relationships using bar plots, histograms, boxplots, scatterplots, and correlation heatmaps.
3. **Feature Engineering**: Extracts car age, applies log transformations, scales numerical features, and encodes categorical variables.
4. **Modeling**: Trains and evaluates Linear Regression, Random Forest, and XGBoost models.

## How to Run

1. Clone the repository and open `car_selling_prediction.ipynb` in Jupyter or VS Code.
2. Ensure you have the required Python packages:
    - pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost
3. Run all cells in the notebook.

## Example Visualizations

- Distribution of selling prices, mileage, engine, and max power
- Bar plots for categorical variables (fuel, seller type, transmission, owner, seats)
- Boxplots and scatterplots for bivariate analysis
- Correlation heatmap among numerical features

## Results

The notebook compares the performance of different regression models and provides evaluation metrics (RMSE, R² score).

---

**Author:** Sameer Shrestha  
**Dataset Source:**
