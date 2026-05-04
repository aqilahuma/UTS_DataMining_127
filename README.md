UTS Data Mining - Prediksi Kualitas Anggur

Nama: Mufida Aqila Humaidah
NIM: 2304020127

Deskripsi
Tugas ini bertujuan untuk membangun model klasifikasi untuk memprediksi kualitas anggur berdasarkan fitur kimiawi.
Tahapan:
1. Pembersihan Data
2. Exploratory Data Analysis (EDA)
3. Preprocessing
4. Perbandingan Model
5. Evaluasi Model
6. Optimasi Model
7. Prediksi Data Testing
8. Kesimpulan

# IMPORT LIBRARY
Impor library tersebut digunakan untuk proyek klasifikasi machine learning, meliputi pandas dan numpy untuk manipulasi data, matplotlib serta seaborn untuk visualisasi, berbagai modul dari scikit-learn untuk preprocessing data (split data, scaling, cross-validation, grid search), evaluasi model (akurasi, classification report, confusion matrix), dan tiga algoritma klasifikasi (Decision Tree, Random Forest, Logistic Regression), serta warnings yang diatur untuk mengabaikan pesan peringatan.
Kode:
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

from sklearn.model_selection import train_test_split, cross_val_score, GridSearchCV
from sklearn.preprocessing import StandardScaler
from sklearn.metrics import accuracy_score, classification_report, confusion_matrix

from sklearn.tree import DecisionTreeClassifier
from sklearn.ensemble import RandomForestClassifier
from sklearn.linear_model import LogisticRegression

import warnings
warnings.filterwarnings('ignore')

