# Predicción-Acoso-en-Twitter
Objetivo: usar Python para detectar el acoso cibernético en Twitter según las categorías y los tipos de lenguaje utilizados con los tweets en riesgo (INFO 368: proyecto de análisis no estructurado)

## Créditos adicionales para miembros del grupo: 
David Kimball, Islam Laib, Adam Soloski y Sammy Jbara

## Fuente de datos:

API de Twitter 

## Bibliotecas principales utilizadas:
Python-Twitter, NLTK, Pandas

Bullying (clasificación binaria basada en la validación cruzada):  

1 = Bullying
0 = No intimidación

## Categorías / tipos de acoso utilizados para recuperar y evaluar con tweets (etiquetas no incluidas en el csv publicado del conjunto de datos):


- Orientado a la política

- Malas palabras

- "Palabras malas" (idiota, perdedor, etc.) 

## Modelos evaluados con n-gramos (unigramo, bigramas, trigramas, combinación (n = 3): 

Bayes ingenuo, árbol de decisión, regresión logística, máquina de vectores de soporte

## Ejemplos de tweets de nuestra metodología usando "malas palabras":
