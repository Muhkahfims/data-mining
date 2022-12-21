# Predicting of Iris Flower
# Abstrak
Kumpulan data bunga Iris adalah kumpulan data multivariat yang diperkenalkan oleh ahli statistik dan ahli biologi Inggris Ronald Fisher dalam makalahnya tahun 1936 Penggunaan beberapa pengukuran dalam masalah taksonomi. Kadang-kadang disebut kumpulan data Iris Anderson karena Edgar Anderson mengumpulkan data untuk mengukur variasi morfologi bunga Iris dari tiga spesies terkait. Kumpulan data terdiri dari 50 sampel dari masing-masing tiga spesies Iris (Iris Setosa, Iris virginica, dan Iris versicolor). Empat fitur diukur dari masing-masing sampel: panjang dan lebar sepal dan petal, dalam sentimeter. Kumpulan data ini menjadi kasus uji tipikal untuk banyak teknik klasifikasi statistik dalam pembelajaran mesin seperti mesin vektor pendukung

#code python
#app.py

  from flask import Flask, render_template, request
  import pickle
  import numpy as np

#read data
  df = pd.read_csv('iris.data')

