# Consumo de alimento en salmones bajo 20% de actividad y su relación con FCRc y SGRc

### Autor
### Pedro Pizarro

### Descripción del Problema a Resolver 


Existe un software en uso que a través de IA ([**3Se**](https://3se.cl)) establece la mayor o menor disposición de los peces a alimentarse durante el período de cultivo medido a través de un % de actividad. El principio establece que alimentar a los salmones durante el ciclo productivo cuando la actividad medida es menor a 20%, resultaría en una mayor probabilidad de pérdida de alimento y, en consecuencia, en una mayor conversión de alimento y en un menor crecimiento. De este modo, se han recopilado los datos 
referentes a la cantidad de alimento ofertada en la fase de 20% de actividad durante todo el período productivo y los parámetros productivos de conversión (**FCRc**) y 
de crecimiento (**SGRc**) al término del ciclo para corroborar o descartar la hipótesis que establece que los peces que durante la totalidad del ciclo productivo consumen más alimento en esta fase de actividad serían menos eficientes en conversión de alimento y en crecimiento. En resumen, el objetivo de este estudio es definir si es que una mayor oferta de alimento entregada bajo esta fase de actividad de 20% afecta el desempeño productivo.

### Descripción de las variables de estudio

- **Consumo de alimento bajo 20% de actividad:** Es la parte expresada en % del total del consumo de alimento, que representa la cantidad de alimento consumida u ofertada a los peces cuando estaban bajo el 20% del indicador de actividad **_(variable predictora)_**.

- **FCRc :** Es el factor de conversión de alimento corregdo de acuerdo al modelo de crecimiento previamnete establecido para el plantel en cultivo. Mide la eficiencia de conversión de alimento a biomasa producida y se expresa en %. **_(variable respuesta)_**.

- **SGRc:** Es la tasa específica de crecimiento corregida de acuerdo al modelo de crecimiento previamente establecido para el plantel en cultivo. Mide la eficiencia del crecimiento en el tiempo y se expresa en %. **_(variable respuesta)_**.    

### Número de observaciones

La base de datos contiene **273 observaciones**.

### Hipótesis de Prueba

Para comprobar si el consumo de alimento bajo la fase de actividad del 20% afecta el rendimiento productivo, en este caso se eligió contrastar a través de análisis estadístico, el consumo en esta fase con la variable de conversión de alimento, ya que por su naturaleza es la variable respuesta que se relaciona de mejor manera con la variable consumo. De este modo, las hipótesis nula y alternativa a contrastar serían:

 **H~0~:** El consumo de alimento bajo 20% de actividad **_no afecta el FCR._**

 **H~1~:** El consumo de alimento bajo 20% de actividad  **_afecta el FCR._**

### Resumen de métodos estadísticos

- Se verifica la correlación entre la variable respuesta FCR y Consumo bajo 20% de actividad mediante test de Pearson.
- Se establece un modelo lineal de la variable FCR en función de Consumo bajo 20% de actividad, Centro y Año de cultivo
- Se aplican test para evaluación de supuestos de independencia, homogeneidad de varianzas y normalidad.
- Se aplica un análisis de varianza de 3 factores para determinar si los efectos de los factores son o no significativos en la variable respuesta.
- Se determina nivel de significancia del modelo y capacidad predictora

### Conclusión del Trabajo

De acuerdo a los análisis estadísticos realizados, se rechaza la hipótesis nula y se concluye que el consumo de alimento bajo 20% de actividad, así como también la variable centro afectan el factor de conversión de los peces (FCR).

 

