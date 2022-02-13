---
title: "Vuelta atrás en Machine Learning"
weight: 1
subtitle: ""
excerpt: "Machine Learning es espectacular, pero es más que *Machines*."
date: 2021-01-01
draft: false
---

# Data Science 
Desde hace unos meses he estado escuchando y leyendo cosas relacionadas
a lo que se conoce como *Data Science*, en un primer momento me despertó
curiosidad, luego descubrí que era casi lo mismo a lo que ya estaba haciendo: estimar modelos para predecir cierta variable (series de tiempo), estimando modelos para medir la probabilidad de que suceda cierto evento (logit y probit), estimar modelos para estimar el efecto causal de cierto tratamiento(análisis de regresión). Pero, me faltaba un ingrediente central en Data Science: El uso intensivo de "*machines*" (computadoras).  
Por supuesto que he estado usando la computadora para estimar mis modelos, hacerlo a mano sería un crimen, pero era de importancia terciaria, lo más importante era encontrar modelos/estimadores que representen cierto comportamiento de los agentes económicos. Todo esto se hacía con teorías *a priori* , es decir, la econometría era una herramienta para mostrar teorías económicas en lugar de demostrarlas. En Data Science, por el contrario, "los datos hablan por sí solos" (o al menos eso es lo que superficialmente vi).Y eso, debo confesar, lo hizo bastante atractivo: Simplemente tenía que crear un *workflow set* con varios modelos de Machine Learning(regression trees, random forest, support vector machines, etc.), elegir mi modelo por medio de *cross-validation*  y listo! Ya no había necesidad de "pensar" simplemente tirarle a la computadora datos y me arrojaría un modelo "óptimo".

## El crimen
Imagina que eres un cocinero y como uno tienes que, bueno cocinar, antes de eso tienes que chequear que tus ingredientes tengan el olor adecuado, no estén dañados, etc (¡No quieres matar a tus comensales!). Lo que yo veía en internet es que la mayoría de personas simplemente **asumían** que sus ingredientes eran buenos y que no necesitaban ningúna revisión. Es más de los ingredientes probablemente no los necesites TODOS, quizás necesites solo una parte o quieras remover otra, mezclar algunos, etc. Esto resulta ser de suma importancia en el modelaje en Machine Learning y se llama *Feature Engineering*, en pocas palabras, significa que *variables* y en qué *forma* van a entrar en tu modelo.  
Tanto en Econometría como en Machine Learning esto es más arte que ciencia y depende en gran parte de la cantidad de variables que tienes disponible y del CONOCIMIENTO que tienes del proceso que quieres modelar, no puedes simplemente dejarle a la computadora hacer los cálculos por ti porque puedes terminar con un modelo totalmente absurdo, es además bastante irresponsable.

## Mi camino
Como he mencionado anteriormente, me emocioné bastante cuando descubrí que simplemente necesitaba más poder computacional, pero luego de pensar un momento me he dado cuenta que ese es el camino a la perdición y a prácticas irresponsables.  
Ahora, no creo considero que Data Science y Machine Learning sean inútiles, al contrario, adecuadamente ejecutadas pueden ser muy útiles , véase un [ejemplo](https://www.youtube.com/watch?v=lji-jNsXmAM), PERO siendo completamente honesto conmigo mismo creo que para llegar al punto en el cual pueda implementar modelos de Machine Learning de manera **responsable**  y **eficiente**  necesito seguir aprendiendo y cometer los suficientes errores, ya he cometido uno: creer que puedo reemplazar pensamiento por gigabytes.


---

