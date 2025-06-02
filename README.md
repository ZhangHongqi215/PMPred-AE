# PMPred-AE: Automated Detection of Pathological Myopia using Attention-Enhanced EfficientNetV2 and Grad-CAM

## Introduction
`PMPred-AE` is an advanced deep learning model designed for the automated detection of Pathological Myopia (PM), utilizing the EfficientNetV2-L architecture enhanced with an attention mechanism. The model employs Grad-CAM for generating interpretable visualizations, aiding in the understanding of AI-driven diagnostic decisions.

## Model Description
The `PMPred-AE` model combines EfficientNetV2-L for feature extraction and a custom classifier enhanced with an attention mechanism to focus on critical features indicative of PM.

### Feature Extraction
Using EfficientNetV2-L, pre-trained on the ImageNet dataset, allows for robust and efficient image feature extraction.

### Classification
An attention-enhanced fully-connected layer follows the feature extraction process to prioritize critical features for accurate PM detection.

## Grad-CAM Visualization
This method highlights the regions of interest in retinal images that the model focuses on, providing a heatmap visualization to support interpretative analysis.

## Installation
```bash
git clone https://github.com/ZhangHongqi215/PMPred-AE

