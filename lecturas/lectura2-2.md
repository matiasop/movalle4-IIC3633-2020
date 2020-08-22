# BPR: Bayesian Personalized Ranking from Implicit Feedback

### Mini-Resumen

En este paper se exploran sistemas recomendadores usando feedback implícito de clicks y compras pasadas. Se presenta un criterio de optimización que viene del máximo estimador posterior bayesiano para encontrar recomendaciones óptimas. También enseñan cómo entrenar este estimador usando descenso de gradiente estocástico.

Para encontrar el mejor estimador bayesiano, usa la función de verosimilitud p(item i es mejor recomendación que el ítem j | estimador) y la función a posteriori p(estimador).

En el algoritmo de aprendizaje se usa descenso de gradiente con 'bootstrap sampling' de tripletas de items. 

### Aspectos positivos del paper
- Deja claramente explicado cuál es el problema que se aborda en el paper. Tiene escritas todas las definiciones matemáticas y hay figuras que ayudan a entenderlas.
- Si bien este sistema recomendador calcula las preferencias estáticamente, los autores explican cómo se podría extender para ir agregando nuevos datos sin tener que recomputar todo desde cero.
- Compara el modelo en distintos datasets y con otras técnicas de recomendación de feedback implícito.

### Aspectos negativos del paper
- No me quedó muy claro cómo dedujo el máximo estimador a posteriori. Creo que se saltan algunos pasos. Podrían haberlo explicado un poco mejor para personas no tan familiarizadas con estimadores bayesianos.
