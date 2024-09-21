# StrengthOfConcrete

### Description:
This project focuses on predicting the compressive strength of concrete using various features such as cement content, fly ash, blast furnace slag, and water content. The project explores various machine learning models to develop an accurate prediction system.

### Dataset

**Size**: 1030 samples
**Features**:
- Cement
- Blast Furnace Slag
- Fly Ash
- Water
- Superplasticizer
- Coarse Aggregate
- Fine Aggregate
- Days (Age of the concrete sample)

**Target** : Concrete Compressive Strength (MPa)

### Key Steps

**Exploratory Data Analysis (EDA)**:

Performed an initial analysis to understand feature distributions, correlations, and target relationships.
Addressed data imbalance by using stratified sampling.

**Feature Engineering**:

- Experimented with various attribute combinations.
- Selected the most important features based on model performance and significance.

**Transformation Pipelines**:

- Built feature transformation pipelines to preprocess the data.
- Applied transformations like log transformation and combined different features where necessary.

**Model Selection**:

Experimented with different models:
- Linear Regression, Support Vector Regressor (SVR), Random Forest Regressor
- Random Forest was chosen as the final model.

**Hyperparameter Tuning**:

Performed hyperparameter optimization using Randomized Search to find the best model configuration.

**Model Evaluation**:

Used RMSE (Root Mean Squared Error) as the evaluation metric:
- Train Error: 1.99
- Mean Cross-Validation Error: 4.98
- Test Set Error: 5.122

**Tools & Technologies Used**:

- Python (scikit-learn, pandas, numpy, matplotlib)
- Random Forest for final model
- Randomized Search for hyperparameter optimization
- Stratified Sampling for handling class imbalance
