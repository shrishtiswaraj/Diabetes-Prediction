# Diabetes-Prediction

**Pima Indians Diabetes Dataset Classification**

This project implements a machine learning model to classify diabetic patients using the Pima Indians Diabetes Dataset. It utilizes Support Vector Machines (SVM) with a linear kernel for prediction.

**Getting Started**

1. **Prerequisites:**
   - Python 3.x
   - Necessary libraries: pandas, numpy, sklearn (including svm, StandardScaler, accuracy_score), pickle

2. **Installation:**
   Install the required libraries using pip:
   ```bash
   pip install pandas numpy scikit-learn pickle
   ```

3. **Running the Script:**
   - Clone or download this repository.
   - Open a terminal or command prompt and navigate to the project directory.
   - Run the script using:
   ```bash
   python your_script_name.py
   ```
   (Replace "your_script_name.py" with the actual filename of your Python script)

**Understanding the Script**

The script performs the following steps:

1. **Imports Libraries:** Imports necessary libraries for data manipulation, model building, and evaluation.

2. **Data Loading and Exploration:**
   - Loads the Pima Indians Diabetes dataset using pandas.
   - Explores the data by printing the first few rows, checking data types, and obtaining summary statistics.
   - Separates the features (X) and target variable (Y).

3. **Data Standardization:**
   - Creates a StandardScaler object to standardize the data (features) for better model performance.
   - Fits the scaler on the training data and transforms both training and testing data.

4. **Train-Test Split:**
   - Splits the data into training and testing sets using `train_test_split` from scikit-learn.
   - Stratifies the split based on the target variable to ensure balanced class distribution in both sets.

5. **Model Training:**
   - Creates a linear SVM classifier.
   - Trains the model on the training data.

6. **Model Evaluation:**
   - Evaluates the model's performance on both training and testing data using accuracy score.

7. **Prediction:**
   - Defines a sample input data point (replace with your actual data).
   - Converts the input data to a NumPy array and reshapes it for prediction.
   - Standardizes the input data using the fitted scaler.
   - Makes a prediction using the trained model.
   - Prints the predicted outcome (diabetic or non-diabetic).

8. **Saving the Model (Optional):**
   - Saves the trained model using pickle for future use (commented out in the example).

9. **Loading the Saved Model (Optional):**
   - Loads the saved model using pickle (commented out in the example).
   - Makes a prediction on a new data point using the loaded model (commented out in the example).

**Additional Notes**

- The script includes comments and explanations throughout the code for better understanding.
- Feel free to modify the sample input data for your own predictions.
- Saving and loading the model allows you to reuse the trained model without retraining every time.

I hope this README file provides a clear overview of the project!
