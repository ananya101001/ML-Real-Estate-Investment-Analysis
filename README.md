# ML Real Estate Investment Analysis

## Project Overview
This project applies machine learning techniques to analyze and predict real estate investment opportunities. The analysis explores various features that influence property values and rental yields to help make data-driven investment decisions.

## Authors
👤 **Apoorva**  
👤 **Ananya** - [GitHub](https://github.com/ananya101001)

## Project Structure
```
ML-Real-Estate-Investment-Analysis/
│
├── ML_Midterm_Real_Estate_Investment_Analysis_Apoorva_&_Ananya_ipynb.ipynb
├── IEEE-Machine Learning for Real Estate Investment Analysis_ Clustering, Classification, and Price Forecasting.pdf
└── README.md
```

## Dataset
The dataset includes various property features such as:
- **Location attributes**: Geographic coordinates, neighborhood demographics
- **Property characteristics**: Size, bedrooms, bathrooms, age
- **Financial metrics**: Sale prices, rental income, property taxes
- **Market indicators**: Days on market, listing prices

*Dataset source and preprocessing steps are documented in the notebook.*

## Reference Paper
📄 **IEEE Paper**: `IEEE-Machine Learning for Real Estate Investment Analysis_ Clustering, Classification, and Price Forecasting.pdf`

This project implements the methodologies and concepts discussed in the accompanying IEEE research paper, which covers clustering, classification, and price forecasting techniques for real estate investment analysis.

## Technologies Used
- **Python**: Primary programming language
- **Jupyter Notebook**: Interactive development environment
- **Machine Learning Libraries**: 
  - Scikit-learn
  - Pandas
  - NumPy
  - Matplotlib/Seaborn (for visualization)

## Machine Learning Models
This project explores multiple regression and classification algorithms:
- **Linear Regression**: Baseline model for price prediction
- **Ridge & Lasso Regression**: Regularized models to prevent overfitting
- **Random Forest**: Ensemble method for robust predictions
- **Gradient Boosting**: Advanced ensemble technique
- **XGBoost/LightGBM**: High-performance gradient boosting implementations

## Evaluation Metrics
Models are evaluated using:
- **R² Score**: Proportion of variance explained
- **RMSE**: Root Mean Squared Error
- **MAE**: Mean Absolute Error
- **Cross-validation**: K-fold validation for generalization

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/ananya101001/ML-Real-Estate-Investment-Analysis.git
   ```

2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter notebook:
   ```bash
   jupyter notebook ML_Midterm_Real_Estate_Investment_Analysis_Apoorva_&_Ananya_ipynb.ipynb
   ```

4. Run all cells to reproduce the analysis

## Results
The analysis provides insights into:
- **Feature Importance**: Which property characteristics most influence value
- **Model Performance**: Comparative analysis of different ML algorithms
- **Investment Recommendations**: Data-driven insights for property selection
- **Market Trends**: Patterns in pricing and rental yields across regions

*Note: Detailed results and visualizations are available in the Jupyter notebook.*

## Future Improvements
- Incorporate time-series analysis for market trends
- Add more external data sources (economic indicators, demographics)
- Deploy model as a web application for real-time predictions
- Expand analysis to multiple geographic regions

## License
This project is part of an academic assignment.

## Contact
For questions or collaboration opportunities, please reach out through GitHub issues.

---
*This project was completed as part of a Machine Learning midterm assignment.*
