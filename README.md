# Prediction of Protein Retention in the Endoplasmic Reticulum by Convolutional Neural Networks
A collection of scripts created throughout my 10 ECTS special course at DTU.

A CNN model, predicting whether a protein is retained in the ER lumen or secreted, is build, trained and tested. 
The input files consist of proteins extracted from the protein data bases UniProt and PROSITE. 

The repository contains scripts from jupyter notebook, in a numbered order. Input files are found in "/1.Parsing_Data_Files/1.1.Data_Files". 
All three input files are run in CD-HIT for homology partitioning, where the output is found in "/1.Parsing_Data_Files/1.3.CD_HIT_Files".

Additionally an analysis in the form of a t-test, of output from the prediction tool DeepLoc, is made. 
DeepLoc is executed with the input files and the output is found in "/3.DeepLoc_SHAP/Pos_Output_Attention" and "/3.DeepLoc_SHAP/Neg_Output_Attention" 