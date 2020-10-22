# Deep Learning based Recommender System: A Survey and New Perspectives

En este paper los escritores revisan distintos modelos de recomendación basados en deep learning. Explican distintas clases de arquitectura de redes neuronales profundas. También explican por qué las redes neuronales tienen buenos resultados en tareas de recomendación: es bueno usar redes neuronales profundas cuando los datos son complejos o cuando hay un gran número de datos de input. También explican las limitaciones de los modelos de aprendizaje profundo: es difícil interpreta por qué tomó las decisiones y requiere muchos datos para funcionar bien.

Los investigadores hablan sobre las ventajas de las redes neuronales profundas en encontrar representaciones útiles de los datos. Me pareció interesante este caso de uso porque generalmente existe mucha información sobre los usuarios, como texto e imágenes, que con métodos tradicionales no se les puede dar mucho uso. Usando métodos tradicionales sería necesario encontrar a mano las features importantes de los datos, pero existen modelos de aprendizaje profundo que se pueden entrenar para encontrar los features más importantes de los datos. Me pareció interesante porque el aprendizaje profundo permite no solamente mejorar el rendimiento en comparación a métodos tradicionales, sino que también permite usar nuevos datos que previamente no estaban disponibles o su uso no era práctico/realista.

Las redes neuronales convolucionales pueden ser usadas para aprender features de imágenes, videos o texto. Los investigadores van varios ejemplos de papers en que se usan imágenes para mejorar sistemas recomendadores ya existentes. Por ejemplo, dan el caso de un recomendador de restaurantes, que extrae los features más importantes (comida y decoración) de las fotos para ayudar a los usuarios a encontrar restaurantes. En otro ejemplo se muestra el uso de redes neuronales convolucionales para obtener features de música en un sistema recomendador de música. Estas features luego son usadas para aliviar el problema de "cold start", cuando la música aun no tiene recomendaciones y mejorar las recomendaciones.

El aspecto que consideré más importante de esta recopilación de papers sobre los usos de deep learning en recomendación es que existen usos muy variados que se le puede dar a los modelos de deep learning. Estos modelos si bien pueden ser útiles al momento de mejorar el rendimiento de recomendación, también tienen pueden tener otros usos que no habrían sido posibles con métodos tradicionales.