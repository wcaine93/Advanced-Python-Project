## A. Import and process the csv data
Use the Panda library to load the csv data with the following: 

1. Load the csv data. 
2. Get a quick overview by printing the first 10 rows of the DataFrame, viewing the last 5 rows of the DataFrame, and showing all the rows.  
3. View the number of rows and columns in the data frame 
4. Get the dataframe information about the data set. 
5. Check the empty value. 
6. Replace Empty Values Using the value that appears most frequently. 
7. Check and Discovering Duplicates. 
8. Removing Duplicates.  

## B. Split the data into training and test data
Use the use the train_test_split helper function from Scikit-learn to split the training date and test data the following: 

1. Create the data features (X) and target labels (y).  
2. Randomly split the data features and labels into a training and test sets by holding 30% of the data for testing. 

## C. Build a baseline NN model
Use the TensorFlow and Keras library to build a neural network model with the following: 

1. Two hidden layer of 10 nodes, and the ReLU activation function 
2. Plot the model architecture 
3. Compile the model using the adam as the optimizer and using the mean squared error as the loss function. 
4. Train the model on the training data using 100 epochs. 
5. Evaluate the model on the test data using model.evaluate 
6. Make predictions on test data using model.predict 

## D. Normalize the data
Repeat Part C but use a normalized version of the data. 
Recall that one way to normalize the data is by subtracting the mean from the individual predictors and dividing by the standard deviation. 

## E. Increase the number of epochs
1. Repeat Part C but use 250 epochs this time for training.  
2. prevent the overfitting using tensorflow.keras.callbacks.EarlyStopping(), if  30 epochs with no improvement by monitoring the validation loss, the training will be stopped,  

## F. Increase the number of hidden layers (5 marks) 

Repeat part C but use a neural network with the following instead: 
1. Four hidden layers, each of 10 nodes and ReLU activation function. 
 
