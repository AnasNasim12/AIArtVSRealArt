# AI-Generated vs. Real Images Classifier
## Overview
This project aims to classify images into two categories: AI-generated images and real images. The motivation behind this project is to distinguish between authentic images and those created by artificial intelligence.

## Prerequisites
Before running this project, ensure you have the following prerequisites installed and set up:
- NumPy, PyTorch, Matplotlib, Timm, Torchmetrics, cv2

## Dataset
The dataset used for this project is available on Kaggle and can be downloaded directly into your project directory using the Kaggle API. The dataset is titled "AI Generated Images vs. Real Images" and consists of two main categories representing the two classes of images we aim to classify.

![Initial Visualisation of data](https://github.com/AnasNasim12/AIArtVSRealArt/assets/106335309/199b4a92-9ca9-4fc5-89cb-6f1f3772fb5b)
Initial Visualisation of data

![Dataset class imbalance analysis (Can be fixed in future)](https://github.com/AnasNasim12/AIArtVSRealArt/assets/106335309/c836f486-a868-41be-a28e-c25f24e2e7d0)
Dataset class imbalance analysis (Can be fixed in future)

I used the pretrained [RexNet_150 model](https://paperswithcode.com/lib/timm/rexnet) for this project. It was a viable option because of it's classification scores.

![image](https://github.com/AnasNasim12/AIArtVSRealArt/assets/106335309/39f56b7a-c8b1-49e5-b85b-f731ddd96494)

The accuracy of the model on test data came out to be **80%** in this experiment. 
![Results on test data](https://github.com/AnasNasim12/AIArtVSRealArt/assets/106335309/e1d4fce4-4070-41e8-bcd9-c3c178ae5449)
Prediction results on test data


**Overall, this project could serve as a preliminary to high-end classifiers that can help us identify real, organic and authentic images from the AI generated ones. In the future, this could be coupled with even more powerful CNNs to improve accuracy and be trained on larger datasets.**

