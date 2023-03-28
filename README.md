# deep-learning-challenge

The purpose of the analysis is to determine which applicants should receive funding based on the chance of having a successful venture.  The model would assist in perdicting in how to allocate the fund to provide applicants with enhancing their venture successes.

The IS_SUCCESSFUL column was the target variable used for the models.  For the features there were two different types used.  For the AlphabetSoupCharity model all columns were used except for EIN, NAME and IS_SUCCESSFUL.  The AlphabetSoupCharity_Optimization model used all columns the feature except IS_SUCCESSFUL.  EIN and NAME are the variables that can be removed because they are neither targets or features.  


The AlphabetSoupCharity model was defined by:
- 100 neurons for two hidden layers and one neuron for the output layer
- relu activation was used for the two hidden layers and sigmoid was used for the output layer

The AlphabetSoupCharity_Optimization model was defined by:
- 200 neurons for four hidden layers and one neuron for output layer
- sigmoid was used for all layers

The AlphabetSoupCharity model produced 72% accuracy.  In order to improve the accuracy more data needed to be added.  For the AlphabetSoupCharity_Optimization model all data was added as well as more neurons and layers.  Changing the activation from relu to sigmoid produced an accuracy of 75% for the AlphabetSoupCharity_Optimization model.

The results of the models showed that providing funding for applicants that can potentially have successful ventures would produce a 75% accuracy.  Increasing the number of data could help provide different results that could be more accurate.  The current data is not enough to increase the accuracy to 90%.  Its recommended that more data be used.



