# Exercise Classification using MLP (PyTorch)

This project implements a Multi-Layer Perceptron (MLP) neural network to classify physical exercises using user metadata such as heart rate, duration, calories, temperature, and body measurements.

## Model Details
- 2 Hidden Layers (128 neurons each)
- ReLU Activation
- Dropout (0.3)
- Adam Optimizer (LR = 0.001)
- ReduceLROnPlateau Scheduler
- Early Stopping

## Performance
- Test Accuracy: 87.67%
- Total Test Samples: 4500
- Correct Predictions: 3945

## Technologies Used
- Python
- PyTorch
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
