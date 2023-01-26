#  Prediccion_inmobiliaria
### Machine learning

En este proyecto, el objetivo era crear un modelo de machine learning que pudiera clasificar correctamente los precios de un grupo de viviendas en Estados Unidos en bajos, altos o medios, prediciendo cuáles eran bajos. Para lograrlo, se podía utilizar un modelo supervisado, uno no supervisado o ambos.

## **Técnicas utilizadas**
### *Modelos supervisados*

##  Random forest

Random forest (o random forests) también conocidos en castellano como '"Bosques Aleatorios"' es una combinación de árboles predictores tal que cada árbol depende de los valores de un vector aleatorio probado independientemente y con la misma distribución para cada uno de estos. Es una modificación sustancial de bagging que construye una larga colección de árboles no correlacionados y luego los promedia.

### Ventajas

- Es uno de los algoritmos de aprendizaje más certeros que hay disponible. Para un set de datos lo suficientemente grande produce un clasificador muy certero
- Maneja cientos de variables de entrada sin excluir ninguna
- Da estimaciones de qué variables son importantes en la clasificación
- Tiene un método eficaz para estimar datos perdidos y mantener la exactitud cuando una gran proporción de los datos está perdida
- Computa los prototipos que dan información sobre la relación entre las variables y la clasificación
- Computa las proximidades entre los pares de casos que pueden usarse en los grupos, localizando valores atípicos, o (ascendiendo) dando vistas interesantes de los datos


## Decition Tree

Un árbol de decisión es un modelo de predicción utilizado en diversos ámbitos que van desde la inteligencia artificial hasta la Economía. Dado un conjunto de datos se fabrican diagramas de construcciones lógicas, muy similares a los sistemas de predicción basados en reglas, que sirven para representar y categorizar una serie de condiciones que ocurren de forma sucesiva, para la resolución de un problema.

### Ventajas

- Fácil de entender e interpretar
- Requiere poca preparación de los datos
- Capaz de manejar tanto datos numéricos y categorizados
- Es posible validar un modelo utilizando pruebas estadísticas
- Funciona bien con grandes conjuntos de datos

### *Modelo no supervisado*

## Kmeans
K-means es un método de agrupamiento, que tiene como objetivo la partición de un conjunto de n observaciones en k grupos en el que cada observación pertenece al grupo cuyo valor medio es más cercano

### Ventajas
- El efecto de agrupamiento es mejor
- El principio es simple, la implementación es fácil y la velocidad de convergencia es rápida
- Hay pocos parámetros para ajustar, y generalmente solo el número de clúster K necesita ser ajustado

