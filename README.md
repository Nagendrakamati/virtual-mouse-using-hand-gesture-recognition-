# virtual-mouse-using-hand-gesture-recognition-
##Implementing a virtual mouse using gesture recognition .

##Required Modules :

##1. OpenCV
##  pip install opencv
2.mouse
  pip install mouse
3.numpy
  pip install numpy
4.math
  pip install math
5.WX
  pip install WxPython
ABSTRACT
We aim to enable a computer to comprehend and perform the mouse functions by analyzing a video with hand motions. For this purpose, dynamic gestures are captured by a web cam and are recognized as pre-defined gestures which are used to suggest mouse functions. The proposed algorithm initially detects the hand. Then, it tracks fingertips' trajectories within a frame sequence. Finally, hand gestures are recognized through computing a set of proposed geometric features of fingers' trajectories and comparing with our collected gestures dataset. In this paper, four types of descriptors are defined for a dynamic gesture. Each descriptor includes different number of features, which compose a feature vector with 135 dimensions. Different classification algorithms (e.g. KNN, LDA, Naïve Bayes and SVM) are applied to compare the detection results. The minimal misclassification error rate (MCR) reaches about 4% (i.e. Correct Recognition rate of 96%). Furthermore, we applied Principle Component Analysis (PCA) to reduce the number of features. With 30 dimensional features (principle components), LDA classifier can achieve about 0.09% misclassification error rate.
