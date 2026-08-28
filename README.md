
## Descripción del proyecto

Este proyecto realiza un análisis exploratorio del dataset histórico del Titanic, que contiene información de 891 pasajeros del viaje. El objetivo es practicar el uso de la librería pandas para cargar, explorar y entender la calidad de los datos (valores faltantes, tipos de datos, distribución de variables) antes de un análisis más profundo.

## Funciones investigadas

Durante la exploración del dataset Titanic se investigaron las siguientes funciones de Pandas:

### `info()`

Permite visualizar información general del DataFrame, como el número de filas, columnas, tipos de datos y valores no nulos. Es útil para conocer la estructura del conjunto de datos.

### `isnull().sum()`

Permite identificar los valores nulos o faltantes en cada columna. `isnull()` detecta los valores vacíos y `sum()` cuenta cuántos existen.

### `shape`

Muestra las dimensiones del DataFrame, indicando la cantidad de filas y columnas que contiene.

### `head()`

Muestra las primeras cinco filas del DataFrame por defecto. Sirve para realizar una visualización rápida de los datos.

### `fillna()`

Permite reemplazar o llenar los valores nulos de una columna o del DataFrame con un valor determinado.

### `drop()`

Permite eliminar filas o columnas que no sean necesarias para el análisis o que contengan información no deseada.

### `value_counts()`

Cuenta cuántas veces aparece cada valor único dentro de una columna. Es útil para conocer la frecuencia de los datos.

## Hallazgos de la exploración

Durante la exploración del dataset **Titanic** se analizaron las columnas, los tipos de datos y la presencia de valores nulos.

Se identificó que el conjunto de datos contiene información sobre los pasajeros, como su edad, sexo, clase, tarifa y si sobrevivieron o no.

También se encontraron valores faltantes en algunas columnas, por lo que es necesario identificarlos y posteriormente realizar procesos de limpieza utilizando funciones como `fillna()` o `drop()`.

Además, mediante `value_counts()` se pueden analizar las frecuencias de los diferentes valores de una columna, lo que permite conocer mejor la distribución de los datos.

De los 891 pasajeros, 549 no sobrevivieron y 342 sí sobrevivieron (aprox. 38% de tasa de supervivencia).


## Filas y columnas: 891 filas, 12 columnas
Columnas con valores vacíos:
Age: 177 vacíos
Cabin: 687 vacíos
Embarked: 2 vacíos

## Analisis de los sobrevivientes 


