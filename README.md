# Swin UNETR-mini: Knowledge Distillation for Efficient 3D Medical Image Segmentation

This repository presents an innovative approach to knowledge distillation for efficient 3D medical image segmentation using the Swin UNETR and Swin UNETR-mini models. By leveraging the power of knowledge distillation, we aim to develop a compact and computationally efficient model while preserving the segmentation accuracy of its larger counterpart.

## Pretrained Models

The learned weights for the Swin UNETR and Swin UNETR-mini models are available at the following Kaggle dataset hosting links:

- [Swin UNETR](https://www.kaggle.com/models/therealcyberlord/swin-unetr-brats)
- [Swin UNETR-mini](https://www.kaggle.com/models/therealcyberlord/swin-unetr-mini)
  
## Code 
You can find the code for training and knowledge distillation in the BRATS folder, all experiments are evaluated on the BRATS 2021 dataset. 


## Key Contributions

**Xingyu:**
- Conceptualized and formulated the research idea
- Designed and implemented the distillation loss training loop

**Matt:**
- Developed a dataset subsampling technique to curate high-quality training data
- Orchestrated precise computational cost analysis by determining FLOPs for model benchmarking

**Sakshi:**
- Conducted experiments across various model configurations and hyperparameters
- Visualized and analyzed results from experiments


Please note that since this project was developed using Jupyter Notebooks, line numbers are not available. However, the relevant code and resources can be found in the corresponding notebook files.
