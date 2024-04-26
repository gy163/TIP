Identincaton of acive moleacules against thrombocytopenia through machine learning

A tool for acive moleacules prediction of thrombocytopenia. 

To use this tool, there are several steps：

#Step 1 Installation Anaconda Go to "https://docs.anaconda.com/free/anaconda/install/windows/" to download and install Anaconda

#Step 2 Use "Orange3 Installation.txt" to install orange3.

#Step 3 To run Orange Canvas run conda install orange3

#Step 4 Then input the Molecular descriptor data (.csv) from the file :"Molecular descriptor" folder into the running Orange.

Installation requirements: We are based on Python 3.10 and Orange3.


The contents of the uploaded file are as follows:

The data in the SMILES folder is based on the selection of 354 unique compounds after our strict data exclusion criteria. The training set includes 283 combinations
The test set contained 98 positive samples and 185 negative samples, while the test set included 71 compounds with 25 positive samples and 46 negative samples.

Under the Molecular descriptor folder is the molecular descriptor raw data (.csv), which is the training set and test set data from the four platforms of Mold2, mordred, PaDEL and Rdkit respectively, which can be divided into positive and negative samples.

Orange3-example-adon-master is the package required to install the active compound prediction tool for predicting thrombocytopenia.

The Orange3 Installation.txt file is the process and code required to install orange and its widgets.

The 379 optimal feature.xlsx is a set of 379 key features identified by four best-performing machine learning algorithms (SVM, RF, ANN, and XGBoost) by using the feature selection method.To seek more refined and efficient model performance.
