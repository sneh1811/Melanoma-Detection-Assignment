# Skin Cancer Detection using CNN

## General Information
This project aims to build a convolutional neural network (CNN) model to accurately detect various types of skin cancer, including melanoma. Melanoma is a deadly type of skin cancer that accounts for a significant portion of skin cancer deaths. Early detection is crucial for effective treatment, and a CNN model can assist dermatologists in diagnosing melanoma from skin images.

The dataset used in this project consists of 2357 images of malignant and benign oncological diseases, sourced from the International Skin Imaging Collaboration (ISIC). The dataset includes nine classes of skin diseases, including melanoma, nevus, squamous cell carcinoma, etc.

## Conclusions
- The CNN model developed achieved a maximum accuracy of around 85% on both the training and validation datasets, indicating good performance in classifying skin cancer types.
- Data augmentation techniques were employed to address issues of overfitting and underfitting, resulting in improved model performance and reduced risk of overfitting.
- Class imbalance was rectified using the Augmentor library, ensuring that each class had a sufficient number of samples for training.

## Technologies Used
- TensorFlow - version 2.0
- Keras - version 2.4.0
- Matplotlib - version 3.4.1
- Pandas - version 1.2.4
- Augmentor - version 0.2.8

## Acknowledgements
- This project was inspired by the need for early detection of melanoma, a deadly type of skin cancer.
- The dataset used in this project was obtained from the International Skin Imaging Collaboration (ISIC).
