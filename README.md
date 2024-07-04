
# Heart Disease Prediction Using Machine Learning, Deep Learning, and Explainable AI

## Project Overview

This project aims to predict heart disease using various machine learning and deep learning models. Additionally, the project incorporates explainable AI techniques to make the predictions more interpretable.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/heart-disease-prediction.git
    cd heart-disease-prediction
    ```
2. Set up a virtual environment:
    ```bash
    python3 -m venv venv
    source venv/bin/activate   # On Windows use `venv\Scripts\activate`
    ```
3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Data

The dataset used in this project is the [Heart Disease UCI dataset](https://archive.ics.uci.edu/ml/datasets/Heart+Disease). It contains various features related to heart health, and the goal is to predict the presence of heart disease.

## Usage

1. Launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
2. Open the `HeartDisease_Prediction.ipynb` notebook.
3. Run the cells in the notebook to execute the data exploration, preprocessing, modeling, and evaluation steps.

## Modeling

The project employs several machine learning and deep learning models, including but not limited to:
- Logistic Regression
- Decision Trees
- Random Forests
- Support Vector Machines
- Neural Networks (Multi-layer Perceptron)
- K-Nearest Neighbors
- Gradient Boosting
- XGBoost
- Naive Bayes

Each model's performance is evaluated and compared to select the best-performing model.

## Explainable AI

To make the model predictions more interpretable, the project utilizes explainable AI techniques such as:
- SHAP (SHapley Additive exPlanations)
- LIME (Local Interpretable Model-agnostic Explanations)

These techniques help in understanding the impact of different features on the model's predictions.

## Results

The results section of the notebook provides a summary of the model performances, including accuracy, precision, recall, and F1-score. The explainable AI techniques are also demonstrated to provide insights into the model's decision-making process.

## Contributing

If you wish to contribute to this project, please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.
