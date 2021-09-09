# Package Requirements

Packages required for data manipulation and manipulation: 
- Numpy; Pandas; Matplotlib; Seaborn; Sklearn
- Codes:  
import numpy as np  
import pandas as pd  
import matplotlib.pyplot as plt  
import seaborn as sns  
import random  
from sklearn.model_selection import train_test_split  

Packages for Matrix Factorization Implementation: 
- Pyspark
- Codes:  
from pyspark.ml.tuning import CrossValidator, ParamGridBuilder, TrainValidationSplit  
from pyspark.ml.evaluation import RegressionEvaluator  
from pyspark.ml.recommendation import ALS  
from pyspark.sql.session import SparkSession  
from pyspark.context import SparkContext  
from sklearn.metrics import ndcg_score  
sc = SparkContext('local')  
spark = SparkSession(sc)  

Packages for Content-Based Recommender System: 
- Sklearn
- Codes:  
from sklearn.feature_extraction.text import TfidfVectorizer  
from sklearn.metrics.pairwise import linear_kernel  

Packages for Factorization Machine: 
- Sklearn; Pyfm; Collections
- Codes:  
from sklearn.preprocessing import OneHotEncoder, LabelBinarizer, normalize  
from pyfm import pylibfm  
from sklearn.metrics import mean_absolute_error, mean_squared_error  
from collections import defaultdict  
from sklearn.metrics import ndcg_score  
from sklearn.metrics import dcg_score  
