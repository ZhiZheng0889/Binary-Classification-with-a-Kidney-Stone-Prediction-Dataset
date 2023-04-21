# Binary-Classification-with-a-Kidney-Stone-Prediction-Dataset
This project uses KNN, SVM, and deep learning (RNN) models trained on the Kidney Stone Prediction based on Urine Analysis dataset.

# Kidney Stone Prediction based on Urine Analysis
This project applies KNN, SVM, and deep learning techniques to predict the presence of kidney stones in urine samples based on urine analysis data. The dataset used in this project is the Kidney Stone Prediction based on Urine Analysis dataset.

# Requirements
To run this project, you will need to have the following installed on your system:

- R version 4.0 or higher
- RStudio version 1.4 or higher
- Required R packages, including keras, tensorflow, caret, class, and readr

# Dataset
The Kidney Stone Prediction based on Urine Analysis dataset contains urine analysis data for patients, including various urine measurements. The target variable is the presence or absence of kidney stones in the urine.

The dataset is split into two CSV files: train.csv and test.csv.

# Running the Project
To run the project, follow these steps:

1. Clone the project repository to your local machine.
2. Open the RStudio project file (kidney_stone_prediction.Rproj) in RStudio.
3. Install the required R packages if you haven't already done so using install.packages().
4. Load the train.csv and test.csv datasets into RStudio using read_csv().
5. Preprocess the dataset using functions like train_test_split() and normalize().
6. Train KNN, SVM, and RNN models on the training data.
7. Evaluate the performance of the models on the validation and testing datasets using metrics like accuracy, precision, recall, and F1-score.
8. Use the models to predict the presence of kidney stones in new urine samples.
9. Create visualizations for model evaluation, such as confusion matrices, ROC curves, and training history plots.

# Conclusion
This project demonstrates how to use KNN, SVM, and deep learning techniques (RNN) in RStudio to predict the presence of kidney stones in urine samples based on urine analysis data. By following the steps outlined in this README, you can replicate this project on your own machine and adapt it to your own datasets and research questions.

