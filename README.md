# Brain_Tumor_Detection
A Lightweight Customized EfficientNetB0 Model for Brain Tumor Detection using MR Images


### Brain Tumor Detection using CNN
This project demonstrates how to detect brain tumors from MRI images using a Convolutional Neural Network (CNN). The model is trained on a labeled dataset of brain scans and classifies whether a tumor is present or not.

### Project Overview
The research work includes Image preprocessing and augmentation, Construction of a custom CNN architecture, Model training and evaluation using accuracy and loss metrics, Visualizations including training curves and confusion matrix, Final prediction on test images to demonstrate real-world use.

### Dataset
The dataset consists of brain MRI images categorized into Tumor and No Tumor
The dataset is loaded from a local directory and split into training, validation, and test sets using ImageDataGenerator from Keras. You can download the dataset from here: https://drive.google.com/file/d/1Qaygsvknz60ivgTwfqnRSJwtAqYV4-Qq/view?usp=sharing

### Technologies Used
Python, tensorFlow / Keras, NumPy, Pandas, Matplotlib & Seaborn (for visualization), Scikit-learn (for evaluation metrics)

### Model Architecture
The CNN model includes Convolutional layers for feature extraction, MaxPooling layers for downsampling, Dropout layers to prevent overfitting, Dense layers with softmax activation for classification.
![Diagram](https://github.com/user-attachments/assets/34d09705-181b-4585-924d-92f06932bf32)


### Results
Achieved high accuracy on both training and validation sets, Model generalizes well to unseen test data, Visual results show strong performance on MRI test samples.

### Accuracy_Curve:
![training and validation accuracy](https://github.com/user-attachments/assets/667387ae-fa21-45cb-b444-732897b11ea1)


### Loss_Curve:
![training and validation loss](https://github.com/user-attachments/assets/d23316c9-797b-444f-81cb-58c4ddeb0f8e)


### Confusion_Matrix: 
![confusion matrix](https://github.com/user-attachments/assets/7c355e1e-77c2-4631-b20f-11c4e4e599a9)


### ROC_Curve: 
![ROC (2)](https://github.com/user-attachments/assets/200d9021-977c-428d-a144-f453ee5d8248)








