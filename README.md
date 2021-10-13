# AI_Pothole_detection
Custom object detection classifier, detecting Potholes on roads. Used Tensorflow Object Detection API

## Brief Summary
This repository is the application of learned knowledge of 'Object Detection Using Tensorflow'.

This model is trained to detect and differentiate 4 different classes,namely
1. Pothole
2. Pothole Group
3. Car
4. Auto

## Implementation
#### 1. Gather required images and label them.
I had got the Pothole images dataset from [Kaggle](https://www.kaggle.com/sachinpatel21/starter-code-to-view-dataset-images/data)
I had used [LabelImg](https://github.com/tzutalin/labelImg) which is an open tool for labelling your images.

#### 2. Training
I trained the model using TensorFlow v1.5 and this [GitHub commit](https://github.com/tensorflow/models/tree/079d67d9a0b3407e8d074a200780f3835413ef99) of the TensorFlow Object Detection API.
You have to choose the correct vesion of Tensroflow and compatible Tensorflow object Detection API Git Commit.Otherwise your code may be end up with lot of errors and code breaks.

#### 3. Model used: Faster-RCNN-Inception-V2-COCO model from TensorFlow's model zoo
TensorFlow provides several object detection models (pre-trained classifiers with specific neural network architectures) in its [model zoo](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/detection_model_zoo.md)