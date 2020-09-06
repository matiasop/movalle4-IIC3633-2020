# Combining Predictions for Accurate Recommender Systems

En este paper se investiga la combinación de distintos algoritmos de recomendación. El objetivo de combinar algoritmos es mejorar las predicciones, lo que se logra hacer. Los investigadores muestran distintas técnicas para hacer "blending" de los distintos algoritmos (linear blending, binned blending, gradient boosted decision trees y redes neuronales), cada una con sus ventajas y desventajas.

En la parte de resultados de la experimentación se muestran gráficos que muestran el RMSE obtenido, usando un distinto color (hue) para mostrar el porcentaje del total del dataset usado. El problema que tuve con este gráfico es que la diferencias en el RMSE de los distintos subsets parece minúscula, del orden de 0.001 entre los distintos subsets. Hubiese sido bueno si hubieran explicado si estas diferencias de accuracy eran importantes o significativas, porque al ojo parecería que no son significativamente diferentes. Con diferencias tan pequeñas se podría pensar que no es necesario probar distintas tantos subsets del dataset.

Un aspecto que consideré bueno del paper es que no solamente comparan distintos algoritmos de blending, sino que dan recomendaciones sobre si usar o no usarlos. Por ejemplo, los investigadores recomiendan nunca usar KRR ya que no se obtienen buenos resultados. En cambio, sí recomiendan usar una mezcla de redes neuronales y bagging por razones prácticas: tiene un bajo tiempo de recomendación. 

En este paper se mostaron distintas técnicas para combinar algoritmos de recomendación. Estas técnicas tienen la ventaja de que pueden mejorar las recomendaciones, pero tienen la desventaja de que tienen un costo en tiempo de procesamiento.
