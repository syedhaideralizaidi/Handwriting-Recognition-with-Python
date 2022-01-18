# Handwriting-Recognition-with-Python
This project reads the data as input and predicts whatever is written in the file.

Libraries involved in project:

1. Tensorflow:
	It is basically a library used for machine learning. It will be used to train and test the model.
2. Numpy:
	This library is used to handle the data in arrays which can be multidimensional.
3. Matplotlib:
	This is a low level graph plotting library in python that serves as a visualization utility.
4.Os:
	The OS module in Python provides functions for creating and removing a directory (folder), fetching its contents, changing and identifying the current directory, etc.
5. OpenCV:
	This is a great tool for image processing and performing computer vision tasks.

Steps to create the project:

→ Mnist variable is used for the classification of the data which will be handwritten whether its 8,9 etc.
→ Afterwards we will train the data which is fed into the model.
→ Normalize the training and testing data between 0 to 1.
→ Now we will create the new model and add new layers in it as we can see in neural networks.     Flatten layer is the first layer and two dense layers are the inner layers of the model. Also the activation function will be applied to all the hidden and output layers(softmax).
→ After this the model will be compiled by using a specific function of it.
→ Model will be fit and model will be trained. Epoches will be 3 which is basically how many times the model will iterate over same data.
→ We can now see the accuracy and loss of the model.
→ Now we will scan and load our own handwritten digits using cv library functions.

