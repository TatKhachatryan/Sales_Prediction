# Sales_Prediction

In this project I did prediction with 2 algorithms: XGBoost and SVR (Spector Vector Regression).

train.csv and test.csv files are uploaded above.

## Modules imported:

import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import plotly.express as px
from sklearn.preprocessing import LabelEncoder
from sklearn.ensemble import RandomForestRegressor
import xgboost as xgb
from sklearn.model_selection import GridSearchCV
from sklearn.svm import SVR
from sklearn import linear_model
