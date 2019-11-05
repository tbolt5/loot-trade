# loot-trade
import matplotlib.pyplot as plt
import numpy as np
import pandas as pd
 
import sys
sys.modules.pop('matplotlib')
from matplotlib import pyplot as plt
 
 
class Loot:
 pass
 
rare = Loot
common = Loot
 
rare= [1,2,3,4,5,5,5,6,6,6,7,7,7,8,9,10]
common= [1,1,1,2,2,2,3,3,3,4,5,6,7,8,9,10]
 
Mean_rare=np.mean(rare)
Mean_common=np.mean(common)
 
STDV_rare=np.std(rare)
STDV_common=np.std(common)
print(STDV_rare)
print(Mean_rare)
