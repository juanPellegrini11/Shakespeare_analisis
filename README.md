# Analísis sobre las obras de William Shakespeare

Este repositorio contiene dos scripts para realizar un análisis sobre los trabajos del escritor **William Shakespeare**. 
Se utilizarón librerias conocidas en el entorno de la ciencia de datos, como ser *Pandas*, *Seaborn*, *Scikit-learn* y *Fasttext*. En el archivo [requirements.txt](https://github.com/britsimm/Shakespeare_works_analysis/blob/main/requirements.txt) puede encontrar las librerias necesarias. 

Se utilizó la siguiente base de datos abierta: [Base de datos con las obras de William Shakespeare](https://relational.fit.cvut.cz/dataset/Shakespeare) .
 
El trabajo se separa en dos partes:

## Parte 1
Se realizó un análisis exploratorio sobre los datos, parte del foco estuvo en las obras del escritor, en particular es de interés los años de publicación así como el género, también se realiza un recuento de palabras. Para esta parte se utilizó el scrtip ["shakespeare_analysis.ipynb"](https://github.com/britsimm/Shakespeare_works_analysis/blob/main/shakespeare_analysis.ipynb)
El resultado de estos análisis se encuentran en el PDF ["Informe"](https://github.com/britsimm/Shakespeare_works_analysis/blob/main/Informe.pdf).


## Parte 2
Se profundiza en técnicas de aprendizaje automático para entrenar dos modelos clasicos _Multinomial Naive Bayes_ (MultinomialNB) y _Support Vector Machine_ (SVM) así cómo un modelo especializado llamado _Fast-Text_ para predecir que personaje dice párrafos dado. Para esta parte se trabajó con un conjunto reducido de tres personajes.

Tanto para _MultinomialNB_ como para _SVM_ se aplico la técnica de _Cross-Validation_ para elegir los parámetros óptimos dentro de un set de 28 posibilidades y se realizo sus respectivas matrices de confusiones para comprender el rendimiento de los modelos. 

Por otro lado, se experimenta cambiando un personaje con el fin de desbalancear la cantidad de párrafos y entender qué efecto tiene en los modelos.

Para esta parte se utilizó el script ["shakespeare_analysis_2.ipynb"](https://github.com/britsimm/Shakespeare_works_analysis/blob/main/shakespeare_analysis_2.ipynb), y los resultados se encuentran en el PDF ["Informe_parte2"](https://github.com/britsimm/Shakespeare_works_analysis/blob/main/Informe_parte2.pdf).







