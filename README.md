# Motion Health Analytics

A comprehensive data analysis project focused on health metrics prediction using machine learning techniques, specifically K-Nearest Neighbors (KNN) and Random Forest algorithms.

## Project Overview

This project analyzes health-related motion data to predict key health metrics including age, height, and weight. The analysis includes data preprocessing, exploratory data analysis, missing value imputation, and predictive modeling with performance evaluation.

## File Structure

```
thanghoang7020202-ttmotionhealthanalytics/
├── dup_rows.txt                        # Duplicate rows analysis results
├── notations.txt                       # Project notes and annotations
├── requirements.txt                    # Python dependencies
├── tree.txt                            # Directory structure documentation
├── YAs47594876.ipynb                   # Main Jupyter notebook with analysis
├── documents/                          # Additional documentation
│   └── COMP4702_Report_47594876.pdf    # Main report
├── EDA/                                # Exploratory Data Analysis
│   └── Faultydata.PNG                  # Visualization of data quality issues
├── knn_outputs/                        # K-Nearest Neighbors results
│   ├── knn-age/
│   │   └── complete_age.txt            # Age prediction results
│   ├── knn_height/
│   │   └── complete_height.txt         # Height prediction results
│   └── knn_weight/
│       └── complete_weight.txt         # Weight prediction results
├── rf_confusion_matrices/              # Random Forest evaluation results
│   ├── result-age-normal.txt           # Age classification confusion matrix
│   ├── result-height-optimal.txt       # Height classification confusion matrix
│   └── result-weight-normal.txt        # Weight classification confusion matrix
└── tree_visualizations/                # Decision tree analysis and results
    ├── combined_output.txt             # Combined tree results
    ├── full-result-depth5.txt          # Tree results with depth 5
    ├── log_loss.txt                    # Log loss evaluation metrics
    ├── result-Age-depth15.txt          # Age prediction tree (depth 15)
    ├── result_height-depth15.txt       # Height prediction tree (depth 15)
    └── result_Weight-depth15.txt       # Weight prediction tree (depth 15)
```

## Key Components

### Data Analysis
- **Main Notebook**: `YAs47594876.ipynb` contains the primary analysis workflow
- **Data Quality**: Duplicate row detection and faulty data identification
- **EDA**: Comprehensive exploratory data analysis with visualizations

### Machine Learning Models

#### K-Nearest Neighbors (KNN)
- Implemented for predicting age, height, and weight
- Results stored in dedicated output directories
- Used for missing value imputation and prediction tasks

#### Random Forest
- Classification models for health metrics
- Confusion matrices generated for model evaluation
- Both normal and optimal parameter configurations tested

#### Decision Trees
- Multiple tree depths analyzed (depth 5 and depth 15)
- Log loss evaluation for model performance
- Separate models for each target variable (age, height, weight)

### Model Evaluation
- Confusion matrices for classification performance
- Log loss calculations for probability-based metrics
- Comparative analysis across different model depths and parameters

## Getting Started

### Prerequisites
Install required dependencies:
```bash
pip install -r requirements.txt
```

### Usage
1. Open the main Jupyter notebook: `YAs47594876.ipynb`
2. Run the cells sequentially to reproduce the analysis
3. Check the output directories for detailed results:
   - `knn_outputs/` for KNN predictions
   - `rf_confusion_matrices/` for Random Forest evaluation
   - `tree_visualizations/` for decision tree analysis

## Results Structure

### KNN Outputs
- Complete predictions for age, height, and weight
- Separate directories for each target variable
- Text files containing prediction results and performance metrics

### Random Forest Results
- Confusion matrices for model evaluation
- Different parameter configurations (normal vs optimal)
- Performance metrics for each health metric prediction

### Tree Visualizations
- Decision tree results with varying depths
- Combined analysis outputs
- Log loss evaluations for model comparison

## Data Quality Notes
- Duplicate rows identified and documented in `dup_rows.txt`
- Faulty data patterns visualized in `EDA/Faultydata.PNG`
- Data preprocessing steps documented in the main notebook

## Project Notes
- Additional annotations available in `notations.txt`
- Methodology and analysis notes included throughout the notebook and in COMP4702_Report_47594876.pdf