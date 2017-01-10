# asl-fingerspelling
"ASL Fingerspelling Interpretation"

In this project, a real time ASL Fingerspelling translator is developed using image processing and supervised machine learning. More particularly, in the finished system an Android smartphone is used to capture an image of a hand
gesture, which is the interpreted on an online server. The final system is able to classify 24 different symbols with reasonable accuracy.

The main.m file contains the code to train the KNN model for four feature extraction methods, namely HOCD, HOCD+Gabor, Gabor and SURF using Bag of Words

Only one of the feature extraction techniques can be run at a time.

The main.m file also provides a template in the end to test the trained model on 10 actual images of hands that are captured by us. These images are present in ‘test_images.mat’ and are called by the template before it is run. 

The error metric that is displayed at the end, gives the test error of the classifier that is used.


