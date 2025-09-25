# -Analisis-de-ventas-y-exito-de-videojuegos-2000-2016-
## Introducción 

Trabajas para la tienda online Ice que vende videojuegos por todo el mundo. Las reseñas de usuarios y expertos, los géneros, las plataformas (por ejemplo, Xbox o PlayStation) y los datos históricos sobre las ventas de juegos están disponibles en fuentes abiertas. Tienes que identificar patrones que determinen si un juego tiene éxito o no. Esto te permitirá detectar proyectos prometedores y planificar campañas publicitarias.

Delante de ti hay datos que se remontan a 2016. Imaginemos que es diciembre de 2016 y estás planeando una campaña para 2017.

Lo importante es adquirir experiencia de trabajo con datos. Realmente no importa si estás pronosticando las ventas de 2017 en función de los datos de 2016 o las ventas de 2027 en función de los datos de 2026.

El dataset contiene una columna "rating" que almacena la clasificación ESRB de cada juego. El Entertainment Software Rating Board (la Junta de clasificación de software de entretenimiento) evalúa el contenido de un juego y asigna una clasificación de edad como Adolescente o Adulto.

## Este proyecto se analizará el conjunto de datos con el fin de:
* Comprender la distribución de ventas por región, plataforma y género.

* Investigar la relación entre reseñas (de críticos y usuarios) y las ventas.

* Evaluar el impacto de las clasificaciones ESRB en diferentes regiones.

* Detectar patrones que caracterizan a los videojuegos más exitosos.

* Formular y probar hipótesis estadísticas relevantes para la toma de decisiones comerciales.

La información obtenida será clave para ayudar a Ice a enfocar sus recursos en proyectos prometedores, optimizar su estrategia de marketing y consolidarse en un mercado altamente competitivo.

## Conclusión general
En este proyecto, analizamos datos históricos de ventas, reseñas, plataformas y géneros de videojuegos disponibles hasta el año 2016 con el objetivo de identificar patrones que ayuden a predecir el éxito de un juego y planificar campañas publicitarias efectivas para el año 2017.

### Preparación y limpieza de datos
Se estandarizaron los nombres de columnas, se convirtieron tipos de datos adecuados y se trató la abreviatura 'tbd' como valores faltantes.

Se creó una nueva columna con las ventas globales (total_sales) sumando todas las regiones.

Se identificaron y excluyeron registros incompletos para los análisis sensibles (como reseñas y fechas).

### Análisis exploratorio
La mayoría de los lanzamientos ocurrieron entre 2000 y 2016. Los datos anteriores son escasos y no representativos, por lo que el modelo se basa en ese período.

Plataformas líderes recientes incluyen PS4, XOne, y 3DS. Consolas antiguas como PS2 y Wii fueron populares, pero ya no presentan lanzamientos.

Se observó que una nueva consola tarda en promedio 2-3 años en alcanzar su punto máximo, mientras que las antiguas desaparecen gradualmente tras ese período.

El género Acción lidera en ventas globales, seguido por Deportes y Shooter. Role-Playing es especialmente fuerte en Japón.

Las reseñas de usuarios y críticos muestran correlación positiva con las ventas, especialmente en plataformas como PS4.

En cuanto a regiones:

Norteamérica y Europa comparten plataformas y géneros populares (Acción, Deportes, Shooter).

Japón muestra claras diferencias, con preferencia por Role-Playing y plataformas portátiles (como DS o PS2).

La clasificación ESRB tiene más influencia en NA y Europa que en Japón, donde muchos juegos no tienen clasificación ESRB.

### Pruebas de hipótesis
Se encontró una diferencia significativa en las calificaciones promedio de usuarios entre las plataformas Xbox One y PC.

No hubo evidencia significativa de diferencia en las calificaciones promedio entre los géneros Acción y Deportes.

### Recomendaciones para 2017
Enfocar campañas en juegos del género Acción y Shooter, especialmente en plataformas como PS4 y XOne.

Considerar diferencias regionales: en Japón, priorizar Role-Playing y consolas portátiles.

Prestar atención a las reseñas tempranas de usuarios y críticos como indicadores de potencial éxito.

Asegurar que los juegos tengan una clasificación ESRB clara para mejorar su recepción en occidente.
