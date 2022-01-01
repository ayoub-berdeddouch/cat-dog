# Building a Flask app on Image Classification of Dog/Cat Dataset implemented by Convolutional Neural Network (CNN)

### Ayoub Berdeddouch
This is the project that we finished after ML ZoomCamp by [@ Alexey Grigorev](https://github.com/alexeygrigorev)

<p align="center">
  <img width="760" height="400" src="https://miro.medium.com/max/1838/1*oB3S5yHHhvougJkPXuc8og.gif">
</p>




## INTRODUCTION
### 1. The Dog vs. Cat Dataset
**Dogs vs. Cats** [dataset](https://www.kaggle.com/c/dogs-vs-cats/data) provided by  Microsoft Research contains 25,000 images of dogs and cats with the labels 
* 1 = dog
* 0 = cat 

### 2. Project goals
- Building a **deep neural network** using **TensorFlow**  & **Transfer Learning** to classify dogs and cats images.

- Making a **Flask application** so user can upload their photos and receive the prediction.

### 3. Project plan

During this project, we tackled these steps:

**A. Build the model**

    
**B. Build the Flask app**

**Front end**
- HTML
    - How to connect frontend to backend
    - How to draw a number on HTML
    - How to make UI looks good

**Back end**
- Flask
    - How to set up Flask
    - How to handle backend error
    - How to make real-time prediction
    - Combine the model with the app

## HOW IT WORK: CONVOLUTIONAL NEURAL NETWORK (CNN)

> In deep learning, a [convolutional neural network](https://en.wikipedia.org/wiki/Convolutional_neural_network) (CNN, or ConvNet) is a class of deep neural networks, most commonly applied to analyzing visual imagery. (Wiki)

For this project, we used **pre-trained model [MobileNetV2](https://keras.io/applications/#mobilenetv2)** from keras. MobileNetV2 is a model that was trained on a large dataset to solve a **similar problem to this project**, so it will help us to save lots of time on buiding low-level layers and focus on the application.

***Note:** You can learn more about CNN architecture [here](https://github.com/alexeygrigorev/mlbookcamp-code/tree/master/course-zoomcamp)*  chapter 8.

![](https://data-flair.training/blogs/wp-content/uploads/sites/2/2020/05/Cats-Dogs-Classification-deep-learning.gif)


## MODEL PERFOMANCE SUMARY
Our model has the accuracy of **99 %** for the train dataset and **98.67 %** for the test dataset. 

## FLASK APPLICATION
### Homepage
![]()
### Example of results

![]()

![]()




