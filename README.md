# Sales Prediction Using Python

## Table of Contents
1. [Overview](#overview)
2. [Dataset](#dataset)
3. [Project Workflow](#project-workflow)
   - [Data Preprocessing](#1-data-preprocessing)
   - [Exploratory Data Analysis (EDA)](#2-exploratory-data-analysis-eda)
   - [Model Building](#3-model-building)
   - [Model Evaluation](#4-model-evaluation)
4. [Installation & Dependencies](#installation--dependencies)
5. [Running the Project](#running-the-project)
6. [Results & Visualizations](#results--visualizations)
7. [Conclusion](#conclusion)
8. [Future Enhancements](#future-enhancements)
9. [Author](#author)
10. [License](#license)

## Overview
Sales prediction involves forecasting the amount of a product that customers will purchase based on various factors such as advertising expenditure, target audience segmentation, and platform selection. In this project, machine learning techniques are used to analyze historical sales data and predict future sales trends.

## Dataset
The dataset used contains sales data along with advertising expenditures on different platforms. The key features include:
- `TV`: Amount spent on TV advertisements.
- `Radio`: Amount spent on radio advertisements.
- `Newspaper`: Amount spent on newspaper advertisements.
- `Sales`: Sales figures (target variable).

## Project Workflow
### 1. Data Preprocessing
- Load the dataset using Pandas.
- Check for missing values and duplicate entries.
- Perform data type conversion and basic cleaning.

### 2. Exploratory Data Analysis (EDA)
- Generate descriptive statistics of the dataset.
- Visualize data distributions using box plots and histograms.
- Use scatter plots and correlation heatmaps to identify relationships between features.

### 3. Model Building
- Split data into training and testing sets.
- Implement **Simple Linear Regression** using `statsmodels` and `scikit-learn`.
- Train the model using the TV advertising budget as the primary feature.

### 4. Model Evaluation
- Calculate key performance metrics such as:
  - **Mean Squared Error (MSE)**
  - **Root Mean Squared Error (RMSE)**
  - **R-squared Score (R2 Score)**
- Visualize predicted vs. actual sales values.

## Installation & Dependencies
### Prerequisites
Ensure you have the following libraries installed:
```sh
pip install numpy pandas matplotlib seaborn scikit-learn statsmodels chardet
```

## Running the Project
1. Clone this repository:
   ```sh
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```sh
   cd sales-prediction
   ```
3. Run the script:
   ```sh
   python sales_prediction.py
   ```

## Results & Visualizations
- **Box Plots**: Show outlier analysis of the advertising expenditure.
- **Pair Plot & Heatmap**: Identify the strongest correlation (TV ads with sales).
- **Regression Line Visualization**: Graphical representation of the best-fit line for sales prediction.
- **Error Distribution Plot**: Analyze residual errors in the model.

## Conclusion
This project demonstrates how linear regression can be used to predict sales based on advertising expenditure. The analysis highlights that TV advertisements have the highest correlation with sales, making them a crucial factor in marketing strategies.

## Future Enhancements
- Implement **Multiple Linear Regression** to include all advertisement types.
- Apply **Polynomial Regression** or **Decision Tree Regression** for improved predictions.
- Develop a **dashboard using Flask or Streamlit** to visualize sales trends interactively.

## Author
- **Dawood M D**

## License
This project is open-source and available under the [MIT License](LICENSE).

