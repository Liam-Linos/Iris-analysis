# Iris Dataset Analysis

## Overview
This project explores the famous **Iris dataset**, which is widely used in machine learning and data analysis. The dataset consists of measurements of different flower species (Setosa, Versicolor, and Virginica). This analysis includes:

- **Data Loading & Exploration**: Inspecting the dataset structure and checking for missing values.
- **Basic Data Analysis**: Computing summary statistics and identifying patterns.
- **Visualizations**: Creating different plots to understand data distributions and relationships.

## Dataset Description
The Iris dataset contains **150 samples** of iris flowers, with the following features:

- **Sepal Length (cm)**
- **Sepal Width (cm)**
- **Petal Length (cm)**
- **Petal Width (cm)**
- **Species** (Categorical: Setosa, Versicolor, Virginica)

## Steps in the Notebook
1. **Loading the Dataset**: Using `pandas` to load and inspect the first few rows.
2. **Exploring Data**: Checking data types and missing values.
3. **Performing Statistical Analysis**: Using `.describe()` to analyze numerical features.
4. **Grouping Data**: Computing average petal and sepal measurements per species.
5. **Visualizing Data**:
   - **Line Chart**: Trends in petal length across species.
   - **Bar Chart**: Sepal width comparison across species.
   - **Histogram**: Distribution of petal lengths.
   - **Scatter Plot**: Relationship between sepal length and petal length.

## Technologies Used
- **Python**
- **pandas** (Data manipulation)
- **matplotlib & seaborn** (Visualization)
- **scikit-learn** (Dataset loading)

## How to Run the Notebook
1. Install the required libraries if you haven't already:
   ```bash
   pip install pandas matplotlib seaborn scikit-learn
   ```
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook iris_analysis.ipynb
   ```
3. Run the cells to execute the analysis and visualize the data.

Findings
- **Setosa** has significantly smaller petal lengths and widths.
- **Versicolor** has moderate petal sizes, while **Virginica** has the largest petals.
- **Sepal length and petal length show a strong correlation**, which helps in classification.

Conclusion
This analysis provides insights into the **Iris dataset**, showcasing the differences between species using statistical and visual techniques. The notebook serves as an excellent introduction to **data analysis and visualization in Python**.



