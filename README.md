##  Software and platform section
This project was implemented using Python 3.10+ in Jupyter Notebook. The required packages include:

- pandas – for data loading and manipulation

- numpy – for numerical operations

- scikit-learn – for preprocessing, cross-validation, and metrics

- PyTorch – for building and training the neural network

- matplotlib and seaborn – for visualizations, including confusion matrices

The code was developed and tested on Windows 10, but it is compatible with macOS and Linux. Standard CPU hardware was used, and GPU acceleration was not required.

## A Map of your documentation
### Data
CSV files containing the main dataset for obesity, and the initial training dataset and final test dataset
### Notebooks
Code jupyter notebooks for:
- EDA 
- Data splitting
- Random forest
- SVM
- Penalize Regression
- Neural Network
- Final test evaluation

### Output
Photo output of:
- KDE Plot of age distribution sorted by obesity category
- Height v. weight scatterplot colored by obesity category
- Outcome frequency for each obesity level pie chart
- Transportation type barchart for outcome frequency
- VIF table for regression analysis with original data
- VIF table for regression analysis with high-VIF features removed
- Age, height, weight boxplots
- Gender v. Smoking mosaic plot
- Confusion Matrix from the Neural Network and the Random Forest
- A decision tree model example
- A linear model using SVM
- A penalized linear model with ___ penalty
