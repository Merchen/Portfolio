# Test

import pandas as pd
import numpy as np
from sklearn import linear_model

df = pd.read_csv('data download.txt')
df

df1 = df.rename(columns = {"test_score(out of 10)" : "test_score","interview_score(out of 10)" : "interview_score"})
df1
