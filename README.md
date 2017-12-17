# ismproject
Capstone Project

This project contains 2 Python files:

Development Code: data cleaning and training, prediction and test of Random Forest and SVM models.
    Input: 
          txt pipe delimited file. Each row of the input data consitutes information regarding a customer and his/her behavior.
          User input to define the threshold for probability that will be applied to define when a costumer is going to upgrade
    Output:
          2 csv pipe delimited files with the resulting probabilities by customer for Random Forest and SVM, one for the test sample and one for the out of bag sample.
   
Production Code: data cleaning and probabilities predictions with the selected Random Forest and SVM models.
    Input: 
          txt pipe delimited file. Each row of the input data consitutes information regarding a customer and his/her behavior.
          User input to define the threshold for probability that will be applied to define when a costumer is going to upgrade
    Output:
          1 csv pipe delimited files with the resulting probabilities by customer for Random Forest and SVM.
