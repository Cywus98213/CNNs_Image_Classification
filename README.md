# CNNs_Image_Classification
## Shoe Classification Project

**Course:** COMP3920SEF Machine Learning  
**Due Date:** 22 April 2025 (23:59)  
**Grade Weight:** 20% of the final grade, 40% of OCAS  

## Project Overview

This project applies machine learning techniques to classify shoe brands (**Nike, Adidas, Converse**). It explores different classification methods, including convolutional neural networks (**CNNs**) and transfer learning using pre-trained models like **YOLO** and **MobileNetV2**. The goal is to build an accurate model for image classification while implementing best practices in machine learning.

## Dataset Details

The dataset includes three classes of shoe brands in JPEG format, split into training, validation, and hidden test sets.

| Brand     | Training Set | Validation Set | Testing Set | Image Shape |
|-----------|-------------|---------------|-------------|-------------|
| Nike      | 200         | 30            | Hidden      | 240 × 240   |
| Adidas    | 200        | 30            | Hidden      | 240 × 240   |
| Converse  | 200        | 30            | Hidden      | 240 × 240   |

## Approach

- **Machine Learning Model:** CNNs and transfer learning techniques  
- **Frameworks Used:** TensorFlow and PyTorch  
- **Loss Function:** Categorical Crossentropy  
- **Validation Process:** Accuracy measurement and model evaluation  
- **Transfer Learning:** YOLO and MobileNetV2 feature extraction  
- **Hyperparameter Tuning:** Optimization for better accuracy  

## Training and Validation

- Data preprocessing applied to improve model performance  
- Regularization techniques used to prevent overfitting  
- Accuracy improvement through tuning learning rates and layers  
- Final model is saved in `.h5` (TensorFlow) or `.pth` (PyTorch) format  

## Model Testing

The notebook includes a dedicated section for loading and testing the trained model on validation data. This ensures model evaluation before final deployment.

## Submission Guidelines

Submit a ZIP file containing:
- A single **Jupyter Notebook (.ipynb)** with all integrated code  
- A **project report (PDF)** explaining the methodology  
- A **hyperparameter tuning table** (for COMPS492F students)  

## Future Improvements

- Expanding the dataset to improve accuracy  
- Experimenting with deeper CNN architectures  
- Optimizing inference speed for real-time classification  
- Deploying the model as a full-stack web application  

## Author

**Name:** Cheng Yui Wang, 
**Student ID:** 13845359
