# Emotion_recognition
Model uses a pretrained model called face_model.h5 which is trained on fer13 dataset, it is a dataset with emotion shown in the facial expression into one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral). The training set consists of 28,709 examples and the public test set consists of 3,589 examples , and additionally haarcascade file along with open cv is used .
The actual model is based on cnn architecture with multilayer of convolution and pooling and with dense layer , features like Image data generator have been used to avoid overfitting.
you can check the similar model implementaion here.
https://www.geeksforgeeks.org/deep-learning/emotion-detection-using-convolutional-neural-networks-cnns/
