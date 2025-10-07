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

--------------------------------

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

--------------------------


## 3. Análisis de Correspondencia Simple (CA)

Con el propósito de explorar las asociaciones existentes entre variables categóricas relevantes dentro del conjunto de datos, se realizaron tres análisis de correspondencia simple (ACS).Cada análisis permitió identificar patrones y relaciones entre categorías, así como posibles agrupamientos o afinidades entre las modalidades de las variables estudiadas.

Los tres análisis efectuados fueron los siguientes:

**a) Relación entre el género del investigador y el gran área del conocimiento.**

Este análisis busca determinar si existen diferencias o concentraciones particulares de género en las distintas áreas del conocimiento, permitiendo observar posibles sesgos o desigualdades en la participación investigativa según el campo disciplinar.

**b) Relación entre el género del investigador y la universidad a la que pertenece.**

En este caso, el análisis permite observar si hay una asociación entre el género y la institución de afiliación, con el fin de detectar posibles patrones institucionales o diferencias en la composición de género entre universidades.

**c) Relación entre el nivel de formación del investigador y su clasificación como investigador.**

El objetivo de este análisis es examinar cómo se relacionan los niveles académicos alcanzados con la categoría de clasificación otorgada a los investigadores, identificando posibles tendencias o correspondencias entre formación y estatus investigativo.



### a) Género y Gran Área del Conocimiento


<img width="1440" height="900" alt="Captura de pantalla 2025-10-07 a la(s) 1 00 56 a m" src="https://github.com/user-attachments/assets/1600c806-7cff-4f0b-bf1f-b582b2eebee5" />


Se observa que en las dos primeras componentes se explica el 99.6% de la varianza, esto nos indica que se deberían escoger dos componentes. Ahora, en las contribuciones y cosenos cuadrados, nos indica algo similar, por lo que se escogen dos componentes.

<img width="1440" height="900" alt="Captura de pantalla 2025-10-07 a la(s) 1 07 35 a m" src="https://github.com/user-attachments/assets/25289893-a9d5-4c47-b6e9-f332517df861" />

La gráfica muestra que las personas que tienen género masculino están asociadas con la gran área de conocimiento, ciencias agrícolas, ciencias naturales y humanidades. 
Por otro lado, las personas del género femenino están asociadas con las ciencias médicas y de la salud. 
Las personas con género intersexual no están asociadas con nadie, al igual que no disponible.
Ingeniería y tecnología, ciencias sociales y no registra, no están asociadas con ningún tipo de género de los investigadores.


### b) Género y Universidad del Investigador


<img width="1440" height="900" alt="Captura de pantalla 2025-10-07 a la(s) 12 57 23 a m" src="https://github.com/user-attachments/assets/f7cc6560-7d0e-4b59-a518-72f437f0d071" />


Se observa que la varianza explicada por las dos primeras componentes es de 84.9% por lo que con dos dimensiones se puede explicar estas dos variables. Aunque sse observa en los cosenos y contribuciones que la dimension tres aporta, de igual manera solo se trabajara con las dos primeras dimensiones.


<img width="1440" height="900" alt="Captura de pantalla 2025-10-07 a la(s) 1 25 50 a m" src="https://github.com/user-attachments/assets/ac785bc8-82d4-41d4-a6e3-19bfc309a301" />


En la gráfica se observa que la universidad estadual do norte fluminense Darcy y Ribero y investigador independiente no se asocian con ningún género, las demás afiliaciones de universidades de los investigadores se asocian a masculino y femenino.
Además no disponible e intersexual, no se asocia a ninguna universidad.



### c) Nivel de Formación y Clasificación del Investigador

<img width="717" height="627" alt="Captura de pantalla 2025-10-07 a la(s) 1 37 08 a m" src="https://github.com/user-attachments/assets/81ce5ea4-620a-4aed-ad07-cf7855a0e60d" />

Se observa que la varianza explicada por las dos primeras componentes es de 98.8% por lo que con dos dimensiones se puede explicar estas dos variables. Los cosenos y contribuciones respaldan esta dicision.


<img width="1394" height="632" alt="Captura de pantalla 2025-10-07 a la(s) 1 48 31 a m" src="https://github.com/user-attachments/assets/5daa9f84-c1b1-4ff4-bf52-6b8dc39e5b6a" />


Los investigadores que tienen posdoctorado se asocian con los investigadores senior y emérito, esto teniendo sentido que entre más estudio poseas el investigador mayor su cargo como investigador.
El investigador junior está asociado con pregrado, magíster, especialidad médica y especialización.
Las demás no tienen asociación





