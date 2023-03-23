![image](https://user-images.githubusercontent.com/68366503/227291364-e5aa6681-ae70-488b-adfc-de88456ba3b0.png)


## Classification of Retinal Diseases using RESNET Model

Developing a computer aided diagnosis tool to detect the presence of diabetic retinopathy and classify whether it is a normal DR or an abnormal DR.

## ABSTRACT 

Retinopathy is the most prevalent cause of avoidable vision impairment, mostly affecting the working-age population in the world. Recent research has given a better understanding in the clinical eye care practice to identify better and cheaper ways of identification and understanding, management, diagnosis and treatment of Retinal Diseases. In previous studies, the deep learning systems were usually trained directly end-to-end from original fundus images to the labels of DR grades, these end-to-end systems might fail to encode the lesion features due to the Black-box nature of deep learning. 

- In our study, we improved the image processing quality using RESNET model and increased the accuracy above 90 percentage. The GUI we developed classifies the images into different classes of DR.

Keywords: Diabetic Retinopathy, RESNET Model, Hemorrhage detection, Image processing quality, GUI.

## RESNET Model

ResNet, short for Residual Networks is a classic neural network used as a backbone for many computer vision tasks. This model was the winner of ImageNet challenge in 2015. The fundamental breakthrough with ResNet was it allowed us to train extremely deep neural networks with 150+layers successfully. Prior to ResNet training very deep neural networks was difficult due to the problem of vanishing gradients.

- Skip Connection — The Strength of ResNet ResNet first introduced the concept of skip connection. The diagram below illustrates skip connection. The figure on the left is stacking convolution layers together one after the other. On the right we still stack convolution layers as before but we now also add the original input to the output of the convolution block. This is called skip connection.

![image](https://user-images.githubusercontent.com/68366503/227286215-e8c09dbf-ddb5-480b-b325-0f0f3fca0951.png)

## Software Requirements PyTorch:

PyTorch is an open source machine learning framework based on the Torch library that may be used for applications like computer vision and natural language processing. The framework is designed to accelerate the transition from research prototyping to implementation.

## Tkinter

Tkinter is Python's standard GUI library. Python and Tkinter make it simple and quick to design graphical user interfaces. Tkinter gives the Tk GUI toolkit a robust object-oriented interface. Tkinter should be imported.

## Modules

OpenCV, Keras, NumPy, etc. are some of the modules in Python that are used in the project. These modules are used for image pre-processing, training the model, and testing the model.

## MOTIVATION

- Diabetic retinopathy is an eye condition that can cause vision loss and blindness in people who have diabetes.
- Diabetic retinopathy (DR) is a common diabetes complication that occurs when the retina's blood vessels are damaged due to high blood sugar levels, resulting in swelling and leaking of the vessels.
- Our goal is to classify the patients having diabetic retinopathy and not having the same, with a high-resolution fundus image of the retina.

## OBJECTIVES

- We process the input retinal images into normal or abnormal retinal images.
- The GUI we develop uses RESNET model for better processing of images.
- In our Study, we classify the images by the way of pre-processing and feature extraction process.
- In these processes we transform the raw images into more informative images.

## SCOPE OF THE PROJECT

- This GUI detects the type of diabetic retinal disease. The accuracy of image processing will be above 90 percentage.
- It can process nearly up to 3000 images.

## PROPOSED SYSTEM DIAGRAM
![image](https://user-images.githubusercontent.com/68366503/227286406-35427b48-580c-46a1-a5ae-ec10855dc71c.png)


## STEP FOR PROJECT

1. TRAINING THE MODEL:
A RESNET model with 152 layers is pretrained using pytorch with 3662 images.

2. TESTING THE MODEL:
Testing the trained model with a sample images of about 20 and classifying the images into different classes of DR. 

These 5 classes include: 
- No DR 
- Mild 
- Moderate,
- Severe 
- Proliferative DR

3. DEVELOPING A GUI:
A user interface is developed which is user friendly developed using tkinter. This GUI asks for the retinal image and gives the report of the classified retinal image.

## CONCLUSIONS AND FUTURE WORK
In this project, we are able to classify the images into different stages of DR using the pretrained RESNET model. The GUI we developed will be helpful for both doctors and also the common people.

Our future work is to convert the GUI into a mobile application. We are also trying to improve the accuracy.

## Output after testing the sample images
![image](https://user-images.githubusercontent.com/68366503/227287048-fc8d13fb-2467-4703-9937-705a846e0d96.png)

## GUI developed
![image](https://user-images.githubusercontent.com/68366503/227287458-164cd18a-18b2-4fae-811f-2eea8dcdbe12.png)

## NO DR OUTPUT
![image](https://user-images.githubusercontent.com/68366503/227287786-36f3492b-4558-4360-b9ca-cac595b402df.png)

## Mild 
![image](https://user-images.githubusercontent.com/68366503/227288175-bbda40d6-68ff-4f9e-9c8f-3ac7b850571e.png)

## MODERATE
![image](https://user-images.githubusercontent.com/68366503/227288555-05c5e2b5-4cd1-4289-add7-9872bba38e81.png)

## PROLIFERATIVE DR
![image](https://user-images.githubusercontent.com/68366503/227288807-d50d64e2-42fd-4a92-a5bb-6d867598f9fa.png)

## Output in the console
![image](https://user-images.githubusercontent.com/68366503/227288988-9dff5966-ead9-4fbd-92a8-e4de044faf57.png)
