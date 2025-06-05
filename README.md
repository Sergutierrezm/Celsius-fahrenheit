# Celsius-fahrenheit
Modelo de regresión lineal entre celsius y fahrenheit con Python utilizando la API de google Colab

Lo primero, se tiene que crear un archivo con datos en formato CSV, mi ejemplo fue con grados celsius y grados fahrenheit.
Al ser en CSV, se ordena por columnas, una de celsius y otra de fahrenheit y se separa con comas (,) y sin espacios.
Luego añades grados en celsius y añades cuanto seria en grados fahrenheit, misma separacion, con comas y sin espacios.

Tenemos que importar la libreria llamada panda para leer los datos y con seaborn que es otra libreria, se tiene que importar, sirve para crear una grafica y mostrar la relacion entre los datos, en este caso de los grados celsius y grados fahrenheit.
Luego tenemos que separar los datos y los tranformamos los datos para poder entrenar y predeccir con "reshape" y luego ya entrnamos el modelo. 
Luego ya podemos hacer predicciones.
