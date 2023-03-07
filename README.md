# deep_learning_challenge
Report on neural network:

Overview of the analysis:
    The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

Data Preprocessing:

What variable(s) are the target(s) for your model?
- IS_SUCCESSFUL is the target.

What variable(s) are the features for your model?
- all the other columns except IS_SUCCESSFUL is feature.

What variable(s) should be removed from the input data because they are neither targets nor features?
- Dropped Name and EIN column. 

Compiling, Training, and Evaluating the Model:

How many neurons, layers, and activation functions did you select for your neural network model, and why?
- neurons I selected were 80 as it should be double the amount of input dimension which is 35. Added four layers so that data is going to pass through and to increase accuracy.

Were you able to achieve the target model performance?
- It is almost near to the target which is 74.09

What steps did you take in your attempts to increase model performance?
- Changed the random state, number of layers, activation type, number of neurons.
