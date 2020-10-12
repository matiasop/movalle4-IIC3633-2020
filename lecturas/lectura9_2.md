# Carousel Personalization in Music Streaming Apps with Contextual Bandits

En este paper se hace uso de algoritmos bandit with multiple arms para elegir items para un "carrusel", que es una especie de lisat ordenada que muestra los ítems.  La idea del algoritmo bandit with multiple arms es, en cada ronda, elegir un conjunto de L items de un total de K items. El objetivo es maximizar la recompensa recibida por haber elegido estos L ítems. Existen distintas versiones del algoritmo, cada una con ventajas y desventajas. Los investigadores prueban distintos de estos algoritmos en el problema de recomendación en un carrusel.

Una aspecto positivo de este paper es que los investigadores explican cómo funciona el algoritmo bandit. Muestran cuál es su objetivo, por qué este algoritmo tiene un problema al ser multi-objetivo y cuáles son los distintos versiones de este algoritmo. En este aspecto este paper es mejor que el paper de algoritmos bandit usados en ensambles de recomendadores. Ese otro paper no explicaba con mucho detalle el algoritmo, solamente decía los elementos principales.

Otro aspecto positivo es que el modelo creado por los investigadores no asume que los ítems no vistos merecen una puntuación de 0. Solo se usan los items que el usuario tuvo la posibilidad de ver al hacer scrolling. 

Fue interesante la parte en que los investigadores explicaron que no necesariamente los mejores L items van a hacer la mejor playlist. El interés de una playlist va a depender de los vecinos en el carrusel, no solamente de lo bueno que sean los items.

Los principales aportes de este paper son: los algoritmos bandit personalizados son mejores a los no-personalizados para la recomendación de carrusel. Aparte usaron el modelo cascada, en que se solo se usan las rewards de los ítems que los usuarios tuvieron la oportunidad de ver, no de todos los ítems.

