# BP Care Assistant

## Description
**BP Care Assistant** is a machine learning-based application designed to monitor and predict blood pressure health status. This tool leverages a Random Forest Classifier to analyze blood pressure readings and classify them into categories such as "Normal," "Elevated," "High Blood Pressure Stage 1," and "High Blood Pressure Stage 2." It aims to help users keep track of their blood pressure health and take necessary actions.

> **Note:** This project is currently a work in progress. Some features and functionalities are still being developed and fine-tuned.

## Project Overview
The goal of **BP Care Assistant** is to provide a simple yet effective way to analyze and classify blood pressure levels. The project involves data preprocessing, feature engineering, model training, fine-tuning, and prediction using Random Forest, a powerful ensemble learning method. The tool offers a user-friendly interface for inputting blood pressure readings and receiving instant feedback on health status.

### Key Features:
- **Data Preprocessing:** Handles missing values, drops unnecessary columns, and encodes categorical variables.
- **Feature Engineering:** Creates a target variable (`Health_Status`) based on systolic and diastolic blood pressure readings.
- **Model Training:** Splits the data into training and testing sets, and trains a Random Forest Classifier to predict health status.
- **Model Evaluation:** Evaluates the model using accuracy scores, confusion matrix, and classification reports.
- **Fine-Tuning:** Optimizes hyperparameters using GridSearchCV to enhance model performance.
- **Interactive Prediction Pipelines:** Integrates input widgets for easy and quick blood pressure status prediction.

### Target Variable:
The target variable *Health_Status* is defined based on systolic and diastolic blood pressure readings:

- **Normal:** Systolic < 120 and Diastolic < 80.
- **Elevated:** Systolic < 130 and Diastolic < 80.
- **High Blood Pressure Stage 1:** Systolic < 140 or Diastolic < 90.
-High Blood Pressure Stage 2:** Systolic >= 140 or Diastolic >= 90.

### Model Training:
The model is trained using a ***Random Forest Classifier:***

-The dataset is split into training and testing sets.
-The Random Forest model is trained on the training set to classify blood pressure status.

## Steps to Run the Project

1. **Clone the repository:**
   ```
   git clone https://github.com/Adithi13/BP_Care_Assistant.git

   ```
   
2. **Navigate to the project directory:**
      ```   
      cd BP-Care-Assistant

      ```
4. **Install the required libraries:**
      ```
       pip install -r requirements.txt

      ```

### Next Steps:
Since the project is still under development, the next steps include:

-Improving the user interface for better usability.
-Adding more features and refining the prediction algorithms.
-Conducting further testing to ensure robustness and accuracy.

### Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

### License
This project is licensed under the MIT License - see the LICENSE file for details.
