# Image Segmentation Using VIT on Cityscapes Datasets  

## Overview  

This project demonstrates image segmentation using Vision Transformers (VIT) on the Cityscapes dataset. The goal is to perform multi-tasking image segmentation, enabling the model to segment various objects in urban scenes effectively.  

## Objective  

The primary objectives of this project are:  
- To implement a multi-tasking image segmentation model using Vision Transformers.  
- To evaluate the model's performance on the Cityscapes dataset.  
- To explore the impact of different hyperparameters on model accuracy and efficiency.  

## Dataset  

The **Cityscapes dataset** is a large-scale dataset for semantic urban scene understanding. It contains high-resolution images with pixel-level annotations for various classes, including roads, vehicles, pedestrians, and more.  

## Model Used  

The project utilizes the **Vision Transformer (VIT)** architecture for image segmentation. VIT has shown promising results in various computer vision tasks by leveraging self-attention mechanisms.  


## Installation  

To run this project, ensure you have the following dependencies installed:  

```bash  
pip install torch torchvision transformers
