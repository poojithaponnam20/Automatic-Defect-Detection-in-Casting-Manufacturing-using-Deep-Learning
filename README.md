# Automatic-Defect-Detection-in-Casting-Manufacturing-using-Deep-Learning
This GitHub repository contains a dataset and code for developing a deep learning classification model aimed at automating the inspection process in casting manufacturing, specifically focusing on submersible pump impeller top views.
# Dataset:
The dataset comprises a total of 7348 grayscale images, each of size 300x300 pixels, showcasing casting manufacturing products. These images capture various defects, including blow holes, pinholes, burr, shrinkage defects, and more. To enhance the dataset, augmentation techniques have been applied to ensure diversity in the training data.

Additionally, there are 1300 images of size 512x512 pixels, including 519 "good_front" and 781 "def_front" impeller images. These images were captured under stable lighting conditions, ensuring consistent quality across the dataset.

# Problem Statement:
Casting defects are undesired irregularities in the metal casting process. The current manual inspection process is time-consuming and prone to human inaccuracies, leading to potential rejections of entire orders and significant losses for the company. The goal is to address these challenges by automating the inspection process using a deep learning classification model.

# Classification Model:
The repository provides code for building a deep learning model capable of classifying images into two main categories: Defective and Good. The model is trained on a split dataset, with 3758 "def_front" and 2875 "good_front" images in the training set. The testing set contains 453 "def_front" and 262 "good_front" images.
