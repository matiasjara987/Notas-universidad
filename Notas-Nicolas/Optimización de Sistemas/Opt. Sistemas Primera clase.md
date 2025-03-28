#Opt-sistemas

El curso se divide en 3 módulos:
1. Fundamentos de la optimización
2. Programación lineal
3. Teoría de juegos

El curso tiene 3 pruebas.

En este curso no vamos a programar, sino que vamos a tener que interpretar situaciones reales en donde tenemos que aplicar conocimientos y técnicas para abordar problemas tipo.

## ¿Qué son las operaciones?
Son procesos industriales. Se pueden integrar métodos matemáticos para modelar y crear sistemas.

## Fundamentos de la optimización

- **Investigación de operaciones**
	- " Investigación" => Aplicación de un método estructurado o científico.
	- "de Operaciones" => Sobre las operaciones. Toma de decisión para asignación de recursos escasos.
- El término "Investigación de operaciones", se acuñó durante la segunda guerra mundial. Militares britanicos solicitaron a científicos e ingenieros analizar varios problemas militares, como el despliegue de radares, control de vehículos, colocación de minas, entre otros.

Existen un montón de variables que requieren logística y análisis para encontrar una forma óptima y segura de lograr terminar un proceso.

## Concepto de modelo
Lo primero que tenemos que hacer para definir un problema de optimización, debemos definir un modelo.

> *"La realidad es tan compleja que debemos crear una simulación que la simplifique"* - Profe Enrique

Los modelos son representaciones de la realidad, pero simplificadas, porque el mundo tiene muchas variables que en ciertos entornos son irrelevantes o no deberían considerarse. 

Todos los modelos están sujetos a:
![[Screenshot 2025-03-21 at 13.45.37.png]]

Si yo necesito modelar cuántos trabajadores necesito para cierto labor, el resultado no puede dar negativo ni algún valor que no tenga sentido dentro del contexto real. Puede tener sentido matemático, pero no en la realidad.

## Métodos o pasos para un proceso de Investigación de Operaciones
Cuando se nos presenta un problema, debemos abarcarlo de una forma que sea ordenada y congruente. Por definición, se siguen los siguientes pasos:

1. Definición del problema de interés y recolección de datos relevantes.
2. Formulación de un modelo matemático que represente el problema.
3. Desarrollo de un procedimiento (basado en comutadora) ára derivar una solución para el problema a partir del modelo.
4. Prueba del modelo y mejoramiento de acuerdo a las necesidades.
5. Preparación para la aplicación del modelo prescrito para la administración
6. Implementación.

Un modelo tiene que ser matemático. No puede ser escrito con palabras

## Caso práctico:

![[Screenshot 2025-03-21 at 14.30.58.png]]

![[Screenshot 2025-03-21 at 14.31.27.png]]

1. Se definen las dos variables de decisión:
$x1$: Cantidad de $P1$ a producir
$x2$: Cantidad de $P2$ a producir

2. Se define una función objetivo:
$Z = x1 * 3000 + x2 * 5000$

3. Se definen restricciones
$x≥0$
$x≥0$

Restricción para planta 01: $x1*1[HR]≤4[HR]$
Restricción para planta 02: $x2*2[HR]≤12[HR]$
Restricción para planta 03: $x1*3[HR]+x2*2[HR]≤18[HR]$

4. Graficamos:
![[Screenshot 2025-03-21 at 14.48.46.png]]