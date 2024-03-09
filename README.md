# SRIP 2024 Animal Classification

**This repository was created for SRIP-2024.**

Kaggle Notebook Link: https://www.kaggle.com/code/k0vidsharma/srip-2024/notebook

### It contains the following files:

1. **OnevsRestPrediction:** Contains all the results of the OnevsRest Classification using pre-trained and custom models.

2. **fiveclass_Prediction:** Contains all the results of the Five class Classification using pre-trained and custom models.

3. **srip-2024.ipynb:** Main Notebook

### Table of Contents of the Notebook:
1. Importing Libraries
2. Walking through data directory
4. Visualizing random images
   * Using Pillow library
   * Using Matplotlib
6. Setting up device agnostic code
7. Setting up helper functions
   * Function for creating dataloaders
   * Function for train step
   * Function for test step
   * Function for training
8. One Vs Rest Classification
   * Creating a Custom Dataset for One vs Rest classification
   * Creating the classification function
   * Getting a pre-trained model
   * Setting up transforms, loss-function and optimizers
   * Function to plot and save the loss and accuracy curves
9. 5-class Classification
   * Creating a Custom Dataset for 5 class classification
   * Creating the classification function
   * Getting a pre-trained model
   * Setting up transforms, loss-function and optimizers
   * Function to plot and save the loss and accuracy curves
10. Custom Model for Classification
    * Creating the Custom Model
    * For One vs Rest Classification
    * For 5-class Classification
12. Visualizing feature maps for Custom Model
    



