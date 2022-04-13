# README #

This repository focuses on the detection of anomalous/fraud reviews from Amazon using supervising fraud detection techniques. The src directory contains the library with code used in these notebooks to create and clean text features found in the sub-directory 'processing' and the 'visualization' sub-directory contain the code to visualize the categorical correlation.    


### What is this repository for? ###

This repository was built to showcase how NLP can be leveraged for anomaly detection. There are two models in this repository: baseline and proposed. The baseline model contains basic feature engineering methods and then trains a model. The proposed solution takes additional steps in feature engineering to achieve a greater accuracy. Both models leverage the same pre-processing components that can be found in src. Through this repository, we hope you achieve the following:

* Learn how to detect fraud in customer reviews with a supervised classification model
* Leverage natural language processing (NLP) to extract insights from text features and learn how to handle the unstructured text to numerical embeddings


### How do I get set up? ###

* Clone the repository.
* cd anomaliesinamazonreviews
* Create a conda environment and install all dependencies: conda env create -f path/to/environment.yml
* conda activate fraud
 
Navigate to the Jupyter notebooks and run the baseline and proposed notebooks:
* jupyter notebook
* Click on notebooks
* Both baseline and proposed notebooks


### How do I navigate this respository? ###
data > external

* Contains the data from Kaggle in .csv format

data > processed

* Contains the pre-processing data outputs as well as the applied model on the data for both the baseline and proposed models. Everything is in .csv format.

notebooks

* Contains both the baseline and proposed notebookes with commentary on the process.

src

* This contains all source code needed for pre-processing and visualization. Both can be found in their correpsonding folders.

models

* This is where the model objects are saved.


### Who do I talk to? ###

* If you have any questions regarding this repository, please visit our website at https://www.phdata.io/ or send us an email at info@phdata.io 