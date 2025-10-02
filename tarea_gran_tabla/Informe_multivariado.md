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

