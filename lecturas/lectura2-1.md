# Collaborative Filtering for Implicit Feedback Datasets

### Mini-Resumen

El problema que trata de resolver este paper es cómo obtener feedback implícito de los usuarios. Busca poder saber, por ejemplo, qué productos no le gustan al usuario. Es importante el uso de feedback implícito porque no todos los sistemas pueden recibir input explicito del usuario (no todas las páginas reciben likes o estrellas). El feedback implícito usa historial de compras, patrones de búsqueda, movimientos del ratón.

El feedback implícito tiene algunas características que lo diferencian del explícito:
- No hay feedback negativo
- Solamente se pueden 'adivinar' las preferencias
- El feedback se cuantifica usando 'confianza' en vez de preferencia
- La evaluación de qué tan bien recomienda es distinta

El modelo propuesto trata de minimizar la 'incertidumbre' de si a un usuario 'u' le gustó un item 'i'. Mientras más veces el usuario haya visto una película, menor será la incertidumbre de que le gustó.

### Aspectos positivos del paper:
- Buena introducción: explica claramente la importancia del feedback implícito y cuales son sus diferencias con el explícito.
- Es bueno que toman en consideración que alguien se puede poner a ver una serie y dejar la televisión prendida, viendo programas que lo le interesan a ese usuario. Para solucionar esto le dan menos peso a los programas a medida que pasa más tiempo desde que se cambió de canal.

### Aspectos negativos del paper:
- No me quedó muy claro cómo calcularon la complejidad computacional del sistema recomendador. Quizás podrían haber hecho un mejor trabajo explicándolo.- Los autores del paper probaron su modelo en un sistema de recomendación de películas usando como feedback implícito de los usuarios el tiempo que vieron las películas. Si bien obtuvieron buenos resultados, hubiese sido bueno que probaran otras formas de recibir input implícito, como el historial de compras, movimientos de ratón, etc. Aunque quizás tendrían que inventar otra manera de crear la matriz usuario-item y sería demasiada información para un solo paper.
- Podrían haber comparado este modelo con un sistema recomendador que use feedback explícito. Esta información podría ser relevante para saber qué tan conveniente es agregar recomendación explícita vs solamente usar implícita.
