MJK-Taxi - Análise de dados sobre o caso Taxi 

###### import json
###### import sqlite3
###### import numpy as np
###### import seaborn as sns
###### import matplotlib as mat
###### import matplotlib.pyplot as plt
###### import colorsys
###### plt.style.use('seaborn-talk')
###### import warnings
###### warnings.filterwarnings("ignore")
###### %matplotlib inline
###### import datetime

df = pd.read_json('atento0.json', orient='records', nrows=4000000, lines=True)
df 

## Questão 1. RESULTADO

#### A distância média percorrida por viagens com no máximo 2 passageiros é:

## Questão 3. RESULTADO

<img src = "q3atento.jpg">

## Questão 5. RESULTADO
<img src = "ModelagemLogica.jpg">

