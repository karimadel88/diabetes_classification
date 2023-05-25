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

## Dataset Description



The "Diabetes" dataset contains various features related to diabetes patients. It includes the following attributes:



1. **Pregnancies**: Number of times pregnant.

2. **Glucose**: Plasma glucose concentration in an oral glucose tolerance test.

3. **BloodPressure**: Diastolic blood pressure (mm Hg).

4. **SkinThickness**: Triceps skinfold thickness (mm).

5. **Insulin**: 2-Hour serum insulin (mu U/ml).

6. **BMI**: Body mass index (weight in kg/(height in m)^2).

7. **DiabetesPedigreeFunction**: Diabetes pedigree function (a measure of the diabetes genetic influence).

8. **Age**: Age in years.

9. **Outcome**: Class variable (0 or 1) indicating the presence of diabetes.

## Code Overview



1. Importing Required Libraries: Imports necessary libraries for data analysis and visualization.

2. Load the data: Loads the "Diabetes" dataset.

3. Data Overview: Provides an overview of the dataset, including the first five rows, information about the columns, and descriptive statistics.

4. Data Preprocessing: Handles missing values by replacing zeros with null values and performs necessary data transformations.

5. Exploratory Data Analysis: Generates histograms, scatter matrices, correlation plots, covariance plots, and box plots to visualize and analyze the data.

6. Target Analysis: Analyzes the distribution of the target variable (Outcome) and shows the difference between the target categories.

7. Standard Scaling: Performs standard scaling on the data.

8. Splitting the Data: Splits the data into training and testing sets.

9. Applying Classification Algorithms: Applies three classification algorithms (Logistic Regression, K-Nearest Neighbors, and Decision Tree) to the data and evaluates their performance.

10. Model Comparison: Compares the accuracy scores of the three models using a bar plot.

11. ROC AUC Analysis: Plots the Receiver Operating Characteristic (ROC) curves and calculates the Area Under the Curve (AUC) for each model.



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

## Author
- Name: Karim Adel Eid

