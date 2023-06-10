# Análisis del Índice de Marginalización en México

Este proyecto de análisis de datos se enfoca en el Índice de Marginalización en México utilizando la Base de datos por municipio 2020 del Consejo Nacional de Población. El objetivo es explorar y visualizar la distribución de la marginalización en el país y su relación con variables como el analfabetismo y la población en localidades pequeñas.

Se puede explorar mucho más de la base de datos de la [CONAPO](https://www.gob.mx/conapo/documentos/indices-de-marginacion-2020-284372). Además en el siguiente [documento](https://www.gob.mx/cms/uploads/attachment/file/685354/Nota_te_cnica_IMEyM_2020.pdf) se desarrolla el significado de las metricas utilizadas.

## Bibliotecas utilizadas

El proyecto se desarrolló utilizando las siguientes bibliotecas:

- **pandas**: Utilizada para la carga y manipulación de datos en forma de tabla.
- **matplotlib**: Utilizada para la generación de gráficos y visualizaciones.
- **numpy**: Utilizada para realizar cálculos numéricos y operaciones en matrices.
- **Jupyter Notebook**: El proyecto se desarrolló en Jupyter Notebook en el ambiente de VS Code.

## Código fuente

El código fuente completo se encuentra disponible en el archivo [aquí](https://github.com/fofojaramillo/datsci-prog-proyecto/blob/main/ind-marg.ipynb). Este archivo contiene el código en Python, junto con los pasos y resultados del proyecto. Para obtener información más detallada, consulta el código fuente y los comentarios en el archivo Python.

## Contenido del proyecto

El proyecto se resume de la siguiente manera:

1. *Carga de datos*: Se lee el archivo CSV que contiene la información del Índice de Marginalización por municipio en 2020 utilizando la biblioteca pandas. Además de verificarse la integridad de los datos de la tabla.

2. *Análisis general de los datos*: Se realiza un análisis descriptivo de los atributos cuantitativos de la tabla, como la población total, el porcentaje de población analfabeta, sin educación básica, sin servicios básicos, etc.

3. *Distribución de la marginalización por estados*: Se crea una tabla dinámica que muestra la cantidad de municipios en cada grado de marginación para cada estado. Se calculan los porcentajes relativos de municipios por estado para cada grado de marginación y se grafican los resultados en un gráfico de barras apiladas.

4. *Distribución de la población en los grados de marginalización por estados*: Se repite el proceso anterior, pero esta vez se suma la población de cada municipio por estado en cada grado de marginación. Se calculan los porcentajes relativos de la población por estado para cada grado de marginación y se grafican los resultados en otro gráfico de barras apiladas.

5. *Analfabetismo y poblaciones pequeñas*: Se crea un subconjunto de datos que contiene las variables de porcentaje de analfabetismo y porcentaje de poblaciones en localidades de menos de 5000 habitantes. Se grafican los datos en un gráfico de dispersión con color, donde cada punto representa un municipio y su posición indica el porcentaje de poblaciones pequeñas y el porcentaje de analfabetismo.

6. *Poblaciones pequeñas*: se hace énfasis en cómo se debe abordar el problema de la marginación de los municipios pequeños. Se muestra cómo difieren las métricas trabajadas en el proyecto con respecto a la media de su respectivo estado.

## Cosas adicionales

- Hay un archivo *.parquet* hecho a partir de dataframe final del proyecto.
- Las graficas obtenidas estan [aquí](https://github.com/fofojaramillo/datsci-prog-proyecto/tree/main/graficas).

Cualquier cosa, detalle, observación, estoy al pendiente.
