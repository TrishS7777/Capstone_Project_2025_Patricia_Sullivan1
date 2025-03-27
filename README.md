# Capstone_Project_2025
Analyze the severity of COPD by age and the effects of smoking and other health issues on the severity of COPD.  
Look at the 6 minute walk test.  Analyze how COPD rehabilitation improves the symptoms and severity of COPD by 
compairing the 6 minute walk test results and FEV1  scores before and after pulmonary rehabilitation. 
Finally, look at the typical progression of COPD, look at the mortality rates of COPD and what factors cause 
the increased progression of the severity of COPD. 

I used Chrome webbrowser (and tested on firefox). 

# PROJECT LOCATION: 
My project can be found on GitHub. My profile name is TrishS7777
https://github.com/TrishS7777/Capstone_Project_2025_Patricia_Sullivan1.git


The 3 Main Datasets I used from Kaggle are:

1) The COPD Dataset
   * read in as copd_dataset1 = pd.read_csv('dataset.csv')
   * webaddress: https://www.kaggle.com/code/anapharm/the-copd-dataset



START HERE: 


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




# Thoughts on tools and methods
multiple plotz to answer questions 
or mutlitple statistical sets
Statistical analysis sets. 