# Support Vector Machines (SVM) - Classification Project

Welcome to the SVM Classification Project! In this project, we aim to build a classification model to predict whether mice infected with a virus will still be infected based on the dosages of two medicines they were administered. The data simulates a medical study, and our goal is to create an accurate predictive model. This README provides an overview of the project, its objectives, and key components.

## Project Objectives

The main objectives of this project are as follows:

1. Dataset Description:
   - Explore the mouse viral study dataset, which includes features such as "Med_1_mL" and "Med_2_mL" (dosage measurements) and the target variable "Virus Present" (indicating if the virus is still present).

2. Data Visualization:
   - Visualize the data by creating scatterplots to understand the distribution of data points and the relationship between dosage measurements and virus presence.

3. Support Vector Machines (SVM) Model:
   - Implement an SVM classification model to create a separating hyperplane that distinguishes between virus presence and absence.

4. Hyperparameter Tuning:
   - Explore the hyperparameters of the SVM model, including "C" (regularization parameter) and "kernel" (choice of kernel function).
   - Experiment with different kernel functions such as linear, radial basis function (RBF), and polynomial.

5. Grid Search for Hyperparameters:
   - Perform grid search to find the best combination of hyperparameters for the SVM model, maximizing accuracy.

6. Model Evaluation:
   - Evaluate the performance of the SVM model using cross-validation techniques.
   - Plot the separating hyperplane and visualize its effectiveness in classifying virus presence.

## Getting Started

To get started with this project:

1. Clone the repository to your local machine
2. Install the required Python packages listed in the project's requirements.txt file:
3. Explore the Jupyter Notebook files in the repository to understand the project's code and analysis.
4. Run the code to reproduce the analysis or experiment with the model as needed for your specific use case.
