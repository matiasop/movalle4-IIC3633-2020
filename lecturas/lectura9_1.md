# Multi-Armer Recommender System Bandit Ensembles

En este paper los investigadores explican un nuevo tipo de ensamble de sistemas recomendadores. Este ensamble se basa en la adaptación de dos algoritmos "bandit". Tiene la ventaja de que la forma de interactuar con el recomendador es "cíclica": esto se refiere a que el usuario le da feedback de las recomendaciones, y el sistema recibe este feedback y crea nuevas recomendaciones para que el usuario evalue.

Los algoritmos bandit son ensambles que eligen el algoritmo de recomendación a utilizar basados en el feedback dado con el usuario. Existen distintas técnicas para elegir el algoritmo, como epsilon-greedy y Thompson.

Un aspecto que encontré interesante es la forma en que testearon los algoritmos bandit. Para simular un ambiente cíclico, donde el sistema recomendador recibe el feedback del usuario para generar nuevas recomendadores, usan solo el 5% de los ratings para el dataset inicial, y el 95% restante lo usan para simular el feedback de los usuarios. Encontré esta técnica interesante porque están "creando" un dataset para probar recomendadores cíclicos sin necesariamente tener usuarios reales que den feedback con cada nueva recomendación. Esto es útil porque hace más fácil probar distintos algoritmos sin tener que probarlos en usuarios humanos, lo que traería varias complicaciones.

Un aspecto que me pareció que podría ser mejorado del paper es la explicación de los algoritmos bandit. Los investigadores dan una explicación de alto nivel de las versiones Thompson y epsilon-greedy de los algoritmos, pero creo que la explicación podría haber sido un poco más detallada. Me pareció que fue una explicación de muy alto nivel, lo que si bien sirve para entender más o menos como funciona el algoritmo, no queda claro exactamente cómo funciona.

Me pareció extraño que most-popular tenga mejor cumulative recall que matrix factorization. Es de esperar que este método de recomendación tenga mejor performance, pero los investigadores explicaron que era porque el dataset estaba divido en 5% training y 95% testing. Esto explica el mal rendimiento de matrix factorization en esta situación.

El principal aporte de este paper fue la creación de un algoritmo bandit que selecciona el algoritmo de recomendación a utilizar según el feedback del usuario. 
