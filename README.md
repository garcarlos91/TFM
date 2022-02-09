# Proyecto Fin de Máster 
## *Predicción del consumo eléctrico mediante Machine Learning*



## 1. Objetivos

El objetivo de este TFM es averiguar cuáles son los **factores** de los que dependen el **consumo eléctrico** para poder predecir el consumo anual per cápita en KWh, aplicando distintas técnicas de Machine Learning.

El primer paso, será **obtener información** de cómo funciona el mercado eléctrico español y como se gestiona la demanda y la producción de energía. Con esta información seremos capaces de saber qué factores afectan, en mayor o menos medida, al consumo eléctrico.

Una vez identificados, tendremos que **obtener datos de calidad** para nutrir el modelo. Para ello, hará falta distintos **procesos de recolección y tratamientos de datos**, un **análisis y estudio estadístico** para terminar con las técnicas de **Machine Learning**.

Utilizaremos distintos **modelos** y compararemos los resultados obtenidos para seleccionar el que mejor se adapte a nuestras **necesidades**. Una vez decidido el modelo, lo **optimizaremos** para que nos proporcione la mejor predicción posible y guardaremos esos resultados.
Para terminar, expondremos los resultados obtenidos en un informe, comparándolos con los **datos reales**.


![2018](https://user-images.githubusercontent.com/82395947/153067978-c30cc035-2bd4-4f4a-a553-4d6b02596ad3.PNG)


## 2. Fuentes de datos


   2.1 *Climatología*
   
   2.2 *Población*
   
   2.3 *PIB per cápita*
   
   2.4 *Número de viviendas*
   
   2.5 *Consumo de energía eléctrica per cápita*
   
   2.6 *Precio del KWh*
   
   
## 3. Comparación de modelos

   
   3.1 *Regresión Lineal (LR)*

   3.2 *K Nearest Neighbours (KNN)*

   3.3 *Random Forest (RF)*

   3.4 *Gradient Boosting Tree (GBT)*

   3.5 *Stacking 1 (Regresión Lineal + Random Forest)*
   
   3.6 *Stacking 2 (Random Forest + Gradient Boosting Trees)*



![Comparación](https://user-images.githubusercontent.com/82395947/153264194-23ec30d5-f6e1-4f43-abcd-a51366512826.PNG)


## 4. Predicciones

Comparamos las predicciones resultantes con los valores reales del año 2018.

![Predicciones](https://user-images.githubusercontent.com/82395947/153264508-89fa10dc-df1d-41e5-a198-162f5c9186f2.PNG)

## 5. Front end

Este apartado lo hemos realizado con un **dashboard de Tableau** compuesto de tres pestañas.

   5.1 *Representación de datos*
   
   5.2 *Predicción vs valores reales*
   
   5.3 *My report*
   
En la última pestaña, podremos crearnos un informe 'a la carta' con todos los datos.

## 6. Conclusión 

Con este proyecto, hemos podido desarrollar con claridad los distintos puntos de los que se compone la ciencia de datos.
El RMSE del modelo con los datos que hemos separado al principio, los del año 2018, es de 506.50 KWh, un buen resultado para un modelo que, en un principio, tiene dificultades para extrapolar fuera del rango de entrenamiento.

## 7. Entorno

fitter      1.4.0

google      NA

joblib      1.1.0

matplotlib  3.2.2

numpy       1.19.5

pandas      1.3.5

plotly      5.5.0

seaborn     0.11.2

sinfo       0.3.4

sklearn     1.0.2


IPython             5.5.0

jupyter_client      5.3.5

jupyter_core        4.9.1

notebook            5.3.1


Python 3.7.12 (default, Jan 15 2022, 18:48:18) [GCC 7.5.0]
Linux-5.4.144+-x86_64-with-Ubuntu-18.04-bionic
2 logical CPU cores, x86_64


Session information updated at 2022-02-09 12:24
