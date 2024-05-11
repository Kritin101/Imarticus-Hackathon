# Imarticus-Hackathon
Files Recived in te competitions were:-
 1. algoparams_from_ui1.json (Instruction For the Ml and AI Models along with other necessary items)
 2. iris_modified.csv (Data File)

Made a code file that automatically parses the json:-
 1. It fetches the Features that are going to be used which are marked as "Is_selected".
 2. It fetches the constraints on handling missing values for each cases (Mean, Median, Mode Impute and Tokenize and hash).
 3. Splits the X and y target varible as given in the json file.
 4. Splits the data with the random_state and test size ratio as given in the file.
 5. It fetches the Algorithms to be built which are marked as "Is_selected".
 6. It fetches the Hyperparameters of GridSearchCV given for each model.
 7. Finally build and runs the GridSearchCV, printing the best hyperparameters along with the test and best score achieved.

*W.I.P File
