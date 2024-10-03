# Swin UNETR-mini: Knowledge Distillation for Efficient 3D Medical Image Segmentation

This repository presents an innovative approach to knowledge distillation for efficient 3D medical image segmentation using the Swin UNETR and Swin UNETR-mini models. By leveraging the power of knowledge distillation, we aim to develop a compact and computationally efficient model while preserving the segmentation accuracy of its larger counterpart.

## Pretrained Models

The learned weights for the Swin UNETR and Swin UNETR-mini models are available at the following Kaggle dataset hosting links:

- [Swin UNETR](https://www.kaggle.com/models/therealcyberlord/swin-unetr-brats)
- [Swin UNETR-mini](https://www.kaggle.com/models/therealcyberlord/swin-unetr-mini)
  
## Code 
You can find the code for training and knowledge distillation in the BRATS folder, all experiments are evaluated on the BRATS 2021 dataset. BRATS/brats_swin_unetr3d.py is the script for training the mini Swin UNETR model with less number of features. BRATS/knowledge-distillation-swin-unetr.ipynb is the script for training the mini Swin UNETR model with knowledge distillation. 
