# Multi-Framework Neural Counter (PyTorch vs. TensorFlow)

This project explores a fundamental Machine Learning task: teaching a neural network to learn a numerical sequence (1-10) based on specific input coordinates.

## 🚀 Overview
The project demonstrates a full data lifecycle:
1. **Manual Data Entry**: Initializing training sets manually in PyTorch and TensorFlow.
2. **Model Architecture**: Using a single hidden layer with 4 units and a Sigmoid activation.
3. **Data Persistence**: Saving training losses and iterations to an Excel file using Pandas.
4. **Data Pipeline**: Importing the Excel data back into the environment to retrain the models.

## 🛠️ Frameworks Used
- **PyTorch**: Used for building a custom `nn.Module` class.
- **TensorFlow/Keras**: Used for a `Sequential` API implementation.
- **Pandas**: Managed the data export/import to `.xlsx` format.

## 📊 Results
Both frameworks successfully learned the sequence over 10,000 epochs, reaching a final Mean Squared Error (MSE) of approximately **0.007 - 0.009**.

## ⚙️ Setup
To run this project locally, install the requirements:
```bash
pip install -r requirements.txt
```
