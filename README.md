# Dimension Reduction Techniques in Machine Learning

## Project Overview
This project explores various dimension reduction techniques in machine learning, focusing on their impact on classification accuracy. It was developed as part of a university course, serving as the second machine learning project in the curriculum.

## Features
- Implementation of multiple dimension reduction methods:
  - SelectKBest with different scoring functions (f_classif, chi2, mutual_info_classif)
  - SelectPercentile
  - Principal Component Analysis (PCA)
  - Linear Discriminant Analysis (LDA)
- Comparison of classification accuracy using Gaussian Naive Bayes classifier
- Visualization of results using matplotlib

## Dependencies
- pandas
- scikit-learn
- matplotlib
- numpy (implied through scikit-learn usage)

## Dataset
The project uses a dataset named "all_data.csv". Ensure this file is in the same directory as the script.

## Code Structure
1. Data loading and preprocessing
2. Initial model training without dimension reduction
3. Implementation of SelectKBest with various scoring functions
4. Implementation of SelectPercentile
5. Implementation of PCA
6. Implementation of LDA
7. Visualization of results for each method

## Key Findings
The project compares the classification accuracy of different dimension reduction techniques against the baseline (no dimension reduction). The results are visualized using bar plots, allowing for easy comparison of the effectiveness of each method.

## Future Improvements
- Experiment with other classifiers beyond Gaussian Naive Bayes
- Implement cross-validation for more robust accuracy estimates
- Explore other dimension reduction techniques like t-SNE or UMAP
- Analyze the computational efficiency of each method

## How to Run
1. Ensure all dependencies are installed
2. Place the "all_data.csv" file in the same directory as the script
3. Run the script using a Python interpreter


## Note

This project is part of a learning process. The code and approach may not be optimal or suitable for production use.
