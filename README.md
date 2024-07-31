# neural-network-challenge-2
Challenge_19

Background
You are tasked with creating a neural network that HR can use to predict whether employees are likely to leave the company. Additionally, HR believes that some employees may be better suited to other departments, so you are also asked to predict the department that best fits each employee. These two columns should be predicted using a branched neural network.

Created a new repository for this project called neural-network-challenge-2.

Cloned the new repository to the computer.

added the starter file attrition.ipynb from your file downloads.

Pushed these changes to GitHub.


In Part 1: Preprocessing I have done the following steps: 
Import the data and view the first five rows.

Determine the number of unique values in each column.

Create y_df with the attrition and department columns.

Create a list of at least 10 column names to use as X data. You can choose any 10 columns you’d like EXCEPT the attrition and department columns.

Create X_df using your selected columns.

Show the data types for X_df.

Split the data into training and testing sets.

Convert your X data to numeric data types however you see fit. Add new code cells as necessary. Make sure to fit any encoders to the training data, and then transform both the training and testing data.

Create a StandardScaler, fit the scaler to the training data, and then transform both the training and testing data.

Create a OneHotEncoder for the department column, then fit the encoder to the training data and use it to transform both the training and testing data.

Create a OneHotEncoder for the attrition column, then fit the encoder to the training data and use it to transform both the training and testing data.

In Part 2: Create, Compile, and Train the Model I have done the following: 
Find the number of columns in the X training data.

Create the input layer. Do NOT use a sequential model, as there will be two branched output layers.

Create at least two shared layers.

Create a branch to predict the department target column. Use one hidden layer and one output layer.

Create a branch to predict the attrition target column. Use one hidden layer and one output layer.

Create the model.

Compile the model.

Summarize the model.

Train the model using the preprocessed data.

Evaluate the model with the testing data.

Print the accuracy for both department and attrition.

In Part 3: Summary I have done the following : 
Briefly answer the following questions in the space provided:

Is accuracy the best metric to use on this data? Why or why not?

What activation functions did you choose for your output layers, and why?

Can you name a few ways that this model could be improved?

YOUR ANSWERS HERE

1. Accuracy is not always the best metric to use on this data because it is squed for the highest events that take place.  
2. I have used sigmoid for the yes or no output; softmax was used to assign a probability for department assessment.  
3. improve and adjust neuron layers to find a better combination; experiment with some additional models or combinations thereof; clean and add the data to better fit the models. 
