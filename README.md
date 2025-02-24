# Capstone_Project_2025
Analyze the severity of COPD by age and the effects of smoking and other health issues on the severity of COPD.  
Look at the 6 minute walk test.  Analyze how COPD rehabilitation improves the symptoms and severity of COPD by 
compairing the 6 minute walk test results and FEV1  scores before and after pulmonary rehabilitation. 
Finally, look at the typical progression of COPD, look at the mortality rates of COPD and what factors cause 
the increased progression of the severity of COPD. 

****Expand, improve and complete my readme file. 

# PROJECT LOCATION: 
# This PC > Windows (C:) > Users > trish > OneDrive > Desktop > Projects > Captstone_Project_2025

The COPD Dataset
https://www.kaggle.com/code/anapharm/the-copd-dataset

Input dataset: 
https://www.kaggle.com/code/anapharm/the-copd-dataset/input

START HERE: 
#Import my pandas library modules and submodule pyplot 

import pandas as pd 
import numpy as np 
import matplotlib
import matplotlib.pyplot as plt


import seaborn as sbn
import seaborn as sb
import plotyly.express as px
import sys
import warnings
warnings.filterwarnings('ignore')
import os
for dirname, _, filenames in os.walk('/kaggle/input'):
    for filename in filenames:
        print(os.path.join(dirname, filename))


# Additional possible datasets to use
Additional datasets I am currently exploring...

Hospital Mortality Quick Exploratory Data Analysis
https://www.kaggle.com/code/shariful07/hospital-mortality-quick-exploratory-data-analysis/log

COPD (Asthma) Patient Dataset
https://www.kaggle.com/datasets/jatinthakur706/copd-asthma-patient-dataset

Emmision of Air Pollutants
https://www.kaggle.com/datasets/elmoallistair/emmision-of-air-pollutants

respiratory symptoms and treatment
https://www.kaggle.com/datasets/abbotpatcher/respiratory-symptoms-and-treatment

Chronic Obstructive Pulmonary Disorder (COPD)
https://www.kaggle.com/datasets/mexwell/chronic-obstructive-pulmonary-disorder-copd

Indoor Air Pollution
https://www.kaggle.com/datasets/programmerrdai/indoor-air-pollution

Diseases and their Symptoms
https://www.kaggle.com/datasets/shobhit043/diseases-and-their-symptoms

Smoking Crisis
https://www.kaggle.com/datasets/willianoliveiragibin/smoking-crisis

Sleep Efficiency Dataset
https://www.kaggle.com/datasets/equilibriumm/sleep-efficiency

WHO Tobacco and Smoking Data 2008-2018
https://www.kaggle.com/datasets/ozgurdogan646/who-tobacco-and-smoking-data-20082018

U.S. Tobacco Use Data
https://www.kaggle.com/datasets/thedevastator/u-s-tobacco-use-data-1995-2010

Health Metrics Dataset
https://www.kaggle.com/datasets/abhayayare/health-metrics-dataset/data

Patient Risk Profiles
https://www.kaggle.com/datasets/sujaykapadnis/patient-risk-profiles

Taxes on Tobacco Over Time
https://www.kaggle.com/datasets/thedevastator/tax-burden-on-tobacco

Demographic Trends and Health Outcomes in the U.S
https://www.kaggle.com/datasets/thedevastator/demographic-trends-and-health-outcomes-in-the-u

Lung Condition Patients (COPD GOLD)
https://www.kaggle.com/datasets/sawdi777/copd-gold-230-patients

Demographic Trends and Health Outcomes
https://www.kaggle.com/datasets/thedevastator/demographic-trends-and-health-outcomes-in-the-u


# Thoughts on tools and methods
multiple plotz to answer questions 
or mutlitple statistical sets
Statistical analysis sets. 