# Práctica 1 - K-Means & GMM
* Llenar información de estatura y edad en la pestaña normales(por favor llenar hoy mismo): Datos
* Utilizar estos datos(primera pestaña) para implementar :
  * Hard-clustering con k-means (no usar sklearn)
  * Soft-clustering con GMM usando sklearn(sklearn.mixture.GaussianMixture)
* Ejecutar al menos 5 experimentos para seleccionar el valor de “K”
  * Ambos métodos pueden usar el mismo valor de “K”
  * Analizar el centroide de cada cluster y determinar si es posible asignar una categoría  cada cluster
* Analizar y concluir si el método del codo es adecuado para este problema
* Usar los datos en la segunda pestaña(valtest(normales)) y estimar:
  * El cluster que k-means asigna cada uno.
  * La probabilidad de pertenecer a cada cluster según GMM.
* Usar GMM y simular 1000 observaciones para estimar(estimación de Monte Carlo) el valor esperado(promedio) de la función f :
f(edad, estatura) = estatura /edad
