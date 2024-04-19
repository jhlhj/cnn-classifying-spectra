# cnn-classifying-spectra
This is a CNN model based on pytorch which can classify 5 types infrared spectra.
Each spectrum data has been broadened to 4000 dimensions. 
The data file contains 450 spectra data (because all 5000 spectra is unpublished, these are part of the data) which can be equally divided into 5 types. 
CrossEntropyLoss function is used as loss function. Adam is used as optimizer. 
This code is an initial model, the part achieving split data as training data, test data and valid data will be added later.
