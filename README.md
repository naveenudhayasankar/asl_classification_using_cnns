# asl_classification_using_cnns
A comparative study of Convolutional Neural Network Models for classifying ASL words.

The dataset consists of spectogram images of 10 ASL gestures performed by 5 subjects. Different convolutional neural network models are used to classify unseen gestures. 

The first model suffers from overfitting and the second and third models address this issue by employing L1 and L2 regularization. 

The third model uses a pretrained Resnet50 model, fine tune it to fit our dataset and predict unseen gestures. 
