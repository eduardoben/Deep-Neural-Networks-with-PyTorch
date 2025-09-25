# CNN Image Classification — PyTorch

## Objective
Train and evaluate a convolutional neural network (CNN) classifier on labeled images to predict the class label and report standard performance metrics.

## Dataset
- Dataset loading logic is defined in the notebook (paths and splits in code cells).

## Analysis
- Data loading with PyTorch `DataLoader` and train/validation (and optional test) splits.
- Batch size: 1, 32
- Loss function(s): CrossEntropyLoss
- Optimizer(s): SGD
- Learning rate(s): 0.000001, 0.001, 0.01
- LR scheduler(s): CyclicLR
- Epochs: 10
- Metrics computed during/after training (accuracy and optionally precision/recall/F1/AUROC).

## Results and Conclusion
- Metrics are generated in the notebook output cells (training/validation/test).

The notebook contains code cells for model training loops, periodic evaluation, and plotting of losses/accuracies for visual inspection.
