# Classify-News-Articles-by-Category

# News Article Classification

This project implements a machine learning model that classifies news articles into different categories such as Sports, Technology, Business, and more. The model uses article metadata and keywords for classification. A Random Forest Classifier is trained to predict the category based on features like word count, the presence of keywords, and estimated read time.

## Project Overview

This repository includes a Python-based implementation for classifying news articles using Random Forest. The classifier is trained on a dataset containing article metadata, and the model's performance is evaluated using confusion matrices, classification reports, and accuracy scores.

## Features

- **Classify News Articles**: Classifies articles into multiple categories like Sports, Tech, Business, etc.
- **Metadata Utilization**: Uses word count, keyword presence, and read time to predict the category.
- **Model Evaluation**: Evaluates the model's performance using confusion matrices and classification reports.
- **Random Forest Classifier**: A robust ensemble method used for classification.

## Requirements

To run this project, you'll need to install the following Python libraries:

- `pandas` — For data manipulation.
- `sklearn` — For machine learning algorithms and evaluation metrics.
- `seaborn` — For visualization.
- `matplotlib` — For plotting graphs.

You can install them using:

```bash
pip install pandas scikit-learn seaborn matplotlib
