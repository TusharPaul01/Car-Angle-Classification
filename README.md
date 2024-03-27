# Car-Angle-Classification
</br>
Task : 

This project involves training a convolutional neural network (CNN) to classify images of cars based on their corresponding angles. The angle represents the click location relative to the car. The task is to achieve the best accuracy in classifying car images into their respective angle categories.

Dataset:
The dataset consists of images of cars along with their corresponding angles. The images are categorized into different angle classes.

Total Images: 27,042.
Classes: 8 (representing different angle ranges)
</br>
</br>
Model Architecture :
**</br>**
The CNN model architecture used for classification is as follows:

The model architecture consists of Conv2D layers followed by MaxPooling layers, gradually increasing filters. After flattening, dense layers process features for classification. Trained for 1 epochs with Adam optimizer, employing categorical cross-entropy loss. Data augmented via generators with 20% validation split.

Model Evaluation:
The model achieved an accuracy of 84% on the validation set after 1 epochs of training. To increase the accuracy we have to increase epochs.

Prediction
The model can be used to predict the angle of a car in an image. Provide the path to the image you want to predict, and the model will output the predicted angle class.

Requirements:
TensorFlow,
Matplotlib,
NumPy

Conclusion
This project demonstrates the use of CNN for classifying car images based on their angles.

# Results
</br>
Angle of the car:
-> 0 degrees

![image](https://github.com/TusharPaul01/Car-Angle-Classification/assets/97314846/992f47ea-b8f8-4754-84de-dfb42d2c086a)


Angle of the car:
-> 40 degrees

![image](https://github.com/TusharPaul01/Car-Angle-Classification/assets/97314846/390988c8-a951-41ab-a91d-3e23a2b9d657)


Angle of the car:
-> 180 degrees

![image](https://github.com/TusharPaul01/Car-Angle-Classification/assets/97314846/3faacdb0-8766-4d69-899c-19aea1bde478)

