# Car Features and MSRP EDA

This repository contains a Jupyter Notebook that performs exploratory data analysis (EDA) on a dataset containing car features and MSRP (Manufacturer's Suggested Retail Price). The analysis includes summary statistics, additional statistical calculations, unique value counts for categorical columns, and various visualizations to better understand the data.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Analysis](#analysis)
  - [Summary Statistics](#summary-statistics)
  - [Additional Statistical Measures](#additional-statistical-measures)
  - [Unique Values in Categorical Columns](#unique-values-in-categorical-columns)
  - [Visualizations](#visualizations)
    - [Distribution of Numerical Columns](#distribution-of-numerical-columns)
    - [Correlation Matrix](#correlation-matrix)
    - [Pairplot](#pairplot)
    - [Boxplots](#boxplots)
    - [Trend Analysis](#trend-analysis)
- [Inference](#inference)
- [Contributing](#contributing)
- [License](#license)

## Introduction
The purpose of this notebook is to perform exploratory data analysis on a dataset containing various car features and their corresponding MSRP. The analysis helps in understanding the data distribution, relationships between features, and identifying patterns and trends.

## Installation
To run this notebook, you need to have Python and the following libraries installed:

- `pandas`
- `matplotlib`
- `seaborn`

You can install the required libraries using pip:

```bash
pip install pandas matplotlib seaborn
```

## Usage
Clone this repository and navigate to the project directory:

```bash
git clone <repository-url>
cd <project-directory>
```

Open the Jupyter Notebook:

```bash
jupyter notebook Car_Features_EDA.ipynb
```

Run the cells in the notebook to perform the analysis.

## Analysis
### Summary Statistics
Generates summary statistics for all columns in the DataFrame, including count, mean, standard deviation, min, max, and quartiles.

### Additional Statistical Measures
Calculates detailed statistics for numerical columns, including mean, median, mode, variance, and standard deviation.

### Unique Values in Categorical Columns
Counts the number of unique values in each categorical column.

### Visualizations
#### Distribution of Numerical Columns
Creates histograms with kernel density estimates (KDE) overlay for each numerical column to visualize their distributions.

#### Correlation Matrix
Generates a heatmap to visualize the correlation matrix of numerical columns, showing the strength and direction of relationships between features.

#### Pairplot
Creates a pairplot for selected numerical columns to visualize pairwise relationships and distributions.

#### Boxplots
Generates boxplots for each numerical column to show the distribution, central tendency, and variability of the data, as well as identifying outliers.

#### Trend Analysis
Visualizes the trend of average car prices over the years using a line plot to identify patterns such as increases or decreases in car prices over time.

## Inference
Based on the analysis, several inferences can be drawn about the data, such as trends in car prices, relationships between features, and identifying outliers. These insights can help in making informed decisions regarding pricing strategies, market positioning, and future investments in the automotive industry.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request if you have any improvements or new features to add.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
