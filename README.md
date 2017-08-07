This repository is my work on BNP Paribas Cardif claim management challenge on Kaggle

<h2>BNP Paribas Cardif Claims Management - Problem statement</h2>

In this challenge, BNP Paribas Cardif is providing an anonymized database with two categories of claims:

    claims for which approval could be accelerated leading to faster payments
    claims for which additional information is required before approval

The challenge is to predict the category of a claim based on features available early in the process, helping BNP Paribas Cardif accelerate its claims process and therefore provide a better service to its customers.

<h3>Steps to run the code</h3>

* Download data from https://www.kaggle.com/c/bnp-paribas-cardif-claims-management/data
* Run the ipython notebooks in the number sequence 00_* through 05_*
* Brief description of code files:
	
  <b>00_data_preprocessing_and_eda.ipynb</b>
	For data loading and pre processing the data and initial eda

	<b>01_data_transformation.ipynb</b>
	Necessary data transformations for model building

	<b>02_missing_value_analysis.ipynb
	Various approaches for handling missing values

	<b>03_xgboost_classifier.ipynb</b>
	Initial xgboost classifier model and performance analysis metrics

	<b>04_xgboost_param_importance.ipynb</b>
	Parameter importance analysis for xgboost model

	<b>05_extratree_PolyFet_Calib.ipynb</b>
	Extra tree classifier for with polynomial and caliberated features
