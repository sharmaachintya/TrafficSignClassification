# TrafficSignClassification
With the help of basic deep learning model, Implemented Traffic sign recognition in real time


NOTE: DATASET WHICH I USED IS GERMAN TRAFFIC SIGN RECOGNITION BENCHMARK, CAN'T UPLOAD IT AS IT IS MORE THAN 100 MB BUT YOU CAN FIND IT ON KAGGLE ALSO HERE'S THE LINK TO THE DATASET : https://www.kaggle.com/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign

TRAINING CODE: In the training I have first imported all the necessary libraries then after that I have defined all the 43 classes as given in the GTSRB dataset, after that I've uploaded all the training dataset with their labels and stored them in a list called data and labels and after that converted both the lists in respective numpy arrays. For the validation dataset, I've used train test split function and taken 20 % of the dataset as validation dataset then I've converted the labels into One hot encoding. In the end I've created an empty neural network with the help of sequential and added convolutional layers and max pooling layers, Flatter layer, Dense layer and the fully connected layer for the training of the model and saved the model in h5 format.



