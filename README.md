# Ionosphere Radar Signal Predictor

This project implements an **Artificial Neural Network (ANN)** to classify radar returns from the ionosphere as either "Good" or "Bad." A "Good" return shows evidence of some type of structure in the ionosphere, while "Bad" returns do not.

## 🚀 Model Performance

The model was trained for **100 epochs**  and achieved the following results:

**Training Accuracy:** ~89.8% 


**Validation Accuracy:** ~91.5% 


**Final Training Loss:** 0.3541 


## 🏗️ Model Architecture

The neural network is built using the **Keras Sequential API**  with the following structure:

**Input Layer:** Dense layer with 10 units and ReLU activation.

**Hidden Layer:** Dense layer with 5 units and ReLU activation.

**Output Layer:** 1 unit with Sigmoid activation for binary classification.

**Optimizer:** Stochastic Gradient Descent (SGD).

**Loss Function:** Binary Crossentropy.


## 🛠️ Requirements

To run this notebook, you will need the following Python libraries:

* `tensorflow` (for Keras)
* `pandas`
* `scikit-learn`

## 📁 Project Structure

`inosphere radar signal predictor.ipynb`: The main Google Colab notebook containing data preprocessing, model building, and training.

`weight.keras`: The saved weights of the trained model.


## 📊 Dataset

The dataset consists of 34 continuous radar measurements (V1 to V34) and a "Class" label. It is automatically fetched from a public repository during the execution of the notebook.
