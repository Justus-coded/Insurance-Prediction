# Insurance-Prediction
To build a predictive model to determine if a building will have an insurance claim during a certain period or not

## Data Description
Recently, there has been an increase in the number of building collapse in Lagos and major cities in Nigeria. An Insurance Company offers a building insurance policy that protects buildings against damages that could be caused by a fire or vandalism, by a flood or storm.

The target variable, Claim, is a:

1 if the building has at least a claim over the insured period.,
0 if the building doesn’t have a claim over the insured period.

## Content
1. Exploratory Data Analysis
2. Data Cleaning and Preprocessing
3. Feature Extraction and generation
4. Predictive Analysis

### Exploratory Data Analysis
Here we dig into the data using Data Visualization Techniques to find relationship between various features. Check jupyter notebook on Exploratory Data Analysis. Tableau was also used to create several dashboards.

### Data Cleaning and Preprocessing
Fill in all missing values, remove redundant features, convert the data-type of categorical features.

### Feature Extraction and Genration
Create new features from relationships between existing ones. For Example, create a new column of painted building with garden or painted building with fenced building.

### Predictive Analysis.
Using various Machine Learning Algorithms like CatBoost and XGBoost, predict whether or not a building will have an insurance claim during a certain period
