# Credit Card Fraud Detection

## Project Data

* A Project developed using Python.
* This project deals with detecting fraudulent transactions in credit card data.
* The dataset used in this project is `creditcard.csv`.
* The project includes data preprocessing, visualization, and model training for fraud detection.

## Programming Language Used

* **Python**

## Author

* **Uppalapati Suchith Chowdary**

## Prerequisites

### Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

# Quick Start 🚀

### Initialization Files

1. Prepare the dataset file named `creditcard.csv`.

### Run the Jupyter Notebook

1. Open the Jupyter Notebook file `Code File.ipynb`.
2. Ensure that the `creditcard.csv` file is in the same directory as the notebook.
3. Execute the cells in the notebook to preprocess the data, visualize it, and train the fraud detection models.

### Files and Outputs

The notebook will guide you through the following steps:

1. Load and explore the dataset.
2. Sample a fraction of the data for faster processing.
3. Visualize the data using histograms and a correlation matrix heatmap.
4. Preprocess the data for model training.
5. Train and evaluate two outlier detection models: Isolation Forest and Local Outlier Factor.

### Get Results

After running the notebook, you will obtain:

1. Visualization plots showing the distribution of features and correlations.
2. Model evaluation metrics such as classification report and accuracy score.

## Detailed Steps

1. **Data Loading and Exploration**: Load the `creditcard.csv` dataset and explore its structure and contents.
2. **Data Sampling**: Randomly sample a fraction of the data to speed up processing.
3. **Visualization**: Plot histograms of each feature and a heatmap of the correlation matrix.
4. **Preprocessing**: Prepare the data by selecting features and the target variable.
5. **Model Training and Evaluation**: Train the Isolation Forest and Local Outlier Factor models and evaluate their performance.

## Example Commands

Here are some example commands to run parts of the notebook directly from the command line (optional):

### Running Data Exploration

```bash
jupyter nbconvert --to notebook --execute Code\ File.ipynb --ExecutePreprocessor.timeout=600 --output output_notebook.ipynb
```

This will execute the entire notebook and save the output in `output_notebook.ipynb`.

## Note

Ensure that all required libraries are installed, and the dataset is available in the working directory before running the notebook.
