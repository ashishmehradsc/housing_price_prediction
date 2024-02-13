[![Ashish-Mehra.png](https://i.postimg.cc/W1sWvwSM/Ashish-Mehra.png)](https://www.linkedin.com/in/ashishmehra/)

# 🎯 Objective: Predict the housing prices in the region
_Real estate company would like a real estate prediction mechanism. This valuation will  depends on multiple factors. i.e. location, type of building, macro-economy to name a few. Knowing the potential direction and strength of prices is very helpful for the construction companies and also real estate sales companies to align their investments and sales strategy._


## 📉  Data: 

The data available is describing different aspects of properties in the Bay area. Name of the fields and their respective explanation is given below - 

| Field | Exaplanation |
| ------ | ------ |
| **Longitude**  | A measure of how far west a house is; a higher value is farther west navigation | - 
| **Latitude**  | A measure of how far north a house is; a higher value is farther north |
| **housing_median_age**  |  Median age of a house within a block; a lower number is a newer building |
| **total_rooms**  | Total number of rooms in the block |
| **total_bedrooms**  | Total number of bedrooms in a block |
| **population**  | Total number of people residing in a block |
| **households**  | Total number of households, a group of people residing within a home unit, for a block |
| **median_income**  | Median income for households within a block of houses (measured in tens of thousands of US Dollars) |
| **median_house_value**  | Median house value for households within a block (in USD) |
| **ocean_proximity**  | House has a ocean in proximity or not |

## 🔎 Approach:
- Data preparation was done importing the given data.
- Feature completeness anad accuracy checks were performed. 
- Data preprocessing was done based on the checks performed:
        > Duplicates and missing data was treated.
        - Obvious unecessary columns were removed.
        - Outliers were removed.
- Exploratory data analysis confirmed no major red flags.
- Categorical columns were encoded using one hot encoding.
- Data was split into features and the label (aka target).
- Trained the linearregression algorithm on the dataset.

## 💻  Dependencies:

**IDE:**
- Jupyter Notebook (alternatively Google Colab can be used)

**Python Libraries:**
```python
import numpy as np
import pandas as pd

import matplotlib.pyplot as plt
import plotly.express as px
import seaborn as sns

from scipy.stats import pearsonr, spearmanr

from sklearn.preprocessing import StandardScaler
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
from sklearn.metrics import mean_absolute_error,r2_score,mean_squared_error
```

## 🔎 Results:

||  Metric  |  Score|
|----| ------ | ------ |
|Training | R^2 | 0.6122729171374928 |
|Test | R^2 | 0.6244442222072821 |



## 📃 License:

>Free Software, Hell Yeah!


----
## Connect on: 

[![linkedin.png](https://i.postimg.cc/YCV2vR0W/linkedin.png)](https://www.linkedin.com/in/ashishmehra/)

