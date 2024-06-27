# PRODIGY_DS_04: Twitter Sentiment Analysis

This repository contains a Python script (`task_4.py`) that performs sentiment analysis on Twitter data, including data preprocessing, exploratory data analysis (EDA), and machine learning model training for sentiment classification.

## Description

The script follows these steps:

1. **Data Extraction**: Extracts data from a ZIP file containing Twitter datasets.
2. **Data Loading**: Loads the extracted CSV files into Pandas DataFrames.
3. **Data Cleaning**: Renames columns, handles missing values, and removes duplicates.
4. **Exploratory Data Analysis (EDA)**: Conducts various analyses, including summary statistics, sentiment distribution, and visualizations.
5. **Sentiment Analysis**: Applies VADER sentiment analysis to calculate sentiment scores.
6. **Advanced EDA**: Creates visualizations for sentiment distribution, sentiment by topic, and sentiment scores.
7. **Handling Imbalanced Data**: Applies resampling techniques to balance the dataset.
8. **Model Training**: Prepares data, vectorizes text, and trains a Random Forest Classifier for sentiment classification.
9. **Model Evaluation**: Evaluates the model's performance on training, test, and validation sets.
10. **Advanced Visualizations**: Generates additional visualizations, including heatmaps and word clouds.

## Requirements

To run this script, you'll need the following Python libraries:
* pandas
* numpy
* matplotlib
* seaborn
* nltk
* scikit-learn
* wordcloud

You can install these libraries using pip:

```
pip install pandas numpy matplotlib seaborn nltk scikit-learn wordcloud
```

## Usage

1. Clone this repository to your local machine.
2. Navigate to the repository directory.
3. Ensure you have the `archive.zip` file containing the Twitter datasets in the same directory.
4. Run the script using the following command:

```
python task_4.py
```

The script will execute, and you'll see the output and visualizations in your console or a separate window, depending on your system configuration.

## Contributing

Contributions to this project are welcome. If you have any suggestions, bug fixes, or improvements, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.

## Acknowledgments

* The Twitter dataset used in this project is sourced from the provided `archive.zip` file.
* The code utilizes various Python libraries, including pandas, numpy, matplotlib, seaborn, nltk, scikit-learn, and wordcloud.
