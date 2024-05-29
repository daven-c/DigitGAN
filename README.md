# Instructions

## Virtual Environment Setup

1. Use python -m venv venv in terminal
2. Use pip install -r requirements.txt
3. Use .\venv\Scripts\activate

## 1. Hyperparameters and Models

Adjust values in settings.cfg\
Tune model parameters in TorchModels.py\
Change model hidden layer size where model instantiation occurs in the trainer.py files

## 2. Training

Option 1: TorchTrainerDCGAN.py, trains a deep convolutional model\
Option 2: TorchTrainer.py, trains a deep neural network model

## 3. Viewing Results

First, rename the best epoch model to GenModel.pth, delete other models if you wish\
Next set the filename variable in ViewResults.py to the model folder, and run

![image](https://github.com/daven-c/DigitGAN/assets/52761945/2b3eb009-15ca-4940-a473-947a07c64a1a)
