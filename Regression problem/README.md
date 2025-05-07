#  Regression problem  
Approximate the function y = sin (2* π x1) x2 x3 x4 𝑒−(𝑥1+ 𝑥2+ 𝑥3+𝑥4 ). With a 4- 
50–1 network. Generate 1000 values in each input dimension in the interval [-1 … 1]. 
The network has sigmoid activation functions in the hidden layer and linear function 
in the output layer. Divide the data into training (70%), testing set (15%) and 
validation data (15%). Use the Mean Square Error objective/ loss function. Evaluate 
the performance of the designed network. 

## Solution steps:  
1- Generate the data (1000 values) 

2- Divide the above data into training data (70%), validation data (15%), and 
testing data (15%).  

3- Build keras network (input layer = 4 , dense layer (number of neuron = 50, 
activation function = sigmoid), dense output layer (number of neuron =1, 
activation function = linear). 

4- Compile the model with loss= mean square error, optimization = adam. 

5- Fit the model using number of epochs = 500. 

6- Draw a curve to represent the epochs on x axis and the loss on the validation 
sample on y-axis to determine the epoch number that has the better model.

7- Predicted the y values by using the test data.  

8- Compare the actual values with the predicted values and compute root mean 
square error. 
