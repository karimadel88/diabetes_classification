# diabetes_classification

Diabetes Prediction using Logistic Regression, k-Nearest Neighbors, and Decision Tree

## Project Overview

Diabetes is a chronic condition that causes a person's blood sugar level to become too high, leading to various uncomfortable and potentially life-threatening symptoms. The prevalence of diabetes has been increasing globally, with significant health implications such as high blood pressure, increased risk of infection, heart disease, gastroparesis, damaged blood vessels, and pancreas malfunctioning (World Health Organization, 2018).



To address the growing concerns about diabetes, our team has selected the data from the National Institute of Diabetes and Digestive and Kidney Diseases for analysis. This dataset is based on a study conducted on the Pima Indians of Arizona, a group known to be affected by diabetes at a higher rate due to lifestyle and genetic factors.



The objective of this analysis is to predict, based on certain diagnostic measurements, whether a patient has diabetes or is likely to have diabetes. Three machine learning models, namely Logistic Regression, k-Nearest Neighbors (k-NN), and Decision Tree, will be employed to achieve this prediction.



## Dataset

The dataset used in this project is obtained from the National Institute of Diabetes and Digestive and Kidney Diseases. It consists of diagnostic measurements such as glucose level, blood pressure, body mass index (BMI), and age, along with the target variable indicating the presence or absence of diabetes.



Several constraints were applied to the selection of instances from a larger database:



- All patients are female.

- All patients are at least 21 years old.

- All patients are of Pima Indian heritage.



The dataset provides valuable insights into the diagnostic potential of these measurements in predicting diabetes.



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
