# Gender_detection
I am creating a Face Detection and Gender Detection System using TensorFlow and OpenCV 
A model is crearted with 5 convolutional layers with dropout (not to overfit the data) and batch normalization to acceralate the process
along with 2 dense layer which give a output of 2 classes of either it is a male or female
I also include Maxpooling to extract important features
I trained the model over 1000 dataset of male and female photos with adam optimization and loss function of mean square error
Then we use opencv to detect faces on the webcam and apply the model on thant face to consider whether it's a male or female faces 
