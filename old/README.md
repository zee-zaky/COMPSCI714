# COMPSCI714


## main.py
This script loads in the Squad dataset and runs a baseline model that we can build off. The hyperparameters are set at the top of the script. We then train and save the model. This script takes a while to run and can be transferred to a notebook. To run the main.py you need to have the data in the same directory. Make sure the script can locate the data. 

## data_preprocessing.py

This script loads in the SQUAD2.0 Data. Need to set the number of records that you want to load in before running main.py. There is some preprocessing done, where we need to add the end index for the answer string. This is done using the 'start index' of the 'answer' part of the data. there are times where the start index is wrong, which we then have to modify it in the dataset. 
