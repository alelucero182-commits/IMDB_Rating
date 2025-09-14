# IMDB_Rating
Análise exploratória de dados (EDA) e modelagem sobre a base de dados contendo informações quantitativas e qualitativas sobre filmes.

Este projeto foi feito na linguagem Python, versão 3.11, no ambiente Spyder, acessado pelo Anaconda Navigator.

import pandas as pd ### trabalhar com dataframe

from nltk.corpus import stopwords #### para retirar stopwords

from wordcloud import WordCloud, STOPWORDS, ImageColorGenerator ### gerar nuvem de palavras

import seaborn as sns # visualização gráfica

import matplotlib.pyplot as plt # visualização gráfica

import time # definição do intervalo de tempo entre gráficos com animação

import statsmodels.api as sm # estimação de modelos

import numpy as np ### realizar operações

from sklearn.metrics import mean_absolute_percentage_error # métricas de ajuste

from sklearn.metrics import mean_squared_error # métricas de ajuste
from sklearn.metrics import mean_absolute_error # métricas de ajuste
from sklearn.metrics import r2_score # métricas de ajuste


