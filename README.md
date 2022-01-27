
# Prediction of NPS value for Santalucia
![Python](https://img.shields.io/badge/-Python-f7c437?style=flat-square&logo=python&logoColor=black)


This is a time-series implementation for the prediction of the NPS (Net-promoter-score) of Santalucía [Spanish Insurance Company]. In this implementation the prediction is done in two different ways. We first use a linear model after applying extensive preprocessing and data handling. In the second implementation we use traditional time-series algorithms, we try simple Moving Averages, ARIMA and Exponential Moving Averages. We execute this trials in both 1,3 and 14 months. We conclude that the exponential moving averages is the best algorithm for the prediction. 

This implementation is done entirely in python using a diverse list libraries ranging from common Numpy, Matplotlib, Sklearn to more niche libraries such as msgo. The pip installation is highlighted below.

## Table of contents
* [ Installation](#Installation)
* [ Execution](#Execution)
* [ Setup](#Setup)


### 1.0 Installation:
   1. Install Python x3.6
   2. Install libraries, libraries needed highlighted in requirements.txt
   3. Email to "alejandrosoumah@hotmail.com" in order to get the data


### 2.0 Execution
   1. Run Notebook from top to bottom executing all cells
   2. Be Aware that <b>profiling</b> takes a long time to execute due to the high number of 

## 3.0 Setup
   1. Run the notebook using your favorite notebook executer, such as Jupyter Notebook or 
   2. Change the path of the data as highlighted below
```
path_1 = <path to dataset x_1>

df_inicial_variables_numericas_imputacion_mediana_outliers_preprocesado = pd.read_csv(path_1)

path ="<path to dataset x_2>

df_label_encoding_variables_categoricas_cualitativas = pd.read_csv(path)

path =<path to dataset x_3>

df_label_encoding_variables_categoricas_cuantitativas = pd.read_csv(path)

path = <path to dataset Y>

y_inicial= pd.read_csv(path)
```

## Sources
OpenCV documentation https://docs.opencv.org/4.x/d6/d00/tutorial_py_root.html
Sklearn documentation https://scikit-learn.org/0.21/documentation.html
Missingno documentation hhttps://github.com/ResidentMario/missingno
Numpy documentation https://numpy.org/doc/
Matplotlib documentation https://matplotlib.org/stable/

