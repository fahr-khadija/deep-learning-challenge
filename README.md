# deep-learning-challenge
## ![Energy](https://tharawat.org/wp-content/uploads/2022/12/Website-header-e1670259531766-2048x901.png)

From Alphabet Soup’s business team, I have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as:

   #### EIN and NAME—Identification columns
   #### APPLICATION_TYPE—Alphabet Soup application type
   #### AFFILIATION—Affiliated sector of industry
   #### CLASSIFICATION—Government organization classification
   #### USE_CASE—Use case for funding
   #### ORGANIZATION—Organization type
   #### STATUS—Active status
   #### INCOME_AMT—Income classification
   #### SPECIAL_CONSIDERATIONS—Special considerations for application
   #### ASK_AMT—Funding amount requested
   #### IS_SUCCESSFUL—Was the money used effectively

With all knowledge of machine learning and neural networks, we’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

## Step 1: 
Preprocess the Data
## Step 2: 
Compile, Train, and Evaluate the Model
  ##### Create a neural network model by assigning the number of input features and nodes    for each layer using TensorFlow and Keras.
              * Create the first hidden layer and choose an appropriate activation function.
              * If necessary, add a second hidden layer with an appropriate activation function.
              * Create an output layer with an appropriate activation function.
              * Check the structure of the model.
              * Compile and train the model.
              * Create a callback that saves the model's weights every five epochs.
## Step 3 :
Evaluate the model using the test data to determine the loss and accuracy.

## Step 4: 
Save and export your results to an HDF5 file.Name the file AlphabetSoupCharity.h5

##  Optimize the Model
Using your knowledge of TensorFlow, optimize your model to achieve a target  predictive  accuracy higher than 75%.
optimize our model:
   ##### Adjust the input data to ensure that no variables or outliers are causing confusion in the model, such as:
             * Dropping more or fewer columns.
             * Creating more bins for rare occurrences in columns.
             * Increasing or decreasing the number of values for each bin.
             * Add more neurons to a hidden layer.
             * Add more hidden layers.
             * Use different activation functions for the hidden layers.
             * Add or reduce the number of epochs to the training regimen.
### Optimisation parameters for each trials : 
Code of the optimisation parameters
 ### ![Opt-para](https://github.com/fahr-khadija/deep-learning-challenge/blob/main/AlphabetSoupCharity_Optimization/AlphabetSoupCharity_Optimization_parameter/AlphabetSoupCharity_Optimization_parameter.ipynb)

### optimisation Data processing Options
Code of the optimisation data processing 
### ![opt-data]https://github.com/fahr-khadija/deep-learning-challenge/blob/main/AlphabetSoupCharity_Optimization/AlphabetSoupCharity_Optimization_parameter/AlphabetSoupCharity_Optimization_data.ipynb
   
# Analysis Report
Analysis-Report _Neural_Network_Model.pdf
### ![Report](https://github.com/fahr-khadija/deep-learning-challenge/blob/main/Analysis-Report%20_Neural_Network_Model.pdf)