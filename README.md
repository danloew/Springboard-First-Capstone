# Springboard-First-Capstone
Full Code, Report, and Slide Deck for Daniel Loew's First Springboard Capstone Project

Title: "Targets: Using Machine Learning Classification Models to Identify Salient Predictors of Cannabis Arrests in New York City, 2006-2018"

This project uses publicly available data from the NYPD to build predictive machine learning classification models of cannabis crime and its subtypes, providing Logistic Regression coefficients which illuminate the features that have the strongest statistical relationship with these crimes. The Jupyter notebooks, data sources, technical requirements for reproducing the results, and reports for this project are specified below. The results of this project, including evaluation metrics of the machine learning models and Logistic Regression coefficients, are reported in the Overall Capstone Project Report linked to below. 

The 11 Jupyter notebooks that are needed to run the project are located at the following links:
  - Data Cleaning for Cannabis Crimes: https://github.com/danloew/SpringboardFirstCapstone/blob/master/Data_Cleaning_cann_Final.ipynb
  
    - The file name is 'Data_Cleaning_cann_Final.ipynb'.
    
    - This notebook uses the original open-source dataset of all crimes in New York City, which is available on the NYC Open 
     Data Project at https://data.cityofnewyork.us/Public-Safety/NYPD-Complaint-Data-Historic/qgea-i56i
     
    - It also uses a file of all NYC subway entrances, available at the following link: https://data.ny.gov/widgets/i9wp-a4ja
    
    - This notebook generates the 'nyc_cann_for_EDA.csv' and 'nyc_cann_EDA_race_reported.csv' files, which are used in the Data Story & EDA Jupyter notebook.
    
    - This notebook also generates the 'nyc_cann_HT_sample.csv' file, for use in the Statistical Data Analysis notebook.
    
    - This notebook also generates the 'nyc_cann_ml_alt.csv' file, for use in the second through seventh Machine Learning Jupyter notebooks.
     
    - This notebook also generates the 'nyc_cann_for_ML.csv' file, for use in the Data Cleaning for Non-Cannabis Crimes Jupyter notebook.
    
  - Data Cleaning for Non-Cannabis Crimes: https://github.com/danloew/SpringboardFirstCapstone/blob/master/DataCleaning_ncann_Final.ipynb
  
    - The file name is 'DataCleaning_ncann_Final.ipynb'.
    
    - This notebook uses the original open-source dataset of all crimes in New York City, which is available on the NYC Open 
     Data Project at https://data.cityofnewyork.us/Public-Safety/NYPD-Complaint-Data-Historic/qgea-i56i
     
    - It also uses a file of all NYC subway entrances, available at the following link: https://data.ny.gov/widgets/i9wp-a4ja 
    
    - This notebook generates the 'nyc_non_cann_HT_sample.csv' file, for use in the Statistical Data Analysis notebook.
    
    - This notebook also generates the 'nyc_non_cann_sample.csv' file for use in the Data Story & EDA notebook.
    
    - This notebook also generates the 'nyc_non_cann_for_ML.csv' file, and concatenates it with the 'nyc_cann_ml_alt.csv' file, which is then exported to the 'concat_cann_non_cann_for_ml.csv' file for use in the first Machine Learning Jupyter notebook.

  - Data Story & EDA: https://github.com/danloew/SpringboardFirstCapstone/blob/master/DataStory_EDA_Final.ipynb
   
    - The file name is 'DataStory_EDA_Final.ipynb'.
    
    - This notebook uses the 'nyc_cann_for_EDA.csv', 'nyc_cann_EDA_race_reported.csv', 'nyc_non_cann_sample.csv', and 'concat_cann_non_cann_for_ml' files.
    
  - Statistical Data Analysis: https://github.com/danloew/SpringboardFirstCapstone/blob/master/DataStory_HT_Final.ipynb
  
    - The file name is 'DataStory_HT_Final.ipynb'.
    
    - This notebook uses the 'nyc_cann_HT_sample.csv' and 'nyc_non_cann_HT_sample.csv' files.
    
- Machine Learning Classification Part I - Cannabis and Non-Cannabis Crimes: 
  - https://github.com/danloew/SpringboardFirstCapstone/blob/master/ML_cann_v_ncann_final.ipynb

  - The file name is 'ML_cann_v_ncann_final.ipynb'.
  
  - This notebook uses the 'concat_cann_non_cann_for_ml' file.
  
- Machine Learning Classification Part II through VII - Possession and Sales, Misdemeanor Possession, Violation Possession, Felony Possession, Misdemeanor Sales, and Felony Sales:
  - https://github.com/danloew/SpringboardFirstCapstone/blob/master/ML_poss_v_sales_final.ipynb
  - https://github.com/danloew/SpringboardFirstCapstone/blob/master/ML_misd_poss_final.ipynb
  - https://github.com/danloew/SpringboardFirstCapstone/blob/master/ML_viol_poss_final.ipynb
  - https://github.com/danloew/SpringboardFirstCapstone/blob/master/ML_felony_poss_final.ipynb
  - https://github.com/danloew/SpringboardFirstCapstone/blob/master/ML_misd_sales_final.ipynb
  - https://github.com/danloew/SpringboardFirstCapstone/blob/master/ML_felony_sales_final.ipynb
  
  - The file names are 'ML_poss_v_sales_final.ipynb', 'ML_misd_poss_final.ipynb', 'ML_viol_poss_final.ipynb', 'ML_felony_poss_final.ipynb', 'ML_misd_sales_final.ipynb', and 'ML_felony_sales_final.ipynb'.
  - These notebooks use the 'nyc_cann_for_ml.csv' file.
  
- The URL detailing the NYPD's police precincts, which is used throughout the project, is located here: https://www1.nyc.gov/site/nypd/bureaus/patrol/precincts-landing.page
- The URL detailing the NYC transit districts, which is used throughout the project, is located here: https://www1.nyc.gov/site/nypd/bureaus/transit-housing/transit.page 

- The file called "requirements.rtf" details all of the software requirements needed to run the Jupyter notebooks. This file is divided into a section for each of the 11 Jupyter notebooks.

Links to the Interim Reports, Final Report, and Slide Deck are below:
- Project Ideas Report: https://github.com/danloew/SpringboardFirstCapstone/blob/master/SB_Project1_Targets_Project_Ideas_Daniel_Loew.pdf

- Project Proposal Report: https://github.com/danloew/SpringboardFirstCapstone/blob/master/SB_Project1_Targets_Project_Proposal_Daniel_Loew.pdf

- Data Cleaning and Wrangling Report: https://github.com/danloew/SpringboardFirstCapstone/blob/master/SB_Project1_Targets_Data_Wrangling_Daniel_Loew.pdf

- Data Story and EDA Report: https://github.com/danloew/SpringboardFirstCapstone/blob/master/SB_Project1_Targets_Data_Story_Daniel_Loew.pdf

- Statistical Data Analysis Report: https://github.com/danloew/SpringboardFirstCapstone/blob/master/SB_Project1_Targets_Statistical_Data_Analysis_Daniel_Loew.pdf

- Milestone Report: https://github.com/danloew/SpringboardFirstCapstone/blob/master/SB_Project1_Targets_Milestone_Report_Daniel_Loew.pdf

- In-depth Analysis and Machine Learning: https://github.com/danloew/SpringboardFirstCapstone/blob/master/SB_Project1_Targets_Machine_Learning_Daniel_Loew.pdf

- Overall Capstone Project Report: https://github.com/danloew/SpringboardFirstCapstone/blob/master/SB_Project1_Targets_Overall_Report_Daniel_Loew.pdf

- Presentation Slide Deck: https://docs.google.com/presentation/d/1Tsno2V6mdiIv5j04ikVXX5ZFqq5gsULlFlDXnczozT4/edit?usp=sharing
