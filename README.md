# Exploratory Data Analysis on Eedi Misconceptions in Mathematics

This repository contains an Exploratory Data Analysis (EDA) on the dataset from the Kaggle competition: [Eedi - Mining Misconceptions in Mathematics](https://www.kaggle.com/competitions/eedi-mining-misconceptions-in-mathematics/data). The competition challenges participants to predict the affinity between misconceptions and incorrect answers (distractors) in multiple-choice questions, aimed at assisting human educators in improving the tagging process for mathematical misconceptions.

## Overview

The dataset consists of diagnostic questions designed to assess students' understanding of mathematical constructs. Each question includes:
- One correct answer.
- Three distractors (incorrect answers), each targeting a specific misconception.

The goal of this EDA is to uncover patterns, relationships, and key insights in the dataset that can aid in developing an effective NLP model for misconception prediction.

## Files in This Repository

- `misconceptions_EDA.ipynb`: The main Jupyter Notebook containing all EDA implementations, visualizations, and analyses.
- Dataset: The dataset used for this analysis can be found on the [competition's Kaggle page](https://www.kaggle.com/competitions/eedi-mining-misconceptions-in-mathematics/data).

## Key Features of the EDA

1. **Understanding the Data**:
   - Loaded and inspected the training, testing, and supplementary data files.
   - Explored the structure, dimensions, and descriptive statistics of the data.
   - Assessed missing values and data quality.

2. **Data Cleaning and Transformation**:
   - Removed duplicate rows.
   - Checked the distribution of null values.
   - Analyzed the presence of mathematical symbols in the question text.

3. **Exploratory Analysis**:
   - Distribution of misconceptions across answers.
   - Analysis of question text lengths and keyword occurrences.
   - Relationships between correct answers and misconceptions.
   - Grouped insights by constructs and subjects.
   - Visualizations including a word cloud of question texts.

4. **Statistical Insights**:
   - Examined correlations and trends in misconception tagging.
   - Frequency analysis of misconceptions across various attributes.

## Requirements

To run the EDA, the following libraries are required:
- Python 3.8+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- imbalanced-learn
- shap
- wordcloud

Install the required libraries using:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn shap wordcloud
```

## Instructions

1. **Download the Dataset**: 
   Obtain the dataset from the [Kaggle competition page](https://www.kaggle.com/competitions/eedi-mining-misconceptions-in-mathematics/data).

2. **Run the Notebook in Kaggle Environment**:
   - Upload the `misconceptions_EDA.ipynb` file to your Kaggle environment.
   - Load the dataset files in the same Kaggle kernel.
   - Execute the notebook to explore the EDA.

## Contributions

Feel free to fork this repository, submit issues, or propose pull requests to improve or extend the analysis.

## Acknowledgments

## Contributions

Feel free to fork this repository, submit issues, or propose pull requests to improve or extend the analysis.

## Acknowledgments

This analysis was inspired by: [Jules King, L Burleigh, Simon Woodhead, Panagiota Kon, Perpetual Baffour, Scott Crossley, Walter Reade, and Maggie Demkin. Eedi - Mining Misconceptions in Mathematics. https://kaggle.com/competitions/eedi-mining-misconceptions-in-mathematics, 2024. Kaggle.](https://kaggle.com/competitions/eedi-mining-misconceptions-in-mathematics)


## License

This project is licensed under the MIT License. See the `LICENSE` file for details.


