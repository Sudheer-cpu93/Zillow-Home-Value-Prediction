# Zillow-Home-Value-Prediction
Home Value Prediction System

#  Zillow Home Value Prediction with Clustering & Regression

##  Project Overview
This project aims to predict home values using various machine learning models and identify property clusters using K-Means clustering. The dataset contains home details such as location, number of bedrooms, and other features.

---

##  Objective
- Develop a predictive model for home prices.
- Use K-Means clustering to group homes based on location and pricing attributes.
- Evaluate the model performance with appropriate metrics like MSE, R², and MAE.

---

##  Dataset Description
- **Source:** Zillow (Home Value Data)
- **Features:**
    - `Metro` - Metropolitan area of the property.
    - `State` - Location of the property.
    - `Bedrooms` - Number of bedrooms.
    - `Days` - Days on the market.
    - `Price` - Target variable, representing the home value.

---

##  Key Features
1. **Data Preprocessing**
   - Handled missing values and inconsistencies.
   - Applied feature scaling for clustering and model training.

2. **Clustering with K-Means**
   - Applied K-Means to group homes into clusters based on latitude, longitude, and cost.
   - Visualized clusters using scatter plots.

3. **Modeling Techniques**
   - Used multiple models for price prediction:
      - Linear Regression
      - Random Forest Regressor
   - Performed k-fold and 10-fold cross-validation to improve model performance.

4. **Evaluation Metrics**
   - Mean Squared Error (MSE)
   - R-squared (R²)
   - Mean Absolute Error (MAE)

---

##  Model Performance
###  Evaluation Results
| Model                      | MSE               | R²     | MAE         |
|----------------------------|-------------------|--------|-------------|
| Linear Regression           | 34,280,234,436.05 | 0.214  | 87,722.54   |
| Random Forest Regressor      | 26,867,821,659.56 | 0.384  | 67,058.19   |
| Random Forest (Cross-Val)    | 26,353,027,167.42 | 0.452  | 63,592.30   |
| Random Forest (10-Fold CV)   | 19,718,269,841.71 | 0.368  | 61,666.08   |

**Best Model:** Random Forest with Cross-Validation (R² = 0.452)

---

##  Visualizations
1.  **Correlation Heatmap** - Shows feature correlations.
2.  **Elbow Method Plot** - Determines the optimal number of clusters.
3.  **Cluster Scatter Plot** - Displays property clusters.
4.  **Prediction Plot** - Visualizes actual vs. predicted home values.

---

##  Technologies Used
- Python (Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn)
- Machine Learning Algorithms
- K-Means Clustering

---
