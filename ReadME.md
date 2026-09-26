
# AI/ML Recruitment 2026

## Candidate Details

- **Name:** Priyansu Samal
- **Domain:** Artificial Intelligence and Machine Learning
- **Year:** Second Year
- **Institution:** SRM Institute of Science and Technology

---

## Tasks Completed

| Task | Project | Description |
|---|---|---|
| Task 1 | Air Quality Forecasting | Forecasting the next hour's CO concentration using historical air quality data and a Random Forest regression model. |
| Task 2 | MNIST Neural Network | Building and evaluating a neural network to classify handwritten digits from the MNIST dataset. |

---

# Task 1: Air Quality Forecasting

## Problem Statement

The objective of this task is to analyze historical air quality data, identify patterns in pollutant concentrations, and develop a machine learning model to forecast future air quality measurements.

The project focuses on predicting the next hour's carbon monoxide (CO) concentration using historical measurements and environmental features.

## Dataset

- **Dataset:** UCI Air Quality Dataset
- **Source:** UCI Machine Learning Repository
- **Data:** Hourly air quality measurements and environmental variables.
- **Target:** Next-hour CO concentration (`CO(GT)`).

## Approach

1. **Data Loading:** Loaded the dataset using Pandas and inspected its structure.
2. **Data Cleaning:** Removed empty rows, handled `-200` missing-value markers, and created a datetime column.
3. **Exploratory Data Analysis:** Visualized pollutant distributions, missing values, and changes in CO concentration over time.
4. **Feature Engineering:** Created time-based features, lag features, and rolling averages.
5. **Model Training:** Used a Random Forest Regressor with a chronological 80:20 training-testing split.
6. **Evaluation:** Evaluated predictions using MAE, MSE, RMSE, and R².
7. **Analysis:** Examined feature importance and prediction errors.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Results

The model was evaluated using the following regression metrics:

- **MAE:** To measure average absolute prediction error.
- **MSE:** To measure average squared prediction error.
- **RMSE:** To measure prediction error in the target's original units.
- **R² Score:** To measure how well the model explains variation in the target.

*The actual metric values and observations will be added after final model evaluation.*

## Limitations

1. The dataset contains missing values, particularly in the `NMHC(GT)` column.
2. The dataset represents measurements from a single monitoring location.
3. The model may not capture sudden changes in pollution caused by unusual events or changing environmental conditions.

---

# Task 2: MNIST Neural Network

## Problem Statement

The objective of this task is to build a neural network that classifies handwritten digits from 0 to 9 using the MNIST dataset.

The model learns patterns from labeled handwritten digit images and predicts the corresponding digit for unseen images.

## Dataset

- **Dataset:** MNIST Handwritten Digits
- **Input:** 28 × 28 grayscale images.
- **Classes:** Digits 0–9.
- **Task:** Multiclass image classification.

## Approach

1. Loaded the MNIST dataset.
2. Explored the dataset and visualized handwritten digit samples.
3. Normalized pixel values to the range 0–1.
4. Built a neural network using a hidden layer with ReLU activation and an output layer with Softmax activation.
5. Trained and evaluated the model.
6. Compared model configurations with different numbers of hidden neurons.

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Google Colab

## Results

Two model configurations were evaluated:

| Hidden Neurons | Test Accuracy | Test Loss |
|---|---:|---:|
| 128 | 97.50% | 0.0794 |
| 64 | 97.15% | 0.0918 |

The model with 128 hidden neurons achieved a test accuracy of **97.50%**.

---

# Key Learnings

1. Learned how to clean and preprocess real-world datasets, including handling missing values.
2. Gained practical experience in feature engineering, model training, and evaluating machine learning models.
3. Understood the fundamentals of neural networks and how model architecture can affect classification performance.

---

# Challenges Faced

1. Handling missing and invalid values in the air quality dataset.
2. Understanding how to create time-based features and prevent future information from leaking into the training data.
3. Learning how to build, train, and evaluate a neural network for handwritten digit classification.

---

# Repository Structure

```text
AIML-Recruitment-2026-PriyansuSamal/
├── README.md
├── Task-1-Air-Quality-Forecasting/
│   └── AIML_Recruitment_Air_Quality.ipynb
└── Task-2-MNIST-Neural-Network/
    └── AIML_Recruitment_MNIST.ipynb
```

---

## Acknowledgment

This repository was created as part of the AI/ML Recruitment 2026 tasks to explore data analysis, machine learning, and neural networks through hands-on projects.