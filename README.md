# Car-Angle-Classification
</br>
Task : 

This project involves training a convolutional neural network (CNN) to classify images of cars based on their corresponding angles. The angle represents the click location relative to the car. The task is to achieve the best accuracy in classifying car images into their respective angle categories.

Dataset
The dataset consists of images of cars along with their corresponding angles. The images are categorized into different angle classes.

Total Images: 27,042
Classes: 8 (representing different angle ranges)
Model Architecture
The CNN model architecture used for classification is as follows:

Input Shape: 224x224 pixels with 3 channels (RGB)
Convolutional Layers:
Conv2D layer with 32 filters and ReLU activation
MaxPooling layer
Conv2D layer with 64 filters and ReLU activation
MaxPooling layer
Conv2D layer with 128 filters and ReLU activation
MaxPooling layer
Flatten Layer
Dense Layers:
Dense layer with 128 neurons and ReLU activation
Output Dense layer with softmax activation (number of neurons equals the number of classes)
Training
The model was trained for 3 epochs with the Adam optimizer and categorical cross-entropy loss function. The training data was augmented using image data generators with a validation split of 20%.

Model Evaluation
The model achieved an accuracy of XX% on the validation set after 3 epochs of training.

Prediction
The model can be used to predict the angle of a car in an image. Provide the path to the image you want to predict, and the model will output the predicted angle class.

Usage
To train the model, you can use the provided code. After training, you can save the trained model for future use.

Requirements
TensorFlow
Matplotlib
NumPy

Conclusion
This project demonstrates the use of CNN for classifying car images based on their angles.

# Results
</br>

![image](https://github.com/TusharPaul01/Car-Angle-Classification/assets/97314846/38e11a3a-fe84-4956-9cc9-de3c67fc3653)

![image](https://github.com/TusharPaul01/Car-Angle-Classification/assets/97314846/e821a0e4-8934-48fa-8d47-ba906458dce4)
