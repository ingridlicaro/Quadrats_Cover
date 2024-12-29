# Quadrats_Cover
Statistical analysis of vegetation cover in intertidal zones.
This code contains the base information tabulated in excel format which was collected during field trips.

#Packages
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt

#Open File
file_path = 'C:/Quadrats Cover_Intertidal.xlsx'  
data = pd.read_excel(file_path)
sns.set(style="whitegrid")
print(data.head())
