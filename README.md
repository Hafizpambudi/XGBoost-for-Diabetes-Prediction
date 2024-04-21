# XGBoost-for-Diabetes-Prediction

## DATASET 
### Sumber Dataset : 
link : https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset
### Melakukan oversampling untuk menangani imbalanced data 
dilakukan oversampling untuk menyamakan jumlah data pada label dataset sehingga nantinya tidak model machine learning tidak menghasilkan bias. kami menggunakan package SmoteNC untuk oversampling dikarenakan tipe data pada dataset yaitu numerik dan kategorial. 

## Pembuatan Model 
### Preprocessing 
didalamnya terdapat imputer untuk menangani data yang bernilai null dan one hot encoder untuk encoding pada data kategorikal 
## XGboost Classifier
model algoritma machine learning xgboost digunakan dikarenakan model ini memiliki waktu eksekusi yang cepat serta memiliki akurasi yang tinggi. 

## Tuning 
## GridsearchCv
memakai gridsearch cv untuk melakukan tuning pada model machine learning yang telah dibuat. hal ini untuk mencegah adanya overfitting maupun underfitting serta menaikan akurasi dari model 
