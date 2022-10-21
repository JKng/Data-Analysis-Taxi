MJK-Taxi - Análise de dados sobre o caso Taxi 

import json
import sqlite3
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib as mat
import matplotlib.pyplot as plt
import colorsys
plt.style.use('seaborn-talk')
import warnings
warnings.filterwarnings("ignore")
%matplotlib inline
import datetime

df = pd.read_json('atento0.json', orient='records', nrows=4000000, lines=True)
df 

<img src = "C:/Users/Ju/Downloads/q3atento.jpg">
