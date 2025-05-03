# Classification problem  
Data set explanation: The iris dataset consists of 150 samples each having 4 attributes. 
The data represents 3 classes of flowers (each of 50 samples): Iris setosa (class 1) , Iris 
versicolor (class 2)and Iris virginica (class 3). For a better understanding of this dataset 
visit:  
https://en.wikipedia.org/wiki/Iris_flower_data_set  
Classify this data using a 4-10 -3 network. The network has sigmoid activation 
functions in the hidden layer and softmax functions in the output layer. Divide the data 
into training (50%), testing set (30%) and validation data (20%). Use the cross-entropy 
objective/ loss function. Evaluate the performance of your classifier (Confusion Matrix). 
## Solution steps:  
1- Read the data  
2- Divide the data into training data (50%), validation data (20%), and testing 
data (30%).  
3- Build keras network (input layer = 4 , dense layer (number of neuron = 10, 
activation function = sigmoid), dense output layer (number of neuron =3, 
activation function = softmax). 
4- Compile the model with loss= cross-entropy, optimization = adam  
5- Fit the model using number of epochs = 500.
6- Draw a curve to represent the epochs on x axis and the error on the validation 
sample on y-axis, to determine the epoch number that has the better model. 
7- Predicted the y values by using the test data.  
8- Compare the actual values with the predicted values and compute accuracy of 
the model through confusion matrix. 
