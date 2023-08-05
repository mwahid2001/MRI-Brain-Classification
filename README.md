# Axial MRI Brain Tumor Images Classification Using Simple CNN Archeticure 
Classification of axial MRI brain tumor images utilizing Simple Convolutional Neural Network (CNN) architecture, using **TensorFlow** . We aim to build a model that can effectively distinguish between **glioma, meningioma, pituitary tumor, and non-tumor cases.** Through deep learning techniques, we aim to contribute to medical image analysis, assisting in early tumor detection and diagnosis for improved patient care.
## Dataset Description
The **Br35H dataset** is a collection of T1-weighted contrast-inhanced MRI brain images obtained from various patients with different brain tumor types. The dataset is preprocessed to include only Axial views of MRI scans, which are commonly used for brain tumor analysis.
## Random Example of Each Class
![example](https://github.com/mwahid2001/MRI-Brain-Classification/assets/133688744/6448d2d6-346d-48e3-ae80-d21db1b337ec)
## Model Architecture
The CNN architecture used for this classification task is a simple and effective model, consisting of multiple Convolutional and MaxPooling layers, followed by flatten to flatten the inputs of the convolutional layers and Dense layers for classification. The model is implemented using TensorFlow and Keras.
## Contents
* **Data:** This directory contains Br35H dataset, filtered from any MRI brain images that are not Axial Views.
* **README.md:** This file provides an overview of the project.
* **axial.h5:** Contains the trained model saved.
## Results
The trained model achieves an accuracy 94% on the test dataset, demonstrating its effectiveness in classifying Axial MRI Brain Tumor Images, without augmentation or segmentation of the pictures.
## Acknowledgments
* The Br35H dataset is provided by **[Kaggle](https://www.kaggle.com/datasets/ahmedhamada0/brain-tumor-detection)** and is used for academic purposes.


Please note that the dataset might have been preprocessed or modified for specific use cases in this project, but its origins are attributed to **[Github](https://github.com/chengjun583/brainTumorRetrieval).**


