# Predicting Student Performance Using Machine Learning

## Project Overview
This project uses Machine Learning to analyze student-related factors and predict academic outcomes based on exam scores, study habits, attendance, family background, and school-related factors.

## Problem Statement
Can we predict whether a student will be a Good Performer (exam score >= 68) or Needs Improvement using student, family, and school factors?

## Objectives
- Analyze factors affecting student academic performance.
- Perform data cleaning and preprocessing.
- Conduct Exploratory Data Analysis (EDA).
- Visualize relationships between student factors and exam scores.
- Train and compare multiple Machine Learning classification models.
- Evaluate models using suitable performance metrics.

## Dataset
**File:** `StudentPerformanceFactors.csv`

The dataset contains student-related factors used for performance analysis and prediction.

Target categories:
- **Good Performer:** Exam score >= 68
- **Needs Improvement:** Exam score < 68

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Scikit-learn

## Project Files
- `predictive project vs code.ipynb` — Data analysis, visualizations, model training, and evaluation.
- `StudentPerformanceFactors.csv` — Dataset used for the project.
- `README.md` — Project documentation.

## Project Workflow
1. Load the dataset.
2. Check missing values and data quality.
3. Clean and preprocess the data.
4. Perform Exploratory Data Analysis (EDA).
5. Analyze relationships between features and student performance.
6. Create the target variable using the exam-score threshold.
7. Split data into training and testing sets.
8. Train multiple classification models.
9. Compare models and evaluate their performance.
10. Summarize findings and conclusions.

## Machine Learning Models
The notebook compares these five models:
- Logistic Regression
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Naive Bayes
- Decision Tree

## Model Evaluation
The models are evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Confusion Matrix
- Log Loss
- Cross-Validation

According to the results recorded in the notebook, Logistic Regression achieved the highest test accuracy of **98.41%** among the five models.

## How to Run the Project
1. Download or clone this repository.
2. Install Python and Jupyter Notebook, or use the Jupyter extension in VS Code.
3. Install the required libraries:

   `pip install numpy pandas matplotlib seaborn scipy scikit-learn jupyter`

4. Keep `StudentPerformanceFactors.csv` in the same folder as the notebook.
5. Open `predictive project vs code.ipynb`.
6. Run the notebook cells in order.

## Conclusion
This project demonstrates how Machine Learning can be used to analyze student performance and identify patterns associated with academic outcomes. The results may help identify students who could benefit from additional academic support.

## Author
Amit Kumar

## Course
Predictive Analytics (CA2)

## Disclaimer
This project is intended for educational purposes. Predictions may be imperfect and should not be used as the sole basis for decisions about individual students.
