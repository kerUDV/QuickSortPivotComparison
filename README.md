# Comparación de QuickSort: Pivote Aleatorio vs Pivote Medio

## Descripción

En este proyecto se implementaron dos versiones del algoritmo QuickSort en Java:

1. QuickSort con pivote aleatorio (randomPivot)
2. QuickSort con pivote en la posición media del subarreglo (middlePivot)

Ambas implementaciones utilizan el esquema de partición de Lomuto.

Se realizaron pruebas con diferentes escenarios:
- ordered (ordenado)
- reversed (inverso)
- random (aleatorio)
- nearlySorted (casi ordenado)

Se probaron diferentes tamaños del arreglo:
100, 500, 1000, 2000 y 5000 elementos.

---

## Métricas evaluadas

Se midieron las siguientes métricas:

- Número de comparaciones
- Número de intercambios (swaps)
- Tiempo de ejecución en nanosegundos

Para el análisis comparativo se utilizaron principalmente las comparaciones,
ya que el tiempo puede variar dependiendo del entorno de ejecución.

---

## Resultados

En los escenarios ordered y reversed se observó que:

- El pivote medio generalmente realizó menos comparaciones.
- El pivote aleatorio mostró un comportamiento más estable en escenarios aleatorios.

En términos generales, ambas implementaciones mantienen una complejidad promedio de O(n log n),
pero la selección del pivote influye en la eficiencia práctica dependiendo del tipo de datos.

---

## Conclusión

La selección del pivote impacta directamente el desempeño del algoritmo QuickSort.

- El pivote medio puede ser más eficiente cuando los datos tienen cierta estructura.
- El pivote aleatorio reduce la probabilidad de caer en el peor caso y ofrece mayor estabilidad.

No se observan diferencias en la complejidad teórica,
pero sí diferencias prácticas en el número de comparaciones dependiendo del escenario.

## Prompt utilizado con ChatGPT
https://chatgpt.com/s/t_699fd32820ec819185ca26242f3868a5
