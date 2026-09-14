# Fashion-MNIST Neural Network Assignment

This project contains the complete implementation of the Fashion-MNIST neural network assignment.

## Dataset

The project uses the Fashion-MNIST dataset containing 28x28 grayscale images from 10 clothing categories.

The images are normalized to the range 0 to 1.

## Parts Covered

### Part 1
Dataset loading, preprocessing and class distribution analysis.

### Part 2
Baseline neural network, activation function comparison and gradient analysis.

### Part 3
Comparison of categorical cross-entropy and mean squared error for classification, followed by a tabular regression experiment.

### Part 4
Comparison of:
- SGD
- SGD with momentum
- RMSProp
- Adam

Both a common learning rate and tuned learning rates are evaluated.

### Part 5
An intentionally overfitted model is trained using a small training set and a large neural network.

### Part 6
The following regularisation methods are evaluated:
- L2 weight decay
- L1 penalty
- Dropout
- Batch normalisation
- Early stopping
- Data augmentation
- More training data

### Part 7
Random hyperparameter search using 12 configurations and 5-fold cross-validation.

The hyperparameters include:
- Learning rate
- Hidden-layer width
- Dropout rate

The best configuration is retrained on the full training set and evaluated once on the held-out test set.

## Final Model

Selected learning rate: [VALUE]

Selected hidden-layer width: [VALUE]

Selected dropout rate: [VALUE]

Best regularisation method: [VALUE]

## Final Results

Test Accuracy: [VALUE]%

Macro Precision: [VALUE]

Macro Recall: [VALUE]

Macro F1: [VALUE]

Part 2 Baseline Accuracy: 87.63%

Improvement over baseline: [VALUE] percentage points

## How to Run

1. Open the notebook in Jupyter Notebook or Google Colab.
2. Make sure the Fashion-MNIST dataset is available at the path specified in Part 1.
3. Run all notebook cells from beginning to end.
4. Wait for all seven parts to finish.
5. The final model results and confusion matrix are produced in Part 7.

## Reproducibility

Random seeds are used throughout the experiments where applicable.

The hyperparameter search uses a fixed random seed of 42 so that the same 12 configurations can be selected again.

## Requirements

The main Python libraries used are:

- Python
- NumPy
- Pandas
- Matplotlib
- PyTorch
- Scikit-learn
