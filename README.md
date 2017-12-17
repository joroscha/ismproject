# ismproject
Capstone Project

This project contains 2 Python files:

•	Development Code: data cleaning and training, prediction and test of Random Forest and SVM models.

    o	Input: 
        	txt pipe delimited file. Each row of the input data constitutes information regarding a customer and his/her behavior.
        	User input to define the threshold for probability that will be applied to define when a customer is going to upgrade
        
    o	Output:
        	2 csv pipe delimited files with the resulting probabilities by customer for Random Forest and SVM, one for the test sample and one for the out of bag sample.



•	Production Code: data cleaning and probabilities' predictions with the selected Random Forest and SVM models.

    o	Input: 
        	txt pipe delimited file. Each row of the input data constitutes information regarding a customer and his/her behavior.
        	2 .sav files, one for the Random Forest model and other for SVM
        	User input to define the threshold for probability that will be applied to define when a customer is going to upgrade
        
    o	Output:
        	1 csv pipe delimited files with the resulting probabilities by customer for Random Forest and SVM.
