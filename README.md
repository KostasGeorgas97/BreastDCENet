# BreastDCENet: Contrastive Learning for Breast DCE-MRI Analysis

A PyTorch framework for learning robust representations from breast Dynamic Contrast Enhanced MRI using contrastive learning. Designed to detect tumor enhancement patterns while preventing overfitting on limited medical datasets.

## Features
- 3D ResNet + temporal enhancement analysis
- Heavy regularization for medical data
- InfoNCE contrastive loss with label smoothing
- Mixed precision training with gradient accumulation
- Comprehensive data augmentation for 3D medical images
