# Integration_of_Data_Mining_techniques_to_identify_factors_involved_in_Cancer_Therapeutics

Capstone project

Dataset(642 Patent files - Google_Patents_PDF_Files_2.zip) can be downloaded from : 
https://drive.google.com/drive/u/1/folders/157Wp-jzIHH8wdDouSp0PxBW6r3XpzdU4


Descriptions of Code files (in code folder):

1. code_module_1: This file contains the code to determine feature 'Cancer type' from text using Cancer types list file "cancer list.txt"

2. code_module_2: In this file, the 652 patents are filtered using Google Tesseract OCR library to obtain only those files which have useful information provided as graphs

3. Code_module_3: This file puts up graph details of all the filtered files, obtained through above code_module_2, in an excel sheet to be used later. 

4. Code_module_4_Final: This file performs text mining on the above filtered files to retrieve feature values for the features like:
'patent_id', 'cancer type', 'chemo agent/ oncolytic virus' and its quantity, 'cell survival %', 'tumor volume (in mm3)', 'days', 'species', 'experiment type', 'cell lines'
