Fraud Detection Analysis (EDA & Feature Importance Analysis)

Fraud Detection EDA Project
This project focuses on Exploratory Data Analysis (EDA) for detecting fraudulent transactions. The dataset used in this analysis is balanced_dataset_50_50.csv, which contains various features related to financial transactions.

Project Overview
The goal of this project is to analyze the dataset to identify patterns and features that distinguish fraudulent transactions from non-fraudulent ones. The EDA process includes data loading, data visualization, and preliminary feature importance analysis using a Random Forest classifier.

Key Steps
1.Data Loading and Inspection:

  Read the dataset into a pandas DataFrame.

  Display the first few rows, basic information, and summary statistics.

2.Missing Values Analysis:

  Check for missing values in the dataset.

  Visualize missing values using a heatmap.

3.Data Visualization:

  Plot histograms to understand the distribution of numerical features.

  Generate a correlation matrix to identify relationships between features.

  Create box plots to check for outliers in numerical features.

  Plot count of fraudulent vs non-fraudulent transactions.

  Use pairplots to visualize pairwise relationships between features.

  Generate bar plots for categorical variables.

  Plot distribution plots and scatter plots for numerical features.

4.Fraud Rate Analysis:

  Calculate and plot the fraud rate for the top 20 recipients by fraud rate.

5.Feature Importance Analysis:

  Prepare the data by identifying and encoding categorical columns.

  Define and train a Random Forest classifier using a pipeline.

  Extract and plot the top 10 features based on their importance in the model.

Technologies Used
  Python

  pandas

  numpy

  matplotlib

  seaborn

  scikit-learn

Visualizations
The project includes several visualizations to aid in understanding the data and identifying patterns related to fraudulent transactions. These visualizations include histograms, box plots, correlation matrices, count plots, pairplots, distribution plots, scatter plots, and bar plots.

How to Run
  1.Clone the repository.

  2.Ensure you have the necessary libraries installed (pandas, numpy, matplotlib, seaborn, scikit-learn).

  3.Run the provided Jupyter notebook or Python script to reproduce the analysis and visualizations.

Conclusion
This EDA project provides valuable insights into the dataset and lays the groundwork for further analysis and modeling efforts aimed at detecting fraudulent transactions. The visualizations and feature importance analysis highlight key patterns and features that can be used in predictive modeling.
