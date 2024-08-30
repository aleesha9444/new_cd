import pandas as pd
import numpy as np

url = "https://www.emsa.gen.tr/fr/produits/electrogenes-a-moteur-diesel"
df = pd.read_csv(url)

pip install openpyxl==3.0.9
df_elc = pd.read_csv('https://www.emsa.gen.tr/fr/produits/electrogenes-a-moteur-diesel')
print('read data into data frame')

df_elc.head(5)
