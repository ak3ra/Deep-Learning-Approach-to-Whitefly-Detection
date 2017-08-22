# Deep-Learning-Approach-to-Whitefly-Detection
Summer 2017 internship project. Applications of deep learning in the Developing world.

The whitefly is an insect that affects Agricultural crops in Africa, current methods of control involve manually moving through fields 
to count the number of whiteflies per cassava leaf

In this project I propose the use of deep learning to automate this counting process by using an object detection approach.

# PROJECT STRUCTURE:

The notebook: whitefly_detection: This shows the methods used in data creation and processing,
### ARCHITECTURE OF CNN:
    Input layer

    Convolution layer: 7 filters of size 3x3
    Pooling layer: Max Pooling factor of 2
    Convolution layer: 12 filters of size 2x2
    Fully connected layer, with 500 hidden units

    Output

### Training Process:
  I ran the training process for 500 epochs and received 0.97063 training accuracy
  The model is saved and can be used to make predictions.
  
  
### Predictions  
 The predictions are shown in the TestNCount.ipynb notebook.
 

### Future Works
    Use transfer learning to improve overall accuracy of the model
    Use of modern state of the art object detection algorithms to test performance e.g using Faster RCNN,SSD.
    Increase the dataset and generate more training data.
 

 
