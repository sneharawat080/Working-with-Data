# Data Analysis on the Iris Dataset

This repository contains a Python script that performs exploratory data analysis (EDA) on the Iris dataset using Pandas, Matplotlib, and Seaborn.

## Features
- Loads the built-in Iris dataset from Seaborn.
- Filters data based on `petal_length > 1.5`.
- Computes mean values grouped by species.
- Performs aggregation on `sepal_length` and `petal_length`.
- Generates visualizations:
  - Histogram of Sepal Length.
  - Boxplot of Sepal Length by Species.
  - Scatterplot of Sepal Length vs. Sepal Width.

## Requirements
Make sure you have the following dependencies installed:
```bash
pip install pandas numpy matplotlib seaborn
```

## Usage
Run the script using:
```bash
python data_analysis.py
```

## Visualizations
The script generates the following plots:
1. **Histogram:** Distribution of Sepal Length.
2. **Boxplot:** Sepal Length variation across species.
3. **Scatterplot:** Sepal Length vs Sepal Width.

## Dataset
The Iris dataset is a well-known dataset in machine learning and statistics, containing 150 samples of iris flowers with four features:
- Sepal length
- Sepal width
- Petal length
- Petal width

## Contributing
Feel free to fork this repository, make improvements, and submit a pull request!

## License
This project is open-source and available under the MIT License.
