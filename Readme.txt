------------------------------------------------------------------------------------------------
Software Defect Severity prediction and Its Analysis via Self-Training Semi-Supervised Learning 
------------------------------------------------------------------------------------------------

   CONTENTS OF THE FILE
   --------------------

	* Introduction
	* Datasets
	* Files
	* Requirements
	* Procedure


   INTRODUCTION
   ------------
   In this file we will discuss about datasets,files and execution procedure of the Project Software Defect Severity Prediction.

   
   Datasets
   --------
   In this project we will be using 4 projects Eclipse,Equinox,Mylyn and Pde as datasets for our evaluation purpose.
   In each of the projects we have combined bug-metrics,change-metrics and single-version-ck-oo files into a single file. 
   The final preprocessed dataset links are provided here:
	https://github.com/DefectSeverityPrediction/ESEC-FSE

   Requirements
   ------------
   We can run this program in Google Colaboratory.
   Library used are 
   1)sklearn
   2)imblearn
   3)numpy
   4)pandas

   Files
   -----
   Defect_Severity_Classifier.ipynb (https://github.com/DefectSeverityPrediction/ESEC-FSE/blob/main/Defect_Severity_Classifier.ipynb)
	- This file contains logistic regression and decision tree classifiers for predicting the defect severity of software modules 
	  and also calculates the performance measures of the model  
   Self_training_Classifier.ipynb (https://github.com/DefectSeverityPrediction/ESEC-FSE/blob/main/Self_training_Classifier.ipynb)
 	- This file contains Self-training semi-supervised learning technique with decision tree as base classifier to predict defect severity
  	  and analyses performance of the model. 
   
   Execution Procedure
   -------------------
   Run the code consecutively given in the programme.
