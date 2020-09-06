# Document Clustering Based On Non-negative Matrix Factorization

Este paper se trata sobre hacer clustering de documentos. Esto significa agrupar los textos que son similares para encontrar grupos parecidos. Para hacer esto, los investigadores proponen un algoritmo de factorización no negativa, y prueban en un dataset y resulta que su algoritmo es mejor que otro algoritmo para clustering (SVD).

Un problema que encontré es que solo hace la comparación entre NMF y SVD en un dataset. Lo ideal es que se hiciera en más de un solo dataset. Podría ocurrir que el algoritmo tiene un buen performance solo en este dataset.

Da una explicación teórica de por qué este modelo debería ser mejor que SVD (algo relacionado con que el hecho de que los vectores no pueden ser negativos y no necesitan ser ortogonales). No me queda claro cómo los investigadores podrían haber sabido a priori, sin realizar la experimentación, que este método era mejor. Podría haber sido el caso que el sistema sin necesidad de factorización matricial ni con vectores con valores exclusivamente positivos hubiese sido mejor. Creo que no dan una explicación de por qué necesariamente esta forma era mejor al particionar documentos.

En esta investigación se explicó el funcionamiento de un algoritmo basado en factorización no negativa de una matriz. Las ventajas que tiene este algoritmo de clustering es que parece ser mejor que otros algoritmos más clásicos como SVD.


