Algoritmos Voraces (Greedy)
Cómo Funciona el Programa

El código implementa dos funciones principales:

1. Mochila Fraccional (`mochila_fraccional`):
   - Calcula cuánto valor aporta cada objeto por unidad de peso (su densidad).
   - Ordena los objetos de mayor a menor densidad.
   - Selecciona los mejores objetos: si caben completos los toma, y si falta espacio, toma exactamente la fracción necesaria para llenar la mochila al límite.

2. Cobertura de Antenas (`cobertura_antenas`):
   - Ordena las posiciones de las casas de menor a mayor.
   - Coloca cada antena estratégicamente en el punto más óptimo hacia la derecha para cubrir la primera casa descubierta.
   - Salta automáticamente las casas que ya quedan dentro de ese rango, logrando usar la menor cantidad de antenas posibles.

3. Como ejecutarlo :
   - Para ete trabajo utilize google colab
   - 1. abrir google colab
     2. crear nuevo cuaderno
     3. pegar el codigo del repositorio tarea_algoritmos.ipynb
     4. ejecutarlo
