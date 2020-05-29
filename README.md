# Detecting Pneumonia in X-Ray Images Using Convolutional Neural Networks

Correctly diagnosing conditions and diseases of patients quickly and accurately allows for the timely treatment of patients as well as freeing up time for medical professionals that would have otherwise been spent diagnosing. If we can create a deep learning model that can accurately classify whether a patient has a condition or not, medical professionals will be able to use the models to better diagnose their patients. 

I'll be attempting to create a deep learning model that can accurately classify whether or not a patient has pneumonia or not by looking at their x-rays. Here's a quick look at some x-ray images from the dataset.

### Normal
<img src='https://i.imgur.com/XiAsJFS.png'>

### Pneumonia
<img src='https://i.imgur.com/DCoj0cd.png'>

## Models Used for Predictions

I'll be making a couple different neural networks to see which one has the best performance. 

The models I tested are:<br>
*Baseline Neural Network
*Convolutional Neural Network
*CNN with added layers and regularization
*Transfer Learning with VGG16
*Trainable VGG16 Model

## Baseline Neural Network
<img src='https://i.imgur.com/aBVbdxV.png'>
<img src='https://i.imgur.com/uVbUkUM.png'>

### Evaluation Metrics
Accuracy: 84%

## Convolutional Neural Network
<img src='https://i.imgur.com/zTKEWdh.png'>
<img src='https://i.imgur.com/g3SqVv7.png'>

### Evaluation Metrics
Accuracy: 86.86%
Precision: 82.91%
Recall: 99.49%
F1-score: 90.44%
Specificity: 65.81%

## CNN with Added Layers and Regularization
<img src='https://i.imgur.com/Id7ZDHM.png'>
<img src='https://i.imgur.com/r1NCIdF.png'>

### Evaluation Metrics
Accuracy: 93.43%
Precision: 91.65%
Recall: 98.46%
F1-score: 94.93%
Specificity: 85.04%

## Transfer Learning with VGG16
<img src='https://i.imgur.com/CAgsGJG.png'>
<img src='https://i.imgur.com/Ssro0hP.png'>

### Evaluation Metrics
Accuracy: 88.62%
Precision: 85.05%
Recall: 99.23%
F1-score: 91.60%
Specificity: 70.94%

## Trainable VGG16 Model
The architecture of the trainable vgg16 model is the same as the vgg model until the flatten layer.
<img src='https://i.imgur.com/gy41Hew.png'>
<img src='https://i.imgur.com/otQdZHH.png'>

### Evaluation Metrics
Accuracy: 90.54%
Precision: 87.19%
Recall: 99.49%
F1-score: 92.93%
Specificity: 75.64%

## Conclusion
The CNN model with added layers and regularization was the best performing model with an accuracy score of 93%. 
