# Credit Risk Prediction Using German Credit Data  
This project focuses on prediciting credit risk using German Credit dataset (source: Hofmann, H. (1994). Statlog (German Credit Data) [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5NC77.). Various machine learning classification models have been implemented to understand their prediction prowess and real-world capabilities in analyzing credit risk in banking.  

## Project Overview

This repository demonstrates a machine learning project that predicts credit risk using the German Credit dataset. The project covers all essential steps including data preprocessing, model training, evaluation, and analysis. The core analysis is contained in a Jupyter Notebook, while a detailed project report is provided in PDF format.

## Repository Structure

```
credit-risk-prediction/
├── README.md                 # This file
├── .gitignore                # Specifies files/folders to ignore in Git
├── requirements.txt          # List of Python packages required for the project
├── notebooks/
│   └── credit-risk-prediction-using-german-credit-data.ipynb  # Main Jupyter Notebook
└── Report.pdf                # Detailed project report
```

- **README.md**: Provides an overview of the project, installation instructions, usage guidelines, and more.
- **.gitignore**: Lists files and directories to exclude from version control.
- **requirements.txt**: Contains all necessary dependencies.
- **notebooks/**: Houses the Jupyter Notebook that contains code for data preprocessing, model training, evaluation, and visualizations.
- **Report.pdf**: A comprehensive report detailing the methodology, experiments, results, and discussion of the project.

## Prerequisites

- Python 3.7 or higher
- Jupyter Notebook or JupyterLab installed

## Installation

Follow these steps to set up the project on your local machine:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/harman11singh/adsc4710-project-group-C.git
   cd credit-risk-prediction
   ```

2. **Create and Activate a Virtual Environment:**

   - On macOS/Linux:
     ```bash
     python -m venv venv
     source venv/bin/activate
     ```
   - On Windows:
     ```bash
     python -m venv venv
     venv\Scripts\activate
     ```

3. **Install Dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

## Running the Project

### Using the Jupyter Notebook

The primary analysis and model implementation are contained within the Jupyter Notebook. To run the notebook:

1. Launch Jupyter Notebook:
   ```bash
   jupyter notebook notebooks/credit-risk-prediction-using-german-credit-data.ipynb
   ```
2. Follow the cells in the notebook to execute data preprocessing, model training, evaluation, and visualizations.

### Reviewing the Report

For a detailed explanation of the methodology, analysis, and results, please refer to the `Report.pdf` file in the repository.

## Project Details

### Data Preprocessing

- **Cleaning:** Handle missing values using median imputation for numerical features and mode imputation for categorical features.
- **Encoding:** Convert categorical variables using one-hot encoding.
- **Scaling:** Standardize numerical features to normalize their distribution.
- **Splitting:** Partition the dataset into training and testing sets.

### Model Training & Evaluation

- **Models Implemented:** Logistic Regression, Decision Trees, Random Forests, and Support Vector Machines (SVM).
- **Hyperparameter Tuning:** Optimize model performance using grid search and cross-validation.
- **Metrics:** Evaluate models using accuracy, precision, recall, F1-score, and ROC-AUC.
- **Visualizations:** Generate confusion matrices and ROC curves to analyze performance.

## Contributing

Contributions are welcome! If you would like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes and push the branch.
4. Open a pull request detailing your changes.

If you encounter any issues or have suggestions, feel free to open an issue.

## Acknowledgements

- The German Credit dataset is sourced from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/statlog+(german+credit+data)).
- Thanks to the community and the documentation provided by [Scikit-learn](https://scikit-learn.org/stable/documentation.html) for support and guidance.
