# classifierandservicelibrary
This repository is for the 3rd component of MyClassifier: an Android plugin that takes a classification model produced by dataGatherer and
classifierapi and detects activies for which that model was trained. 

Specifically, the model is a set of trained parameters for logistic regression. These are stored in a text file by dataGatherer. This plugin
reads this text file (which can be placed wherever a developer chooses) and uses the parameters to make its predictions. 
