# **Chemical Mass Prediction** ⚗️

This project predicts the masses of chemicals (Mass C and D) based on the input masses of compounds A and B. It utilizes various machine learning models, including multi-output regression and other techniques, to generate accurate predictions. The final prediction is presented through a Tkinter GUI that accepts the masses of compounds A and B as input and displays the predicted values of masses C and D, along with graphical outputs.

## **Table of Contents** 📚

- [Overview](#overview)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Dataset](#dataset)
- [How It Works](#how-it-works)
- [Installation Guide](#installation-guide)


---

## **Overview** 🌟

The **Chemical Mass Prediction** project is built to predict the masses of chemical compounds based on given input masses using machine learning models. It employs a multi-output regression technique and other models to provide predictions for compounds C and D. A **Tkinter GUI** is provided for user interaction, where users input the masses of compounds A and B, and the program predicts the corresponding masses of compounds C and D, displaying the results visually with graphs.

---

## **Features** 🚀

- **Multiple Models**: Utilizes several machine learning models, including Linear Regression and MultiOutputRegressor, for chemical mass prediction.
- **Graphical Visualization**: Graphs of predicted vs actual values for the masses of chemicals A, B, C, and D.
- **Tkinter GUI**: A user-friendly interface to input masses of compounds A and B and display predicted masses of C and D.
- **Image Outputs**: Saves prediction graphs and GUI images for easy visualization and analysis.
- **Prediction for Masses C and D**: Based on input Mass A and B, predicts the values for Mass C and D.

---

## **Technology Stack** 🛠️

- **Python**: Primary language for implementing the machine learning models and GUI.
- **Machine Learning**: 
  - Scikit-learn for regression models (Linear Regression, MultiOutputRegressor).
  - Other models and techniques for better prediction.
- **Tkinter**: For building the GUI interface.
- **Matplotlib**: For graph plotting and visualization.
- **Pandas**: For handling the dataset.
- **NumPy**: For numerical operations.

---

## **Dataset** 📊

The dataset used in this project contains the following columns:

| Input  | Mass A | Mass B | Mass C | Mass D |
|--------|--------|--------|--------|--------|
| 0.0    | 1.0    | 1.0    | 0.0    | 0.0    |
| 0.5    | 0.95   | 0.95   | 0.05   | 0.05   |
| 1.0    | 0.904875 | 0.906125 | 0.093875 | 0.095125 |
| ...    | ...    | ...    | ...    | ...    |

The dataset consists of input values for **Mass A** and **Mass B**, along with their corresponding outputs for **Mass C** and **Mass D**.

---

## **How It Works** ⚙️

1. **Preprocessing**: The dataset is loaded, and necessary preprocessing steps are performed.
2. **Model Training**: Multiple models are used to train the data, with a focus on MultiOutputRegressor for predicting multiple outputs at once. The models evaluate the relationship between input values (Mass A and Mass B) and output values (Mass C and Mass D).
3. **Prediction**: The trained models are used to predict the masses of C and D based on user-provided values for A and B.
4. **Graphing**: Graphs of the predicted vs. actual values for all masses are generated.
5. **GUI**: A Tkinter-based graphical user interface accepts input from the user, predicts the corresponding masses, and displays the results with graphs.

---

## **Installation Guide** 🔧

### Prerequisites
Make sure to have Python installed on your system along with the following libraries:

```bash
pip install pandas scikit-learn matplotlib tkinter numpy
