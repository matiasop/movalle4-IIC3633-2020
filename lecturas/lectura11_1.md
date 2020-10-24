Deep Learning based Recommender System: A Survey and New Perspectives

En esta segunda parte los investigadores describen las redes neuronales recurrentes. Dicen que pueden ser usadas para lidiar con información secuencial, como texto y audio. También explican las aplicaciones de las máquinas de Boltzmann para la tarea de recomendación. Estas fueron de las primeras implementaciones de deep learning para sistemas recomendadores. Los sitemas basados en atención permiten filtrar las features irrelevantes para dejar solamente la información importante para la tarea. Estos modelos basados en atención permiten que las redes recurrentes puedan procesar información larga y con mucho ruido como habla humana. También explican otros tipos de modelos y hablan sobre explicación de recomendaciones con Deep Learning.

Existen varias aplicaciones interesante de las redes recurrentes. Por ejemplo, hay un sistema que predecía el siguiente ítem que iba a comprar un usuario basado en el historial de clicks. El problema que tenía este modelo es que solamente utilizaba la información de la sesión actual, no de sesiones pasadas. Otros modelos pudieron incorporar información adicional, como de sesiones pasadas. 

También me pareció interesante el tema de explicación de las recomendaciones. Uno de los problemas de los sistemas recomendadores que usan deep learning es que no se tiene la capacidad de dar razones sobre por qué se recomendó tal ítem a tal usuario. Sin embargo, la "explicabilidad" es una característica deseable de los sistemas recomendadores. A los usuarios les gusta que exista una razón clara por qué el sistema les recomendó un ítem. Los modelos de atención tienen mayores grados de interpretabilidad que otros tipos de modelos de deep learning, lo que los hace llamativos para utilizarlos en tarea de recomendación. Los modelos de atención son capaces de destacar los atributos más importantes que contribuyeron a la decisión que tomó. Los modelos "deep multi-task" también pueden contribuir a dar una mayor explicabilidad. Este tipo de modelos tiene tareas auxiliares que debe realizar aparte de mejorar las recomendaciones. El cumplimiento o no cumplimiento de estas tareas auxiliares puede dar mayor interpretabilidad a las recomendaciones.

Los aportes más destacables de esta parte del paper son las explicaciones de los modelos de recurrentes y de atención y sobre todo haber explicado los desafíos que deep learning debe resolver: explicabilidad de las recomendaciones, escalabilidad de las redes neuronales, capacidad de aumentar la profundidad de las redes y una unificación en la forma de evaluación de las distintas redes.