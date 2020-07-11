# Speech-Emotion-Recognition
This project aims to implement speech emotion recognition strategy proposed in Speech Emotion Recognition Using Deep Convolutional Neural Network and Discriminant Temporal Pyramid Matching

Preprocessing Data
Update path of dataset which you want to save from path.py

Downloading Berlin Database of Emotional Speech!

Berlin Dataset
$ python load_emodb.py
eNTERFACE Dataset
Downloading the eNTERFACE05 Dataset and update the dataset root
Starting preprocessing

$ python melSpec.py

Feature Extracting
Finetune AlexNet with Tensorflow

$ python finetune.py
Discriminant Temporal Pyramid Matching

$ python dtpm.py -s  
$ python dtpm.py -n
Classfier
Support Vector Machine

$ python svm.py
Refrences:
Refrence Model:

Alexnet
SVM
Refrence Papers:

ImageNet Classification with Deep Convolutional Neural Networks
Speech Emotion Recognition Using Deep Convolutional Neural Network and Discriminant Temporal Pyramid Matching
Geometric ℓp-norm feature pooling for image classification
