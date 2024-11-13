
![Profile Views](https://komarev.com/ghpvc/?username=anay-a-joshi&color=green)  

# CS 5173 (Deep Learning) 
### Homework 3: Medical Image Segmentation    
```Level: Undergraduate```  
  
```Language: Python```  

## Overview
This repository contains code and models for ```Homework 3``` of the ```CS 5173``` ```Deep Learning``` course, focusing on segmenting retinal blood vessels using a U-Net architecture. The goal of this project is to train a U-Net model from scratch to perform accurate medical image segmentation, helping in the diagnosis of retinal diseases such as diabetic retinopathy and macular degeneration.

The dataset consists of high-resolution retinal fundus images, each with pixel-level annotations for blood vessel segmentation. The repository covers data pre-processing, model training with hyperparameter tuning, evaluation, and visualization of results.

## Repository Structure  
* ```With-Normalization```   
  - Contains 10 images capturing the Model's Training and Evaluation for U-Net configurations with normalization.
  - For each model (U-Net 2 Layers, U-Net 3 Layers, U-Net 4 Layers), there are:
    1. A **Training vs Validation Dice Coefficient Graph** (Dice Coefficient vs Epoch)
    2. A **Training vs Validation IoU Graph** (IoU Score vs Epoch)
    3. Final **Dice Score and IoU Score**
  - The final image is a **Model Demo** arranged in a 4x5 grid displaying Input, Label/True Mask, and predictions from each U-Net model configuration (2 Layers, 3 Layers, 4 Layers).

* ```Without-Normalization```    
  - Similar to the above folder, contains 10 images showing Training and Evaluation for Models without normalization, structured identically with:
    1. A **Training vs Validation Dice Coefficient Graph** for each model (Dice Coefficient vs Epoch)  
    2. A **Training vs Validation IoU Graph** for each model (IoU Score vs Epoch)  
    3. Final **Dice Score and IoU Score** for each model
  - The last image in this folder is also a **Model Demo** in a 4x5 grid layout with Input, Label/True Mask, and U-Net predictions (2 Layers, 3 Layers, 4 Layers).

* ```Anay_Joshi_Homework3_Normalization.ipynb```  
  - Code for U-Net model training **with normalization** on input images.
  - Includes steps for data pre-processing, model creation, training, and evaluation.

* ```Anay_Joshi_Homework3_Without_Normalization.ipynb```  
  - Code for U-Net model training **without normalization**.
  - Follows similar steps to the normalization version to allow for performance comparison.

* ```Homework3-AnayAbhijitJoshi.pdf```  
  - Project report covering all homework steps, including data analysis, model architecture, and performance results.
  
* ```README.md```  
  - Documentation of repository structure, setup, and usage instructions.

  
## U-Net Models  
* ```U-Net (2 layers)```  
* ```U-Net (3 layers)```  
* ```U-Net (4 layers)``` (Extra configuration)  

Each model is evaluated using the Dice Score and IoU metrics, with performance comparisons across configurations.


## Parameters in ``` test_model ``` function
* ```model_name```

``` 
  The 'test_model' function uses keyword-only arguments, and the given parameter is required.
  Ensure that you specify the parameter name when passing value(s).
```

