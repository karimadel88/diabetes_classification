# diabetes_classification

Diabetes Prediction using Logistic Regression, k-Nearest Neighbors, and Decision Tree

## Project Overview

This project aims to predict the occurrence of diabetes in individuals using three different machine learning models: Logistic Regression, k-Nearest Neighbors (k-NN), and Decision Tree. The dataset used for this project is the Pima Indians Diabetes Database.

The project involves performing exploratory data analysis, data preprocessing, model training, evaluation, and comparison of the three models. The objective is to assess the performance of each model in predicting the presence or absence of diabetes based on the provided features.

## Dataset

The dataset used in this project is the Pima Indians Diabetes Database. It contains various features such as glucose level, blood pressure, body mass index (BMI), and age, along with the target variable indicating the presence or absence of diabetes.

The dataset can be obtained from [https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database].

## Requirements

- Python
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

## Project Structure

The project directory has the following structure:

```
- README.md
- diabetes_prediction.ipynb 
- diabetes.csv
```

- `diabetes_prediction.ipynb`: Jupyter Notebook containing the project code and analysis.
## Instructions

1. Install the required dependencies listed in the "Requirements" section.
2. Clone or download the project repository.
3. Place the `diabetes_data.csv` file in the `data/` directory.
4. Open the `diabetes_prediction.ipynb` notebook using Jupyter Notebook or any compatible environment.
5. Run the notebook cells sequentially to perform the data analysis, preprocessing, model training, evaluation, and comparison.

## Results

The project generates the following results:

- Accuracy comparison: A bar chart comparing the accuracy scores of the three models (Logistic Regression, k-NN, Decision Tree).
- ROC curves: ROC curves for each model, showing the trade-off between true positive rate and false positive rate.

## Conclusion

Through this project, we analyzed the Pima Indians Diabetes Database and applied three different machine learning models to predict the occurrence of diabetes. The models (Logistic Regression, k-NN, Decision Tree) were evaluated and compared based on their accuracy scores and ROC curves.
