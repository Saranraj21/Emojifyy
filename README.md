# Emojifyy
Create your own emoji with Deep Learning
Deep Learning project for beginners


Emojis or avatars are ways to indicate nonverbal cues. 
These cues have become an essential part of online chatting, product review, brand emotion, and many more. 
It also lead to increasing data science research dedicated to emoji-driven storytelling.

With advancements in computer vision and deep learning, it is now possible to detect human emotions from images. 
In this deep learning project, we will classify human facial expressions to filter and map corresponding emojis or avatars.


# About the dataset
The FER2013 dataset ( facial expression recognition) consists of 48*48 pixel grayscale face images. 
The images are centered and occupy an equal amount of space. This dataset consist of facial emotions of following categories:

0:angry

1:disgust

2:feat

3:happy

4:sad

5:surprise

6:natural


# Facial Emotion Recognition using CNN
In the below steps will build a convolution neural network architecture and train the model on FER2013 dataset for Emotion recognition from images.

Download the dataset from the above link. Extract it in the data folder with separate train and test directories.

# Summary
In this deep learning project for beginners, we have built a convolution neural network to recognize facial emotions. We have trained our model on the FER2013 dataset. Then we are mapping those emotions with the corresponding emojis or avatars.

Using OpenCV’s haar cascade xml we are getting the bounding box of the faces in the webcam. Then we feed these boxes to the trained model for classification.

DataFlair is committed to provide all the resources to make you a data scientist, which includes detailed tutorials, practicals, use-cases as well as projects with source code.

(Note It's existing project with little changes done by Saranraj)
