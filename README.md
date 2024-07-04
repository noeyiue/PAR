# Repository Contents

This repository contains the necessary files to train models for multi-label classification tasks. Below are details about the files and instructions on how to use them.

## Files

### `Train_{model_name}.ipynb`
This Jupyter notebook is used to train a model. You can change the model to your desired PyTorch model by modifying the configuration.

## Training Instructions

1. **Set the Model Name:**
   Locate the `TrainingConfig` class or dictionary in the notebook. Find the `MODEL_NAME` attribute.

2. **Change the Model Name:**
   Change `TrainingConfig.MODEL_NAME` to the name of the PyTorch model you want to use.
   ```python
   class TrainingConfig:
       MODEL_NAME = "mobilenet_v3_small"

After finish training, model will be saved in `./{model_name}.pth`.

## Files

### `prob-predictions.ipynb`
This Jupyter notebook is used to predict test results. The prediction data will be saved in `./prob_predictions.csv`.

## Files

### `group_and_evaluation.ipynb`
This Jupyter notebook is used to evaluation a model. Evaluation result will be saved in `./performance_metrics.csv`. And all confusion matrix will be saved in `./confusion_matrix_{model_name}/`.

