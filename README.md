# UAF_WORKSHOP
3 Days Workshop on Data Science in UAF
First DAY
Data Science with python
print('my first code')
'My first code'
1
2
3
12.4
13.6
2x+1
2+3-3

#import libararies
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt



#import dataset
df = sns.load_dataset('titanic')
df
df.head()
df.tail(10)
#dimention
df.shape
df.describe()
df.info()
df.isnull().sum()
df