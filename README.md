# Skin_lesion_segmentation
Skin Lesion Segmentation
Project Overview: This project implements a U-Net Convolutional Neural Network for segmenting skin lesions from dermoscopic images. The dataset used contains lesion images and corresponding masks to train and evaluate the model.

Technologies Used:

Python: For data processing and training.
PyTorch: For building and training the U-Net model.
Albumentations: For data augmentation.
OpenCV: For image manipulation.
Matplotlib: For visualizing results.
How It Works:

The project loads and augments dermoscopic images of skin lesions.
A U-Net model is defined and trained to predict the segmentation mask of the lesion.
The trained model is evaluated using various metrics to measure the accuracy of the segmentation.
Setup Instructions:

Clone this repository.
Install the required Python packages:
bash
Copy code
pip install torch torchvision albumentations opencv-python matplotlib
Download the dataset and place it in the appropriate directories (Training_Input, Training_groundTruth, etc.).
Run the script to train the model:
bash
Copy code
python skin_lesion_segmentation_with_eval(2).py
Usage:

The model will be trained using the dataset, and after training, it will predict and display the segmented lesions for evaluation.
