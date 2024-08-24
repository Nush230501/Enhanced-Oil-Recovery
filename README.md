# EOR Well Log Analysis

This repository contains a comprehensive Jupyter notebook focused on analyzing well log data to predict Enhanced Oil Recovery (EOR) outcomes using machine learning techniques. The analysis encompasses data preprocessing, feature selection, model training, and evaluation, with a focus on understanding the key factors that influence EOR.

## Table of Contents
- [Introduction](#introduction)
- [Data Loading and Preprocessing](#data-loading-and-preprocessing)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Model Training](#model-training)
- [Feature Importance Analysis](#feature-importance-analysis)
- [Model Evaluation](#model-evaluation)
- [Plot Interpretations](#plot-interpretations)
- [Conclusion](#conclusion)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [References](#references)

## Introduction

This project aims to predict the effectiveness of Enhanced Oil Recovery (EOR) techniques using well log data. By leveraging machine learning models, we can gain insights into the most critical geological and petrophysical parameters that influence EOR success.

## Data Loading and Preprocessing

The analysis begins by loading well log data and performing initial preprocessing steps:

- **Libraries Used**: `pandas`, `numpy`, `matplotlib`, `seaborn`, and `sklearn`.
- **Data Loading**: The dataset is loaded into a Pandas DataFrame for analysis.
- **Data Cleaning**: Missing values are handled, and relevant features are extracted for modeling.

## Exploratory Data Analysis

Exploratory data analysis (EDA) is performed to understand the structure of the data:

- **Displaying the Data**: The first few rows of the dataset are displayed to provide an initial overview.
- **Statistical Summary**: Descriptive statistics are generated to understand the distribution of features.
- **Correlation Analysis**: A correlation matrix is plotted to identify relationships between features.
- **Visualization**: Key features are visualized using histograms, box plots, and scatter plots.

## Model Training

Several machine learning models are trained to predict EOR outcomes:

- **Model Selection**: Models like Linear Regression, Decision Tree, and Random Forest are implemented.
- **Training**: The models are trained on the processed data, and hyperparameters are tuned for optimal performance.
- **Cross-Validation**: Cross-validation techniques are used to validate the models.

## Feature Importance Analysis

Feature importance is analyzed to determine the most influential factors in EOR prediction:

- **Feature Ranking**: The importance of each feature is ranked based on the model's outputs.
- **Visualization**: Important features are visualized using bar charts.

## Model Evaluation

The models are evaluated using various metrics to assess their performance:

- **Metrics Used**: Metrics such as Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared are calculated.
- **Evaluation**: The results are compared to determine the best-performing model.

## Plot Interpretations

The results are visualized and interpreted to understand the key findings:

- **Plot Types**: Various plots, including line plots, bar plots, and heatmaps, are used.
- **Interpretation**: Insights gained from the visualizations are discussed.

## Conclusion

The project concludes with a summary of the findings and suggestions for future work:

- **Summary**: A brief overview of the key findings is provided.
- **Future Work**: Potential improvements and future directions for research are discussed.

## Prerequisites

- Python 3.x
- Jupyter Notebook

## Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/EOR-Well-Log-Analysis.git
    ```
2. Navigate to the project directory:
    ```bash
    cd EOR-Well-Log-Analysis
    ```
3. Create and activate a virtual environment (optional but recommended):
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```
4. Install the necessary dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

To run the analysis on your local machine:

1. Open the Jupyter notebook:
    ```bash
    jupyter notebook EOR_Well_Log_Analysis.ipynb
    ```
2. Run the cells in the notebook to perform the analysis.

## Dependencies

- pandas==1.3.3
- numpy==1.21.2
- matplotlib==3.4.3
- seaborn==0.11.2
- scikit-learn==0.24.2

## Dataset

- Source: [Link to Dataset Source]
- Format: CSV
- Preprocessing Steps: [Briefly describe any preprocessing steps]

## Project Structure

```
EOR-Well-Log-Analysis/
│
├── data/
│   ├── raw_data.csv
│   └── processed_data.csv
│
├── notebooks/
│   └── EOR_Well_Log_Analysis.ipynb
│
├── src/
│   └── preprocessing.py
│
├── requirements.txt
└── README.md
```


## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or feedback, please contact [your-email@example.com].

## References

- [Reference 1](#)
- [Reference 2](#)
