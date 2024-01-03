# Spam Classifier Using Machine Learning

## Overview
This repository contains the code and discussion for building a spam/no spam classifier using machine learning. The goal is to create a model capable of effectively distinguishing between spam and non-spam emails.

## Contents
- **Data Processing:** The dataset undergoes preprocessing steps, including converting boolean values to integers and removing duplicate rows.

- **Text Processing:** A function is developed to process text, retaining only alphabet letters, lemmatizing words, removing stopwords, and filtering out short words.

- **Model Training:** The machine learning model is trained to create a spam/no spam classifier. Hyperparameter optimization is explored to improve test accuracy and reduce overfitting.

- **Evaluation:** The model's performance is assessed, and considerations for further improvement are discussed, addressing the balance between precision and recall.

## Project Structure
- The main script for the project can be found in `src/spam_class.ipynb`.
- Raw data is stored in `data/raw/`.
- Trained models are saved in `models/`.

## How to Use
1. Clone the repository to your local machine.
2. Install the necessary dependencies using the provided `requirements.txt` file.
3. Follow the Jupyter Notebooks for step-by-step execution and understanding.

## Example Use Case
This project serves as a didactic example for building a spam classifier. While achieving acceptable results, there is room for improvement in hyperparameters or data cleaning for better model effectiveness.

Feel free to contribute and enhance the model by refining hyperparameters or suggesting improvements.

Happy coding!
