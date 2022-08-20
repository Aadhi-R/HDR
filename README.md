# HDR
Handwritten Digit Recognition using Faster R-CNN

HDR is a Deep-learning model which detects digits written by hand.It is the ability of a computer to recognize the human handwritten digits from different sources like images, papers, touch screens, etc, and classify them into 10 predefined classes (0-9)

The code present in the repositary implements a model proposed by a journal paper titled "_An improved faster‑RCNN model for handwritten character
recognition_" published under the 'Arabian Journal for Science and Engineering'.

1.For HDR, a speedier, more specific deep learning model has been implemented using the existing modules present in python. 

2.Customized Faster Regional Convolutional Neural Network is the name of the model (Faster-RCNN). 
  2.1 The region of interest is first determined by doing annotation insertion. 
  2.2 The deep features are then computed using the Faster-RCNN, which introduces DenseNet-41. 
  2.3 The digits are then localised and divided into ten classes using the regressor and classification layer (0-9). 
  
3.The MNIST dataset was used in this study. 

4.This design employs DenseNet-41 architecture that acts as the feature-extraction tool. It reduces the number of parameters to a bare minimum which makes it cost-efficient. It holds the winning accuracy of 99.78%.



