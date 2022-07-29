# Hamoye-Internship-Stage-A


import pandas as pd
import statistics

df = pd.read_csv('C://Users//D-IKE//Desktop//HamoyeCODES//FoodBalanceSheets_E_Africa_NOFLAG.csv')
df.head()
df.groupby(['items']).sum()
print(df)

#Mean  for year 2015
#statistics.mean(dat.Y2015)
print("Mean  for year 2015 is " %(statistics.mean(df.Y2015)))

#Median  for year 2015
print("Standard deviation for year 2015 is " %(statistics.stdev(dat.Y2015)))

#missing data in year 2016
Y2016.isnull().sum()

#Highest sum of import quantity
df.groupby(['Elements']).sum()
print(df)

#selecting Y2018
df.iloc[11]

#checking for duplicates
df.duplicated().any()
