# Contaminacion_Madrid

Data Cleaning &amp; Exploratory Data Analysis de la contaminacion por NO2 en Madrid en 2018. 
El jupyter notebook "contaminacion_madrid_2018.ipynb" contiene todo el data cleaning y analisis  para obtener los resultados mostrados debajo.
Tambien se implementó un modelo predictivos XGBoost (Decision trees), que tuvo en cuenta la serie temporal a la vez que la temperatura.

## 1. Analisis Descriptivo & exploracion gráfica:

Valores de NO2 del compunto de estaciones:

count    8759.000000

mean       36.553205

std        23.798604

min         2.916667

25%        18.958333

50%        30.208333

75%        48.750000

max       161.750000

![image](https://github.com/JuanFran9/Contaminacion_Madrid/assets/58949950/a93d5472-fbdc-43ed-a745-3163ad96ed79)

![image](https://github.com/JuanFran9/Contaminacion_Madrid/assets/58949950/39c84009-0f00-4d7d-ab5d-fd3a3dea9457)

![image](https://github.com/JuanFran9/Contaminacion_Madrid/assets/58949950/e4858aa9-40b6-43d6-b663-bc69cc4af543)

## 2. Correlaciones entre temperatura/estaciones y NO2:

![image](https://github.com/JuanFran9/Contaminacion_Madrid/assets/58949950/5ab93556-51fa-4def-951c-55a6bb02601a)

<img width="1066" alt="image" src="https://github.com/JuanFran9/Contaminacion_Madrid/assets/58949950/fa7744ac-3ae6-42f4-b6ad-c81d2996c006">

<img width="1102" alt="image" src="https://github.com/JuanFran9/Contaminacion_Madrid/assets/58949950/cc0adf37-d1d0-4e90-89e8-af0acaf53f59">

## 3. Modelos Predictivos 
### Analisis Autocorrecalcion para ARIMA
![image](https://github.com/JuanFran9/Contaminacion_Madrid/assets/58949950/2384ed76-3be4-4b7e-833b-88bc5f85f086)
### Predicciones con XGBoost 
![image](https://github.com/JuanFran9/Contaminacion_Madrid/assets/58949950/6fc52bc6-780b-4385-b822-0c028cf22b2e)
![image](https://github.com/JuanFran9/Contaminacion_Madrid/assets/58949950/4794b82c-7ef2-4df3-8f36-a6d23c4b8ec2)




