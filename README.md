# House Price Prediction Using Regression

## Project Overview

This project uses machine learning regression algorithms to predict house prices based on property characteristics. It includes data preprocessing, exploratory data analysis (EDA), feature preparation, model training, and evaluation.

## Dataset Features

The dataset contains the following features:

- `Square_Footage` — House size in square feet
- `Num_Bedrooms` — Number of bedrooms
- `Num_Bathrooms` — Number of bathrooms
- `Year_Built` — Year the house was built
- `Lot_Size` — Property lot size
- `Garage_Size` — Garage size
- `Neighborhood_Quality` — Neighborhood quality score
- `House_Price` — Target variable

**Dataset file:** `house_price_regression_dataset.csv`

## Machine Learning Workflow

1. Load and inspect the dataset.
2. Handle missing values and duplicate records.
3. Perform exploratory data analysis.
4. Visualize feature distributions and correlations.
5. Detect and handle outliers.
6. Apply log transformation where appropriate.
7. Separate features and target variable.
8. Split the dataset into training and testing sets.
9. Scale features using StandardScaler.
10. Train and evaluate regression models.

## Models Used

- Linear Regression
- K-Nearest Neighbors (KNN) Regression


Based on these recorded results, Linear Regression performed better than KNN Regression on the evaluated test set.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Installation and Usage

### 1. Clone the repository

```bash
git clone <your-repository-url>
cd <your-repository-folder>
```

### 2. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 3. Add the dataset

Place `house_price_regression_dataset.csv` in the same directory as the notebook.

### 4. Run the notebook

```bash
jupyter notebook
```

Open `House_Price_Prediction_(Regression).ipynb` and execute the cells in order.

## Project Structure

```text
House-Price-Prediction/
├── House_Price_Prediction_(Regression).ipynb
├── house_price_regression_dataset.csv
└── README.md
```

## Limitations

- The dataset must be available locally to run the notebook.
- Model results should be validated on appropriate unseen data before real-world use.
- This project is intended for educational purposes and does not replace a professional property valuation.

## Author

**Aishwarya Patil**

GitHub: https://github.com/aishpatilds-lang
