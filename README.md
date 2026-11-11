# House Price Data Analysis and Preprocessing

## Project Overview
This project focuses on analyzing and preprocessing a housing prices dataset using Python. It includes data inspection, data cleaning, handling missing values, standardizing categorical data, and exploratory data analysis (EDA).

## Objectives
- Understand the structure of the housing dataset.
- Identify and handle missing values.
- Remove duplicate and redundant columns.
- Standardize inconsistent categorical values.
- Convert columns into appropriate data types.
- Perform exploratory data analysis using visualizations.
- Generate a cleaned dataset for further analysis.

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Dataset
**Dataset Name:** `housing_prices_regression.csv.xls`

The dataset contains housing-related information such as:
- Property ID
- ZIP Code
- House Size (Square Feet)
- Number of Bedrooms
- Garage Availability
- Garden Availability
- Sale Price

## Data Preprocessing

The following preprocessing operations are performed:

1. Create a copy of the original dataset.
2. Handle redundant ZIP code columns.
3. Standardize categorical values in `has_garage` and `has_garden`.
4. Convert `size_sqft` into numeric format.
5. Handle missing numeric values using median imputation.
6. Replace missing property IDs with `Unknown`.
7. Save the cleaned dataset as `housing_prices_cleaned.csv`.

## Exploratory Data Analysis (EDA)

### 1. Univariate Analysis
- Distribution of sale prices.
- Distribution of property sizes.

### 2. Bivariate Analysis
- Relationship between property size and sale price.
- Relationship between bedrooms and sale price.

### 3. Multivariate Analysis
- Sale price versus property size based on garage availability.
- Correlation heatmap of numerical features.

## Project Structure

```text
House-Price-Analysis/
│
├── MiniProject.ipynb
├── housing_prices_regression.csv.xls
├── housing_prices_cleaned.csv
└── README.md
```

## Installation and Execution

### Step 1: Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### Step 2: Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Step 3: Open Jupyter Notebook

```bash
jupyter notebook
```

### Step 4: Run the Project
1. Open `MiniProject.ipynb`.
2. Make sure the dataset is available in the project directory.
3. Execute all cells sequentially.
4. View the data cleaning results and visualizations.

## Future Improvements
- Perform outlier detection.
- Apply categorical encoding.
- Implement machine learning regression models.
- Evaluate prediction performance using MAE, MSE, RMSE, and R².

## Author
**Your Name**

## License
This project is intended for educational purposes.

