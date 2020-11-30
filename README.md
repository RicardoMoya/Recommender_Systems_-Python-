# Sistemas de Recomendación

* Autor: Ricardo Moya García, PhD
* Release: 1.0.0
* Fecha última actualización: 30-05-2020
* ![python versions](https://img.shields.io/badge/python-3.6%2C%203.7-blue.svg)


<hr>

En este proyecto de GitHhub podrás encontrar parte del material que utilizo para impartir las clases de Sistemas de Recomendación.



El contenido compartido es el siguiente:


### Tema 1: Introducción a los Sistemas de Recomendación

Introducción a los Sistemas de Recomendación, ¿Que son?, tipos de Sistemas de Recomendación, ¿Que datos utilizamos para emitir recomendaciones?

- [1_Introduccion_a_los_Sistemas_de_Recomendacion.ipynb](https://github.com/RicardoMoya/Recommender_Systems_-Python-/blob/main/1_Introduccion_a_los_Sistemas_de_Recomendacion.ipynb)


### Tema 2: Técnicas y Métricas de Evaluación de los Sistemas de Recomendación

En tema se muestra la manera de evaluar el rendimiento de los sistema de recomendación, viendo las métricas tradiciones para evaluar los resultados de las recomendaciones así como métricas de evaluación específicas de los sistemas de recomendación. 

- [2_Evaluacion_de_los_Sistemas_de_Recomendacion.ipynb](https://github.com/RicardoMoya/Recommender_Systems_-Python-/blob/main/2_Evaluacion_de_los_Sistemas_de_Recomendacion.ipynb)


### Tema 3: Filtrado Colaborativo

En este tema se muestran los Sistemas de Recomendación basados en Filtrado Colaborativo, explicando que es el Filtrado Colaborativo y como se realizan las recomendaciones paso por paso:

- [3_0_Filtrado_Colaborativo.ipynb](https://github.com/RicardoMoya/Recommender_Systems_-Python-/blob/main/3_0_Filtrado_Colaborativo.ipynb)

#### Tema 3.1: Filtrado Colaborativo con K-Vecinos (KNN)

En este apartado se muestra el funcionamiento e implementación paso a paso de un Sistema de Recomendación basado en Filtrado Colaborativo con el algoritmo de aprendizaje de los K-Vecinos.

- [3_1_1_Filtrado_Colaborativo_K_Nearest_Neighbors.ipynb](https://github.com/RicardoMoya/Recommender_Systems_-Python-/blob/main/3_1_1_Filtrado_Colaborativo_K_Nearest_Neighbors.ipynb)
- [3_1_2_Filtrado_Colaborativo_K_Nearest_Neighbors_MovieLens.ipynb](https://github.com/RicardoMoya/Recommender_Systems_-Python-/blob/main/3_1_2_Filtrado_Colaborativo_K_Nearest_Neighbors_MovieLens.ipynb)

#### Tema 3.2: Filtrado Colaborativo con Factorización Matricial

En este apartado se muestra el funcionamiento e implementación paso a paso de un Sistema de Recomendación basado en Filtrado Colaborativo con Factorización Matricial.

- [3_2_1_Filtrado_Colaborativo_Factorizacion_Matricial.ipynb](https://github.com/RicardoMoya/Recommender_Systems_-Python-/blob/main/3_2_1_Filtrado_Colaborativo_Factorizacion_Matricial.ipynb)
- [3_2_2_Filtrado_Colaborativo_Factorizacion_Matricial_MovieLens.ipynb](https://github.com/RicardoMoya/Recommender_Systems_-Python-/blob/main/3_2_2_Filtrado_Colaborativo_Factorizacion_Matricial_MovieLens.ipynb)


`Nota: Los Notebooks de los temas 3.2 y 3.1 se encuentran completos en la carpeta Notebooks_Resueltos.`

<hr>

## Instalación del entorno

Para ejecutar los scripts y notebooks de este proyecto es necesario tener creado un entorno virtual con conda (también puede ser con un virtualenv), en el que es suficiente tener instaladas las librerías que instala anaconda por defecto al crear el entorno (numpy, scipy, pandas, matplotlib, scikit, etc).

A continuación se muestran los pasos a seguir para crear el entorno virtual con conda por medio de una consola:

`Nota: estos mismos pasos pueden realizarse también por medio del Anaconda Navigator, pero mejor hacerlo por consola.`

1.- Crear un entorno virtual con un python 3.6 llamado "python36_RecSys"

```
>> conda create -n python36_RecSys python=3.6 anaconda
```

2.- Activar el entorno virtual

```
>> conda activate python36_RecSys
```

#### Bonus Track Anaconda

A continuación se muestran algunas acciones extra:

1.- Desinstalar librerías:

```
>> pip uninstall nombre_libreria
```

2.- Desactivar el entorno virtual (previamente tiene que estar activado)

```
>> conda deactivate
```

3.- Eliminar entorno virtual (llamado "python36_RecSys")

```
>> conda remove -n python36_RecSys -all
```