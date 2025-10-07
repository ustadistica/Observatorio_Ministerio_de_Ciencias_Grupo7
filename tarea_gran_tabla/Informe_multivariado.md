# Análisis Multivariado

## 1. Análisis de Componentes Principales (ACP)

*Técnicas con variables numéricas*

En la base de datos analizada se cuenta con las siguientes variables:

Edad → variable numérica continua.

Nivel de estudio conseguido por el investigador → variable cualitativa ordinal (codificada con números, pero que representa categorías ordenadas).

Nivel del investigador → variable cualitativa ordinal (también codificada en números, pero que corresponde a jerarquías de categorías).


El Análisis de Componentes Principales (ACP) es una técnica multivariada cuyo propósito es reducir la dimensionalidad de un conjunto de variables cuantitativas, transformándolas en nuevas variables no correlacionadas llamadas componentes principales, que explican la mayor parte de la varianza total.


Requisitos fundamentales:

Contar con varias variables numéricas continuas.

Que exista una matriz de correlaciones significativa entre ellas.

En el presente caso:

Solo se dispone de una variable continua (Edad).

Las otras dos variables, aunque están codificadas como números, son en realidad cualitativas ordinales, por lo que no cumplen el supuesto de ser cuantitativas.



Conclusión: No es posible aplicar un ACP en esta base de datos, ya que no existen suficientes variables numéricas continuas para extraer componentes principales.



## 2. Análisis Factorial (FA)

*Técnicas con variables numéricas*


El Análisis Factorial es una técnica multivariada que busca identificar factores comunes latentes que expliquen las correlaciones entre un conjunto de variables observadas.

Requisitos principales:

Contar con múltiples variables numéricas continuas.

Que dichas variables estén suficientemente correlacionadas para justificar la existencia de factores comunes.

En este caso:

Solo se dispone de una variable continua (Edad).

Las otras dos, aunque numéricas en apariencia, son en realidad ordinales categóricas y no cumplen con los supuestos del análisis factorial.

Conclusión: No es posible realizar un análisis factorial en esta base de datos, pues no se cumplen los requisitos básicos de contar con varias variables numéricas continuas correlacionadas.


## 3. Análisis de Correspondencia Simple (CA)

Con el propósito de explorar las asociaciones existentes entre variables categóricas relevantes dentro del conjunto de datos, se realizaron tres análisis de correspondencia simple (ACS).Cada análisis permitió identificar patrones y relaciones entre categorías, así como posibles agrupamientos o afinidades entre las modalidades de las variables estudiadas.

Los tres análisis efectuados fueron los siguientes:

**a) Relación entre el género del investigador y el gran área del conocimiento.**

Este análisis busca determinar si existen diferencias o concentraciones particulares de género en las distintas áreas del conocimiento, permitiendo observar posibles sesgos o desigualdades en la participación investigativa según el campo disciplinar.

**b) Relación entre el género del investigador y la universidad a la que pertenece.**

En este caso, el análisis permite observar si hay una asociación entre el género y la institución de afiliación, con el fin de detectar posibles patrones institucionales o diferencias en la composición de género entre universidades.

**c) Relación entre el nivel de formación del investigador y su clasificación como investigador.**

El objetivo de este análisis es examinar cómo se relacionan los niveles académicos alcanzados con la categoría de clasificación otorgada a los investigadores, identificando posibles tendencias o correspondencias entre formación y estatus investigativo.






ç



