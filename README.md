# STEM-courses-Salary

import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import scipy.stats as st
import random
import plotly.express as px
import plotly.graph_objects as go
import plotly.io as pio
from scipy.stats import skew, kurtosis
import statsmodels.formula.api as sm
plt.style.use('default')
pd.set_option('display.max_columns', None)
df = pd.read_csv("Levels_Fyi_Salary_Data.csv")
pio.templates.default = 'plotly_white'
dark_blue = '#0a275f'
honey_orange = '#EBA937'
cobalt_blue = '#1143a6'
