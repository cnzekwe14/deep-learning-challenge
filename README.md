# deep-learning-challenge

The purpose of the analysis is to determine which applicants should receive funding based on the chance of having a successful venture.  The model would assist in perdicting in how to allocate the fund to provide applicants with enhancing their venture successes.

The IS_SUCCESSFUL column was the target variable used for the model.  For the features there were two different types used.  For the first model which outputed 73% all columns were used except for EIN, NAME and IS_SUCCESSFUL.  The second model which outputed 96%, all columns were used for the feature except IS_SUCCESSFUL.  EIN and NAME are the variables that can be removed because they are neither targets or features.  


The first model was defined by:
- 100 neurons for two hidden layers and one neuron for the output layer
- relu activation was used for the two hidden layers and sigmoid was used for the output layer

The second model was defined by:
- 200 neurons for four hidden layers and one neuron for output layer
- sigmoid was used for all layers

The first model produced 73% accuracy.  In order to improve the accuracy more data needed to be added.  For the second model all data was added as well as more neurons and layers.  Changing the activation from relu to sigmoid produced an accuracy of 75% for the second model.

The results of the model showed that providing funding for applicants that can potentially have successful ventures would produce a 75% accuracy.  Increasing the number of data could help provide different results that could be more accurate.  The current data is not enough to increase the accuracy to 90%.  Its recommended that more data be used.



