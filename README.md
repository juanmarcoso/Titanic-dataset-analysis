# Planteo y resolución de un Dataset sobre el viaje del Titanic

En el siguiente modelo vamos a realizar un análisis exploratorio de datos sobre la base de datos de pasajeros del Titanic.

Dicha base de datos se puede descargar desde la siguiente dirección **(https://raw.githubusercontent.com/mwaskom/seaborn-data/master/titanic.csv)**

El set de datos se descargará de forma local en el almacenamiento de Google Colab (opcional) y luego se importará a un DataFrame de **Pandas** para su procesamiento.

Para ello se deberán realizar las siguientes acciones:

1. Describir la estructura del conjunto de datos.
2. Obtener algunos indicadores estadísticos de las columnas:
  1. age
  2. fare
3. Caracterizar a grandes rasgos el pasaje de barco de acuerdo a sexo, edad y nivel socioeconómico
4. Representar cada una de esas características mediante un gráfico adecuado
5. Categorizar el pasaje nuevamente, pero considerando solamente los pasajeros embarcados en el puerto de Shouthampton
6. ¿Puede sacar alguna conclusión comparando las dos muestras de datos?
7. Reemplazar los valores nulos en el campo `age` con el promedio de edades calculado para la misma columna. ¿Cómo cambia el promedio de edades al hacer ese cambio?
8. ¿Qué proporción de hombres adultos sobrevivieron en relación a todos los hombres del barco?
9. ¿Qué proporción con respecto al total de pasajeros?
10. ¿Qué proporción de pasajeros sobrevivieron, de acuerdo al tipo de cubierta en la que viajaban?
11. Divida los valores de la columna `fare` (Precio del boleto) en 4 segmentos.
12. Utilize esos segmentos para comparar los supervivientes, con respecto a la cantidad total de supervivientes del pasaje
13. ¿Obtiene alguna información útil con respecto a este análisis?
14. Realice el mismo análisis con el campo `age` (Edad) de los pasajeros.
15. ¿Obtiene información útil en este caso?
