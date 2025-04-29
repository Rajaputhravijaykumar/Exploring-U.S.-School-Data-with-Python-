import
impr±
impr±
pandas as pd
ru—y as np
seaborn as sns
matplotlib.pyplot as pl t
from scipy. stats zscore
# Load the dataset using knm•.m working encoding
file_path
= "C: csv"
df = encoding:' latinl')
# 1. Info about dataset
Dataset Info
print (df. info( ) )
print( Surnary Statistics
print (df. )
print(df. isnull() . sum())
# 2. Handling Missing Data
df df. dropna()
print( After Handling Missing Values
print (df. isnull() . sum())
PairpLot to view relationships
pairplot(df, hue: )
of Academic Performance", y—I. Q)
pit. show()
Correlation Heatmap
pit. 6))
heatmap(df annot:True, cmap= ' coolwarm' )
Heatmap")
pit. show()
sns.
sns.
