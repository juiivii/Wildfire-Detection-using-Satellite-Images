This jupyter Notebook containing the complete workflow — from data preprocessing to model evaluation.
README.md: Project overview and usage instructions.

Objective: 
To develop an image classification model that can accurately detect the presence of wildfires in satellite images using deep learning techniques.

Techniques Used:
Image Preprocessing: 
Resizing images to a standard shape 
Normalization 
Data Augmentation (e.g., rotation, flipping)

Model Architecture: 
Convolutional Neural Network (CNN) built with TensorFlow/Keras

Training & Validation: 
Accuracy and loss tracked across epochs 
Evaluation using confusion matrix and classification report

Visualization: Training vs Validation Accuracy & Loss plots

Dataset: Source: https://www.kaggle.com/datasets/abdelghaniaaba/wildfire-prediction-dataset/code

Classes:
1. wildFire
2. No wildFire

Step: 
1.Preprocess the image data 
2.Build and train the CNN 
3.Evaluate the model on test data 
4.Requirements include: tensorflow, numpy, matplotlib, sklearn, and PIL.

Results: 
The CNN achieved high accuracy in classifying images as fire/no fire. 
Visualization plots show learning trends and potential overfitting/underfitting behavior.

Future Work: 
Test with real-time satellite data 
Improve model generalization with larger datasets 
Integrate with alert/notification systems for deployment

Author: Jivesh Karthik
