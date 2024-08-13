# Lung_Diseases_Detection

📌 Detect lung disease's location in Chest X-Ray Images

## Overview
The detection and localization of diseases from Chest X-ray (CXR) images is a crucial task in medical diagnostics, enabling timely and accurate identification of various thoracic conditions. This project aims to leverage advanced machine learning and deep learning techniques to detect and localize distinct diseases from CXR images.

## Description
Chest X-ray (CXR) imaging is a fundamental diagnostic tool in medical practice, widely used for the assessment and management of various thoracic conditions. The objective of this project is to harness the power of machine learning and deep learning technologies to detect and localize ten specific diseases from CXR images: Edema, Pneumonia, Tuberculosis, Cardiomegaly, Emphysema, Covid, Effusion, and Atelectasis. The successful implementation of this project can significantly aid radiologists by providing a reliable, quick, and accurate diagnostic assistant, thus improving patient care and outcomes.

Switching from classification to object detection is necessary because Grad-CAM, used in classification tasks, often struggles to accurately indicate the precise locations of diseases within the CXR images. Object detection techniques, on the other hand, are designed to identify both the presence and the specific locations of diseases, thereby providing more actionable information for radiologists. This approach enhances the diagnostic utility of the system by highlighting the exact regions of interest in the X-ray images where abnormalities are detected.

## Data Description
#### Citations
- [NIH Chest X-rays](https://www.kaggle.com/datasets/nih-chest-xrays/data)

  📌 Select Edema, No Finding, Pneumonia, Tuberculosis, Cardiomegaly, Emphysema, Covid, Effusion, Atelectasis
- [Chest X-Ray(Pneumonia, Covid-19, Tuberculosis)](https://www.kaggle.com/datasets/jtiptj/chest-xray-pneumoniacovid19tuberculosis)
  
  📌 Select Only Covid-19 
- [Chest X-Ray Images(Pneumonia)](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)
  
  📌Select Only Pneumonia
- [Tuberculosis(TB) Chest X-ray Database ](https://www.kaggle.com/datasets/tawsifurrahman/tuberculosis-tb-chest-xray-dataset)
  
  📌Select Only Tuberculosis
  
#### Modifications to original data 
- We have modified the original dataset by selecting only 8 specific lung diseases. This targeted approach allows for a more detailed and accurate classification and detection system.
There are 9classes(8 diseases, and one for "No Findings")

- Edema
- No Finding
- Pneumonia
- Tuberculosis
- Cardiomegaly
- Emphysema
- Covid
- Effusion
- Atelectasis

## Display Grad CAM in Lung Diseases

### Label: Edema

![edema](https://github.com/user-attachments/assets/cdb574f6-d81a-4299-82c0-3320b58b6c02)

### Label: Pneumonia

![pneumonia](https://github.com/user-attachments/assets/37ca9149-32b4-4fde-aa92-7d53f28dde12)


## Display Bbox Examples
![box1](https://github.com/user-attachments/assets/ad158863-3fd7-4986-9fe5-c3dcd1cbdbf7)

![box2](https://github.com/user-attachments/assets/f7d37c96-2f55-4140-a21c-6ea1fd474026)

## Labeling
![de](https://github.com/user-attachments/assets/83a33f6a-9b26-4ef5-8ef4-3b730ca05b17)





