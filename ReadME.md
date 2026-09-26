# AI/ML Recruitment 2026

A collection of AI/ML projects exploring data analysis, machine learning, and neural networks as part of the AI/ML recruitment process.

## Candidate Details

* **Name:** Priyansu Samal
* **Institution:** SRM Institute of Science and Technology
* **Department:** Computer Science and Engineering
* **Year:** Second Year

## Tasks

### Task 1: Air Quality Forecasting

**Status:** Planned

Analyze historical air-quality measurements and build a machine learning model to predict future air quality using time-series data.

### Task 2: Neural Network — MNIST

**Status:** Completed

Build and train a neural network to classify handwritten digits from 0 to 9 using the MNIST dataset.

## Project Structure

```text
AIML-Recruitment-2026-PriyansuSamal/
│
├── README.md
│
├── Task-1-Air-Quality-Forecasting/
│
└── Task-2-MNIST-Neural-Network/
    └── AIML_Recruitment_MNIST.ipynb
```

## Task 2: MNIST Neural Network

### Problem Statement

Build a neural network that recognizes handwritten digits from 0 to 9 using the MNIST dataset.

### Approach

1. Load and explore the MNIST dataset.
2. Normalize image pixel values to the range 0–1.
3. Build a neural network using TensorFlow and Keras.
4. Use ReLU activation in the hidden layer and Softmax in the output layer.
5. Train and evaluate the model using accuracy and loss.
6. Visualize training curves and a confusion matrix.
7. Experiment with different hidden layer sizes and compare performance.

### Technologies Used

* Python
* TensorFlow and Keras
* NumPy
* Matplotlib
* Scikit-learn
* Google Colab

### Results

| Model                  | Test Accuracy | Test Loss |
| ---------------------- | ------------: | --------: |
| Baseline (128 neurons) |        97.50% |    0.0794 |
| Modified (64 neurons)  |        97.15% |    0.0918 |

### Key Learnings

1. Learned how to load and preprocess image data.
2. Understood neural network architecture and activation functions.
3. Learned to train and evaluate a classification model.
4. Interpreted accuracy and loss curves and a confusion matrix.
5. Explored how changing the number of hidden neurons affects performance.

### Challenge and Solution

**Challenge:** Preparing image data for neural network training.

**Solution:** Normalized pixel values to the range 0–1 and used a Flatten layer to convert each image into a one-dimensional vector.

## Task 1: Air Quality Forecasting

This section will be updated with the dataset, preprocessing, exploratory analysis, forecasting model, evaluation metrics, and findings after completing Task 1.

## How to Run

1. Open the relevant notebook in Google Colab.
2. Run the cells from top to bottom.
3. Review the outputs, visualizations, and results.

## Repository

This repository contains the notebooks, code, and documentation for the AI/ML recruitment tasks.
