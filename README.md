# Quora Question Pairs

## Business Problem

Quora is a platform for gaining and sharing knowledge. It connects people who contribute unique insights and quality answers, empowering users to learn from each other and better understand the world. With over 100 million visitors every month, many questions on Quora are similarly worded, causing seekers to spend more time finding the best answer and making writers feel they need to answer multiple versions of the same question. Quora values canonical questions because they provide a better experience for both seekers and writers, offering more value to both groups in the long term.



## Problem Statement

- Identify which questions asked on Quora are duplicates of questions that have already been asked.
- This could be useful to instantly provide answers to questions that have already been answered.
- The task is to predict whether a pair of questions are duplicates or not.

## Project Overview

This project involves developing a machine learning model to detect duplicate questions on Quora, enhancing user experience by reducing redundant content. The project includes data preprocessing, feature extraction, model building, and deployment.

## Features

- **Advanced NLP Techniques**: Implemented tokenization, stemming, lemmatization, and named entity recognition to preprocess the text data.
- **Feature Engineering**: Designed token features to measure question similarity, including common non-stopwords, stopwords, and token matches.
- **Exploratory Data Analysis (EDA)**: Visualized data relationships with seaborn pairplots and created word clouds to analyze frequent words in duplicate questions.
- **Model Deployment**: Developed a user-friendly Streamlit interface for inputting question pairs and predicting their similarity.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Muhammad-Sheraz-ds/Quora-Question-Pairs.git
   ```

2. Install the required dependencies:

    ```
    pip install -r requirements.txt
    ```


## Contributing

Contributions are welcome! If you'd like to contribute to the project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a new Pull Request.