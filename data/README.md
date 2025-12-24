## Dataset Description

**Dataset**: 2018 Data Science Bowl – Nuclei Segmentation

The dataset consists of microscopy images for the task of cell nuclei segmentation.
Images exhibit significant variability in biological and imaging conditions, making the task challenging and realistic.

You can download it from Kaggle here:  
[2018 Data Science Bowl – Nuclei Segmentation](https://www.kaggle.com/competitions/data-science-bowl-2018/data)

**Image variability includes**:
- Different cell types
- Varying magnifications
- Multiple imaging modalities, including:
  - Brightfield microscopy
  - Fluorescence microscopy

**Data Structure**:
- The dataset is organized into train and test directories.
- Each image is stored in a separate folder identified by a unique image ID.

**Training set**:
- 670 image samples
- Each sample contains:
  - One microscopy image (.png)
  - A set of binary segmentation masks, where each mask corresponds to a single nucleus

**Test set**:
- 65 image samples
- Contains only microscopy images
- Ground truth masks are not provided

For this project, the training set will be further split into training and validation subsets to enable model selection and performance evaluation.