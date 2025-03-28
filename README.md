# Capstone_Project_2025

What is COPD? 
(cite: This description is borrowed from the COPD Patient dataset (copd_dataset1) in Kaggle)

Chronic obstructive pulmonary disease, commonly referred to as COPD, is a group of progressive lung diseases. The most common of these diseases are emphysema and chronic bronchitis. Many people with COPD have both of these conditions. Emphysema slowly destroys air sacs in your lungs, which interferes with outward airflow. Bronchitis causes inflammation and narrowing of the bronchial tubes, which allows mucus to build up.

It’s estimated that about 30 million people in the United States have COPD. As many as half are unaware that they have it. Untreated, COPD can lead to a faster progression of diseases, heart problems, and worsening respiratory infections.

The purpose of this Analysis is to analyze various factors that occur with and possibly affect COPD. We look at the severity of copd (stages 1, 2, 3, 4), Ages of those in each stage, do men or women tend to get copd more often, and other factors.  

============================================================================

Note: In the future as time allows, I plan to analyze this data further to find out how Pulmonary  rehabilitation improves the symptoms and severity of COPD by looking at the 6 minute walk test results, FEV1 scores, and other information, before and after pulmonary rehabilitation. This will require merging an additional dataset with the pulmonary rehabilitation information.
Finally, will look at the typical progression of COPD over time, with and without Pulmonary Rehabilitation, and what other factors may cause the progression to speed up or worsen. 

============================================================================

This project was completed and tested on a Chrome webbrowser.

# PROJECT LOCATION: 
My project can be found on GitHub. 
My profile name is TrishS7777
My project address is: https://github.com/TrishS7777/Capstone_Project_2025_Patricia_Sullivan1.git


The 3 Datasets I used and merged were from Kaggle:

1) The COPD Dataset
   * read in as copd_dataset1 = pd.read_csv('dataset.csv')
   * webaddress: https://www.kaggle.com/code/anapharm/the-copd-dataset

2) Patient Risk Profiles
   * read in as copd_dataset2 = pd.read_csv('patient_risk_profiles.csv')
   * webaddress: https://www.kaggle.com/datasets/sujaykapadnis/patient-risk-profiles

3) Respiratory Symptoms and Treatment 
   * read in as copd_dataset3 = pd.read_csv('respiratory symptoms and treatment.csv')
   * webaddress: https://www.kaggle.com/datasets/abbotpatcher/respiratory-symptoms-and-treatment?select=respiratory+symptoms+and+treatment.csv

Additional detail:

The 5 datasets in the project are:
*copd_dataset1
*copd_dataset2
*merged_copd_dataset1
*copd_dataset3
*merged_copd_dataset2


*The first 2 datasets, 'copd_dataset 1' and 'copd_dataset2', were read in and cleaned, then merged 
 into...'merged_copd_dataset1' and cleaned.
*Next 'copd_dataset3' was read in and cleaned.
*Finally, 'merged_copd_dataset1' was merged with 'copd_dataset3' to form the final  
 'merged_copd_dataset2'. 
*This final dataset was then cleaned and analyzed.  


============================================================================

Some information about the data from each dataset
-------------------------------------------------

FROM DATASET1 (dataset.csv)
About the data:
The dataset is a cohort of patients, who had been invited to take part in a rehabilitation program to help manage their COPD.

Content
It includes 101 patients and 24 variables. There's information on their characteristics, disease severity, and co-morbidities. It's also got measures of their walking ability, quality of life, and anxiety and depression. Following are the list of variables and the categories they belong to.

*Serial Number
 Index

*ID
 Unique ID

*AGE
 Age of the user

*PackHistory
 person’s pack years smoking, where pack years is defined as twenty cigarettes smoked every day for one year

*COPDSEVERITY
 Severity of the disease.  There are 4 stages of COPD, with 1 being the mildest and stage 4 being most severe and having a low expectation of survival past 5 years. 

---------------------------------------------------------------------------------------------------
FROM DATASET2 (patient_risk_profiles.csv)
About the data:




----------------------------------------------------------------------------
FROM DATASET3 (respiratory_symptoms_and_treatment.csv)
About the data:
 


 ===========================================================================



 My hypotheses and what I would expect to find:






 Where the data took us.  What the analysis showed.