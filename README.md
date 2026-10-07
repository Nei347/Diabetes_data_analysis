# Diabetes Dataset Analysis — Beginner Data Science Project

**Makhavhu Munei**  
BBusSci Mathematical Statistics & Data Science — University of Cape Town

## About the Project

This is one of my beginner data science projects, where I used Python to explore and analyse the diabetes dataset provided through scikit-learn.

The main goal was to practise the basic steps involved in a data science workflow rather than simply focusing on building a complicated machine-learning model.

I worked through the dataset by first understanding the data, checking its structure and quality, calculating descriptive statistics, exploring correlations, creating visualisations, and finally building a simple linear regression model.

This project helped me connect some of the statistics I am learning at university with practical Python and data-analysis skills.

## What I Practised

- Python
- Pandas
- NumPy
- Matplotlib
- scikit-learn
- Data inspection
- Descriptive statistics
- Missing-value checks
- Correlation analysis
- Data visualisation
- Train/test splitting
- Simple linear regression
- Model evaluation using RMSE and R²

## Dataset

The dataset is loaded directly from `sklearn.datasets.load_diabetes`.

It contains **442 observations** and **10 predictor variables**, together with a quantitative target representing disease progression.

No separate dataset download is required because the dataset is included with scikit-learn.

## What I Did

### 1. Loaded and inspected the data
I loaded the dataset using scikit-learn and converted it into a Pandas DataFrame. I then looked at the number of observations and variables, the first few rows, data types and summary statistics.

### 2. Checked the data quality
I checked the dataset for missing values. There were no missing values, so no imputation was necessary for this introductory analysis.

### 3. Explored the variables
I calculated descriptive statistics such as the mean, standard deviation, minimum and maximum.

### 4. Visualised the target variable
I created a histogram to see how the target values were distributed.

### 5. Investigated correlations
I calculated the correlation between each numerical variable and the target. BMI showed one of the stronger positive linear relationships with the target.

Correlation does **not** prove that one variable causes another.

### 6. Built a simple regression model
I used BMI as a single predictor and the diabetes target as the response variable. I split the data into 80% training data and 20% testing data, then fitted a simple linear regression model.

The model produced an R² of approximately **0.23**, showing that BMI alone explains only part of the variation in the target.

## What I Learned

This project helped me understand how the different parts of a data-analysis workflow fit together.

I also learned that a model should not just produce predictions; its performance needs to be evaluated and interpreted carefully.

## Limitations

- Only one predictor was used for the regression model.
- The dataset is relatively small.
- Correlation does not imply causation.
- The model is not intended to make medical predictions.
- More advanced modelling and validation would be needed for serious predictive analysis.

## How to Run the Project

1. Install Python 3.
2. Install the required packages:

```bash
pip install -r requirements.txt
```

3. Open `Diabetes_Data_Analysis.ipynb` in Jupyter Notebook, JupyterLab or VS Code.
4. Run the cells from top to bottom.

## Project Structure

```text
diabetes-data-analysis-python/
│
├── Diabetes_Data_Analysis.ipynb
├── README.md
├── requirements.txt
└── PROJECT_GUIDE.md
```

## CV Description

**Diabetes Dataset Analysis | Python, Pandas, NumPy, Matplotlib, scikit-learn**

- Performed exploratory data analysis on 442 observations using Python, descriptive statistics and correlation analysis.
- Created visualisations to investigate the distribution of the target and relationships between variables.
- Built a simple linear regression model using BMI as a predictor and evaluated performance using RMSE and R².
- Practised an end-to-end introductory data-analysis workflow using Pandas, NumPy, Matplotlib and scikit-learn.

## Note

This project is intended for educational purposes and is **not intended for medical decision-making**.
