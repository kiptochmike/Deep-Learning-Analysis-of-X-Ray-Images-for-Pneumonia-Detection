# Deep-Learning-Analysis-of-X-Ray-Images-for-Pneumonia-Detection



![Alternative text](https://github.com/Bree-009/Deep-Learning-Analysis-of-X-Ray-Images-for-Pneumonia-Detection/blob/main/banner.png)



### Project Overview
## Business Understanding
The project aims to develop a deep learning model for accurate pneumonia detection from chest X-ray images. This technology can enhance diagnostic speed and accuracy, benefiting healthcare professionals, patients, and healthcare systems.

### Technical Objectives
Develop and fine-tune a deep learning model for pneumonia detection.
Apply data augmentation and optimization techniques.
Evaluate model performance using metrics like accuracy, recall, and loss.

### Data Understanding
Dataset: 5,863 chest X-ray images categorized as "Pneumonia" and "Normal".
Origin: Pediatric patients aged 1-5 years from clinical care at Guangzhou Women and Children’s Medical Center.

### Model Development
Baseline Model
Dense Neural Network achieved a training accuracy of 93.94% and validation accuracy of 87.50%.
CNN Models
Model 2: Basic CNN showed overfitting with a training accuracy of 80.41% and validation accuracy of 56.25%.
Model 3: Enhanced CNN architecture achieved a training accuracy of 98.66% and validation accuracy of 75.00%.

### Model Evaluation
Model 3 outperformed Model 2 with better metrics: lower test loss, higher accuracy, and precision.

### Deployment
I deployed Model 3 using flask and it was able to make the predictions
![Alternative text](https://github.com/Bree-009/Deep-Learning-Analysis-of-X-Ray-Images-for-Pneumonia-Detection/blob/main/pneumonia.PNG)
