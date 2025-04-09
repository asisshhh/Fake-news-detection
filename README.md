## Fake News Detection
This repository contains a machine learning model designed to detect fake news. The goal is to use a combination of natural language processing (NLP) and classification techniques to classify news articles as either "real" or "fake."

## Libraries Used
pandas: A powerful data analysis and manipulation library for Python.

numpy: A library for numerical computations.

seaborn: A Python data visualization library based on Matplotlib that provides a high-level interface for drawing attractive statistical graphics.

matplotlib: A plotting library for creating static, animated, and interactive visualizations in Python.

scikit-learn: A library for machine learning that includes various algorithms and utilities for classification, regression, clustering, and more.

re: Python's built-in library for regular expression operations.

string: Provides common string operations.

## Usage
Load the dataset ( fake and real_news.csv) into the script.

Preprocess the text data by removing unnecessary characters, cleaning up whitespace, etc.

Split the data into training and testing sets using train_test_split.

Train a classification model ( Logistic Regression, Random Forest).

Evaluate the model's performance using accuracy and other metrics like the classification report.
## License
This project is licensed under the MIT License - see the LICENSE file for details.
