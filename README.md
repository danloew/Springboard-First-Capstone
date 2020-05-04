# Springboard-First-Capstone
Full Code, Report, and Slide Deck for Daniel Loew's First Springboard Capstone Project

Title: "Targets: Using Machine Learning Classification Models to Identify Salient Predictors of Cannabis Arrests in New York City, 2006-2018"

The 11 Jupyter notebooks that are needed to run the project are located at the following links:
  - Data Cleaning for Cannabis Crimes: https://github.com/danloew/Springboard-First-Capstone/blob/master/1st_Capstone_Data_Cleaning_cannabis_Daniel_Loew_Final.ipynb
  
    - The file name is '1st_Capstone_Data_Cleaning_cannabis_Daniel_Loew_Final.ipynb'.
    
    - This notebook uses the original open-source dataset of all crimes in New York City, which is available on the NYC Open 
     Data Project at https://data.cityofnewyork.us/Public-Safety/NYPD-Complaint-Data-Historic/qgea-i56i
     
    - It also uses a file of all NYC subway entrances, available at the following link: https://data.ny.gov/widgets/i9wp-a4ja
    
    - This notebook generates the 'nyc_cann_for_EDA.csv' and 'nyc_cann_EDA_race_reported.csv' files, which are used in the Data Story & EDA Jupyter notebook.
    
    - This notebook also generates the 'nyc_cann_HT_sample.csv' file, for use in the Statistical Data Analysis notebook.
    
    - This notebook also generates the 'nyc_cann_ml_alt.csv' file, for use in the second through seventh Machine Learning Jupyter notebooks.
     
    - This notebook also generates the 'nyc_cann_for_ML.csv' file, for use in the Data Cleaning for Non-Cannabis Crimes Jupyter notebook.
    
  - Data Cleaning for Non-Cannabis Crimes: https://github.com/danloew/Springboard-First-Capstone/blob/master/1stCapstone_Data_Cleaning_non-cannabis_Daniel_Loew_Final.ipynb
  
    - The file name is '1stCapstone_Data_Cleaning_non-cannabis_Daniel_Loew_Final.ipynb'.
    
    - This notebook uses the original open-source dataset of all crimes in New York City, which is available on the NYC Open 
     Data Project at https://data.cityofnewyork.us/Public-Safety/NYPD-Complaint-Data-Historic/qgea-i56i
     
    - It also uses a file of all NYC subway entrances, available at the following link: https://data.ny.gov/widgets/i9wp-a4ja 
    
    - This notebook generates the 'nyc_non_cann_HT_sample.csv' file, for use in the Statistical Data Analysis notebook.
    
    - This notebook also generates the 'nyc_non_cann_sample.csv' file for use in the Data Story & EDA notebook.
    
    - This notebook also generates the 'nyc_non_cann_for_ML.csv' file, and concatenates it with the 'nyc_cann_ml_alt.csv' file, which is then exported to the 'concat_cann_non_cann_for_ml.csv' fie for use in the first Machine Learning Jupyter notebook.

  - Data Story & EDA: https://github.com/danloew/Springboard-First-Capstone/blob/master/7.2%20First%20Capstone%20Data%20Story%20%26%20EDA%20Final.ipynb
   
    - The file name is '7.2 First Capstone Data Story & EDA Final.ipynb'.
    
    - This notebook uses the 'nyc_cann_for_EDA.csv', 'nyc_cann_EDA_race_reported.csv', 'nyc_non_cann_sample.csv', and 'concat_cann_non_cann_for_ml' files.
    
  - Statistical Data Analysis: https://github.com/danloew/Springboard-First-Capstone/blob/master/8.5_1st_Capstone_Statistical_Data_Analysis_Daniel_Loew_Final.ipynb
  
    - The file name is '8.5_1st_Capstone_Statistical_Data_Analysis_Daniel_Loew_Final.ipynb'.
    
    - This notebook uses the 'nyc_cann_HT_sample.csv' and 'nyc_non_cann_HT_sample.csv' files.
    
- Machine Learning Classification Part I - Cannabis and Non-Cannabis Crimes: 

  - The file name is '10.6_First_Capstone_Machine_Learning_part_I_cann_v_non_cann_final.ipynb'.
  
  - This notebook uses the 'concat_cann_non_cann_for_ml' file.
  
- Machine Learning Classification Part II through VII - Possession and Sales, Misdemeanor Possession, Violation Possession, Felony Possession, Misdemeanor Sales, and Felony Sales

  - The file names are '10.6_First_Capstone_ML_part_II_possession_v_sales.ipynb', '10.6_First_Capstone_ML_part_III_misdemeanor_possession_final.ipynb', '10.6_First_Capstone_ML_part_III_violation_possession_final.ipynb', '10.6_First_Capstone_ML_part_III_felony_possession_final.ipynb', '10.6_First_Capstone_ML_part_III_misdemeanor_sales_final.ipynb', and '10.6_First_Capstone_ML_part_III_felony_sales_final.ipynb'.
  
  
 

- The URL detailing the NYPD's police precincts, which is used throughout the project, is located here: https://www1.nyc.gov/site/nypd/bureaus/patrol/precincts-landing.page
- The URL detailing the NYC transit districts, which is used throughout the project, is located here: www1.nyc.gov/site/nypd/bureaus/transit-housing/transit.page
- The file called "requirements.rtf" details all of the software requirements needed to run the Jupyter notebooks. This file is divided into a section for each of the 11 Jupyter notebooks.
- Reports: names and links to them
- Slide Deck: name and link on Google Docs
- instruction on how to repeat your code
- very brief synopsis of results: reference to reports and section names, most likely. writing anything up here would be too much, I think
