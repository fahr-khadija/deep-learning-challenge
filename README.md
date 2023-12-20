# deep-learning-challenge

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

## Step 1: Preprocess the Data
## Step 2: Compile, Train, and Evaluate the Model
       Create a neural network model by assigning the number of input features and nodes for each layer using TensorFlow and Keras.
       Create the first hidden layer and choose an appropriate activation function.
       If necessary, add a second hidden layer with an appropriate activation function.
       Create an output layer with an appropriate activation function.
       Check the structure of the model.
       Compile and train the model.
       Create a callback that saves the model's weights every five epochs.
       Evaluate the model using the test data to determine the loss and accuracy.
       Save and export your results to an HDF5 file. Name the file AlphabetSoupCharity.h5.