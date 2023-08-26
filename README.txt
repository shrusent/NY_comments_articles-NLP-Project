To run the code, install the following dependencies and libraries on python:

import pandas as pd
import numpy as np
from zipfile import ZipFile
from io import BytesIO
import urllib.request as urllib2
import matplotlib.pyplot as plt
from matplotlib.pyplot import figure
import seaborn as sns
from sklearn.preprocessing import LabelEncoder
from collections import defaultdict
from sklearn.preprocessing import StandardScaler
import time
from sklearn.cluster import KMeans
import random
import math
from collections import defaultdict
import statsmodels.api as sm
import re
import nltk
import string
from wordcloud import WordCloud
from nltk.corpus import stopwords
nltk.download('stopwords')
nltk.download('wordnet')
nltk.download('omw-1.4')
nltk.download('punkt')

For running NYT-comments dataset, the csv should be in the same folder as the python environment. Pip install required for libraries not included in the environment. 

