# CS229ToShare

Specs: 

Written with Python 2.7, but should still work with the cs229 env with the right installations (keras, theano, sci-kit learn)

Other instructions:

Please note that the data folder has to be in a directory folder just before where the code itself actually resides.

For all the deep learning codes, the codes should run as is.

For the LR code, the age demographic is automatically omitted. To include it, please include an additional element in the vector in line 132. It should be from the vector "demographics" with the file name as the first index and "1" as the second index.

For the SVM code, you can change the type of kernels by changing at line 279.

Final info so that you don't get alarmed:

For F1 scores, you may see "nans". This is because the model aggressively guesses all 0's, so you end up with division by zero when calculating precision :') 
