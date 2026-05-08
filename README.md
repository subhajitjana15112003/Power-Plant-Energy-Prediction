# Power-Plant-Energy-Prediction
Power Plant Energy Output Prediction using Artificial Neural Network (ANN)
# Power Plant Energy Output Prediction using ANN and PyTorch

## Overview
This project predicts the electrical energy output of a power plant using an Artificial Neural Network (ANN) implemented with PyTorch.

The model is trained on environmental parameters such as:
- Ambient Temperature
- Exhaust Vacuum
- Ambient Pressure
- Relative Humidity

The goal is to estimate the net hourly electrical energy output of the power plant.

---

## Technologies Used
- Python
- PyTorch
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

---

## Dataset
Dataset used:
- `powerplant_data.csv`

Features:
- Temperature (AT)
- Exhaust Vacuum (V)
- Ambient Pressure (AP)
- Relative Humidity (RH)

Target:
- Electrical Energy Output (PE)

---

## Machine Learning Workflow

### Data Preprocessing
- Data loading using Pandas
- Feature scaling using `StandardScaler`
- Train-test splitting

### Deep Learning Model
Artificial Neural Network Architecture:
- Input Layer
- Hidden Layer 1 (ReLU)
- Hidden Layer 2 (ReLU)
- Output Layer

### Training
- Loss Function: Mean Squared Error (MSE)
- Optimizer: Adam Optimizer
- Framework: PyTorch

---

## Project Structure

```bash
Power-Plant-Energy-Prediction/
│
├── ANN_Regresion.ipynb
├── powerplant_data.csv
├── README.md
└── LICENSE
