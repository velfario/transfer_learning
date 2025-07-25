Transfer learning es una técnica en la que se usa una red neuronal pre entrenada en una tarea para realizar una tarea similar. En este trabajo se usa la red ResNet50, una red neuronal entrenada para identificar animales, para clasificar frutas. el proceso de transfer learning es el siguiente:
- se toma una red neuronal pre entrenada.
- se agrega una última capa para la identificación de las nuevas clases.
- se congelan las primeras capas de la red y solo se modifican los parámetros de las últimas capas, se utiliza una taza de aprendizaje muy baja (fine tunning)
- se evalúa la red con normalidad.

Transfer learning nos permite tomar redes neuronales que han demostrado tener un buen desempeño y usarlas en tareas distintas para propósitos particulares.
