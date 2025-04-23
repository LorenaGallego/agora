# Basics of Deep Learning

This folder includes introductory materials from Ágora sessions on core Deep Learning concepts.

Each session typically includes:
- A short theoretical overview
- A hands-on Jupyter Notebook
- Optional slides or reference materials

### Topics covered
- Convolutional Neural Networks (CNNs)
- Recurrent Neural Networks (RNNs) & LSTMs
- Transformers

Materials are organized by session and presenter.

## CNN Session Notebook
The notebook for this session is designed to complement the theoretical session on Convolutional Neural Networks (CNNs).  

In this notebook, we cover:
- Training a **custom CNN classifier from scratch**.
- Using a **pretrained ResNet** for classification.
- Fine-tuning **YOLOv8** for object detection.
- Training a **Simple U-Net** and a **pretrained MONAI U-Net** for segmentation.
- Choosing the right **loss functions** and **evaluation metrics** based on the task.

> ⚠️ **Note:** This notebook is designed to be run on [Kaggle Notebooks](https://www.kaggle.com).  
> Some datasets need to be uploaded manually (see following information for details).

### Datasets used:
1. **[Brain Cancer - MRI Dataset (Kaggle)](https://www.kaggle.com/datasets/orvile/brain-cancer-mri-dataset)**  
   ✅ Available directly on Kaggle — can be added through “Add Data” in the notebook interface.

2. **[Brain Tumor Detection Dataset (Ultralytics)](https://docs.ultralytics.com/datasets/detect/brain-tumor/#sample-images-and-annotations)**  
   ➡️ Download manually from the Ultralytics website.  
   ➡️ Upload it yourself to Kaggle Datasets to use it in the notebook.

3. **[Pancreatic Stem Cells Dataset (Cell Tracking Challenge)](https://celltrackingchallenge.net/2d-datasets/)**  
   ➡️ Download manually from the Cell Tracking Challenge page.  
   ➡️ Upload it to Kaggle Datasets before running the segmentation part of the notebook.

## ⚠️ Important Notes About Kaggle Usage

- You will need to create a **Kaggle account** to use notebooks.
- Kaggle notebooks can be either **public** or **private**:
  - **Public notebooks** ❌ do not have internet access (so you cannot download pretrained models inside the notebook).
  - **Private notebooks** ✅ have internet access (allowing you to download weights, libraries, etc.) — but require **phone verification** on your account.
- If you are new to Kaggle, you can check out:  
  👉 [Kaggle Documentation: How to use Notebooks](https://www.kaggle.com/


---
