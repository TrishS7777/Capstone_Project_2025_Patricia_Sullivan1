# Capstone_Project_2025

What is COPD? 
(cite: This description is borrowed from the COPD Patient dataset (copd_dataset1) in Kaggle)

Chronic obstructive pulmonary disease, commonly referred to as COPD, is a group of progressive lung diseases. The most common of these diseases are emphysema and chronic bronchitis. Many people with COPD have both of these conditions. Emphysema slowly destroys air sacs in your lungs, which interferes with outward airflow. Bronchitis causes inflammation and narrowing of the bronchial tubes, which allows mucus to build up.

It’s estimated that about 30 million people in the United States have COPD. As many as half are unaware that they have it. Untreated, COPD can lead to a faster progression of diseases, heart problems, and worsening respiratory infections.

The purpose of this Analysis is to analyze various factors that occur with and possibly affect COPD. We look at the severity of copd (stages 1, 2, 3, 4), Ages of those in each stage, do men or women tend to get copd more often, and other factors.  

GOLD Stages:
The Global Initiative for Chronic Obstructive Lung Disease (GOLD) system categorizes COPD severity into stages, with stage 4 representing very severe COPD (FEV1 less than 30%). 

There is no cure for COPD (Chronic Obstructive Pulmonary Disease), but certain treatments and Pulmonary Rehabilitation may improve the condition, the patient's quality of life and extend life expectancy. 

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

The virtual R/Pharma Conference is happening this week! To celebrate, we're exploring Patient Risk Profiles. Thank you to Jenna Reps for preparing this data!

This dataset contains 100 simulated patient's medical history features and the predicted 1-year risk of 14 outcomes based on each patient's medical history features. The predictions used real logistic regression models developed on a large real world healthcare dataset.

*There are over 100 column names with various conditions, smoking, etc...too many to list.  Here are the ones
 that were not dropped:

*personId = ID

*Sex = FEMALE integer	A binary column where 1 means the patient has a female sex

*Sex = MALE	integer	A binary column where 1 means the patient has a male sex

*Heart failure in prior year	integer	A binary column where 1 means the patient had a record for heart 
 failure in the prior year and 0 means they did not

*Chronic obstructive pulmonary disease (COPD) in prior year	integer	A binary column where 1 means the patient had 
 a record for chronic obstructive pulmonary disease in the prior year and 0 means they did not


----------------------------------------------------------------------------
FROM DATASET3 (respiratory_symptoms_and_treatment.csv) (from the Kaggle dataset)
About the dataset:
 
Context (paraphrased summary)
Respiratory isease causes an immense health burden. It is estimated that worldwide, more than 200 million people have chronic obstructive pulmonary disease (COPD), 65 million endure moderate-to-severe COPD, 1–6% of the adult population (more than 100 million people) experience sleep-disordered breathing, 9.6 million people develop tuberculosis (TB) annually, millions live with Pulmonary Hypertension and more than 50 million people struggle with occupational lung diseases,more than 1 billion people suffering from chronic respiratory conditions. At least 2 billion people are exposed to the toxic effects of biomass fuel consumption, 1 billion are exposed to outdoor air pollution and 1 billion are exposed to tobacco smoke. Each year, 4 million people die prematurely from chronic respiratory disease.To analyze pulmonary diseases we collected the data from the local health department of Albuquerque, NM, US. The Data containing different attributes to identify the disease and nature.

Content
This data was collected from public health department to identify different chronic respiratory diseases across the state of NM,US.
This data consists of different attributes like Name,age,sex,diseases,treatment and nature.Here Name,Sex,Diseases,Treatment and Nature are string values and some of them like Sex and nature are categorical values.This data contains 37000+ records till now and it has been updated regularly in quarterly basis.

Acknowledgements
We would like to thank public health department of New Mexico for their cooperation and considering our request.

List of Variables:
* Symptoms

* Age

* Sex

* Disease

* Treatment

* Nature


 ===========================================================================
 MY HYPOTHESES OF WHAT THE ANALYSIS WILL REVEAL:

 * My hypothesis is that the longer a person smoked, the more severe their case/stage of copd would be. 
 * I also think that we would see more people with copd in the higher ages because they have smoked (or been    
   exposed to polutants) longer or enough to develop COPD. 
 * It will be interesting to find out if more men or women have a higher incidence of COPD. I do not have a 
   hypothesis either way on this factor. 
 * I would think that co-morbidities would be high, because copd limits the ability for the body to get oxygen
   to parts of the body. It seems like that would be harder on the heart and immune system. For now I am just looking at ischemic Heart Disease, but as time permits, I plan to expand this study. 

=============================================================================
 Where the data took us.  What the analysis showed.

The analyses so far show that: 
 * Phase 2 COPD has the highest occurence, and there was only 1 occurence of VERY SEVERE COPD. The low incidence  
   of VERY SEVERE COPD could be attributed to the high death rate of those with SEVERE COPD. Further analysis is needed to confirm or disprove this theory. 

 * Males have a higher incidence of COPD than Females. 

 * Only 7 people out of 52 with COPD also have IHD, so there seems to be a very low correlation between those 
   specific conditions/diseases. 

 * A higher (longer) PackHistory does show a correlation with the number of incidences and severity of COPD. 

 * The most common ages for highest incidence of copd are 60 through 80. There is an increasing trend in the  
   number of incidences into the mid-70's, then starts decreasing again. There is a very low incidence past age 80. This is probably because only a few people with copd live that long. Further analysis is needed to compare 
   the life expectancy of a normal healthy person with a person with copd (unless we want to look at previous studies).

 * The plan is to continue looking at additional relationships between copd and other comorbidities and factors. 