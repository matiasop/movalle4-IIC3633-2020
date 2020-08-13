# Netflix Update: Try This at Home

En este blog post, uno de los participantes de la competencia de sistemas recomendadores de Netflix, explica cómo fue que obtuvo un buen resultado. La competencia consiste en predecir el ranking que los usuarios le darán a las películas. Se usa la raiz del error cuadrático medio para calcular el error de clasificación. Usaron 'singular value decomposition' para reducir la cantidad de aspectos de las películas. Basado en el rating que el usuario da a la película X, el algoritmo ve que tan alejado está ese valor del promedio y genera un valor para las preferencias del usuario basado en las categorias de la película X (por ejemplo, si le da un rating mayor al promedio en una película de acción, el valor de la preferencia de acción del usuario sube).

Es divertido de leer porque no está escrito de forma estrictamente académica. Para hacer más fácil la comprensión del trabajo hecho se podrían haber usado diagramas o imágenes, aparte del código.

Aparte de explicar la solución que su equipo hizo, el autor narra los problemas con los que se encontró en el proyecto. Estas historias me ayudaron a darme cuenta de que el asunto no es tan simple como leer un enunciado y buscar la solución en un libro. Tuvieron que idear soluciones que nunca antes se habían usado.
