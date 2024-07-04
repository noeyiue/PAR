# Repository Contents

This repository contains the necessary files to train models for multi-label classification tasks. Below are details about the files and instructions on how to use them.

## Files

### `Train_mobilenet_v3_small_1.ipynb`
This Jupyter notebook is used to train a model. You can change the model to your desired PyTorch model by modifying the configuration.

## Training Instructions

1. **Open the Notebook:**
   Open the `Train_mobilenet_v3_small_1.ipynb` file in Jupyter Notebook or Jupyter Lab.

2. **Set the Model Name:**
   Locate the `TrainingConfig` class or dictionary in the notebook. Find the `MODEL_NAME` attribute.

3. **Change the Model Name:**
   Change `TrainingConfig.MODEL_NAME` to the name of the PyTorch model you want to use. For example:
   ```python
   class TrainingConfig:
       MODEL_NAME = "resnet50"  # Change this to your desired model

4. **Run the Notebook:**
    Execute the cells in the notebook sequentially to start training the model. Ensure you have all dependencies installed and your data properly set up.

After finish training model with save to './{model_name}.pth
