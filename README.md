# Hill_Climbimbing
Programa de rutas con modelo hill climbing

El *Hill Climbing* es un algoritmo de búsqueda local utilizado para problemas de optimización. Es un método heurístico que busca iterativamente la solución óptima al comenzar desde un punto inicial y realizar mejoras incrementales hasta alcanzar un punto donde no se puede encontrar una solución mejor en el vecindario inmediato.

### Funcionamiento básico
1. **Inicialización**: Comienza desde una solución inicial aleatoria.
2. **Evaluación**: Evalúa la calidad (o el costo) de la solución actual.
3. **Vecindad**: Genera soluciones vecinas (modificaciones pequeñas de la solución actual).
4. **Selección**: Si una solución vecina es mejor, se mueve hacia ella.
5. **Repetición**: El proceso se repite hasta que no haya vecinos mejores.

### Tipos de Hill Climbing
- **Simple Hill Climbing**: Acepta el primer vecino que mejora la solución actual.
- **Steepest-Ascent Hill Climbing**: Evalúa todos los vecinos y elige el mejor.
- **Stochastic Hill Climbing**: Selecciona un vecino aleatorio que sea mejor.

### Desventajas
- Puede quedar atrapado en máximos locales.
- Es sensible a la selección de la solución inicial.

Para evitar algunos de estos problemas, se pueden usar variantes como el *Simulated Annealing* o *Algoritmos Genéticos*, que tienen mayor capacidad para escapar de máximos locales y explorar mejor el espacio de soluciones.
