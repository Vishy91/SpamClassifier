# SpamClassifier
Classify emails as Spam or not spam using decision tree and naive bayes 
This is a group project and was part of the course Elements of AI

* Program should accept command line arguments like this:
./spam mode technique dataset-directory model-file

where mode is either test or train, technique is either bayes or dt, dataset-directory is a directory containing
two subdirectories named spam and notspam, each filled with documents of the corresponding type, and
model is the name of your trained model. In training mode, dataset-directory will be the training
dataset and the program should write the trained model to model, and in testing mode dataset-directory
will be the testing dataset and your program should read its trained model from model.
