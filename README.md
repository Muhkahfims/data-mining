# Predicting of Iris Flower
# Abstract
The Iris flower data set is a multivariate data set introduced by the British statistician and biologist Ronald Fisher in his 1936 paper The use of multiple measurements in taxonomic problems. It is sometimes called Anderson's Iris data set because Edgar Anderson collected the data to quantify the morphologic variation of Iris flowers of three related species. The data set consists of 50 samples from each of three species of Iris (Iris Setosa, Iris virginica, and Iris versicolor). Four features were measured from each sample: the length and the width of the sepals and petals, in centimeters.
This dataset became a typical test case for many statistical classification techniques in machine learning such as support vector machines

#code python
#app.py
from flask import Flask, render_template, request
import pickle
import numpy as np

#read data
df = pd.read_csv('iris.data')

