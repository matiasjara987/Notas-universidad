#Opt-sistemas 

## Un pequeño resumen
Nuestro modelo matemático debe tener como máximo 2 variables de decisión, y estas deben estar directamente relacionadas con el modelado matemático final. 

Las restricciones que imponemos en nuestros modelos deben tener relación y sentido en el contexto. Las restricciones pueden ser de símbolo (ej. $x1>0$)

Cuando nosotros leamos "*Modele*", deberíamos llegar a algo parecido a esto:

*MAX* $3000x1+5000x2$
$S.A$
$x1≤4$
$x2≤6$
$3x1*2x2≤18$
$x1≥0$
$x2≥0$

Cuando nos pidan "*Grafique*", deberíamos llegar a algo parecido a esto:
![[IMG_0070.jpeg]]

Necesitamos identificar como se desplaza la recta de la función objetivo. ¿Cómo? Identificando los puntos frontera de nuestro modelo, en donde ya no se puede desplazar más porque no cumpliría las restricciones.

Forma vectorial y matricial => estudiar
## Algunas definiciones
- Una **SOLUCIÓN FACTIBLE** es aquella que satisface todas las restricciones al mismo tiempo.
- Una **SOLUCIÓN NO FACTIBLE** es aquella donde al menos una restricción no se cumple.
- La **REGIÓN FACTIBLE** es la región compuesta por todas las soluciones factibles.
- Una **SOLUCIÓN ÓPTIMA** es una solución factible que entrega el valor más "favorable" de la función objetivo

Una solución factible es un vértice (FEV) es una solución que se encuentra en una esquina de una región factible.

**Relación entre las soluciones óptimas y las soluciones FEV:**
- Considere cualquier problema de programación lineal con soluciones factibles y una región factible acotada En pocas palabras, debe tener un límite, ya que el infinito no es válido para considerarse como solución.
- El problema debe poseer soluciones FEV y a menos una solución óptima. Además, la mejor solución FEV debe ser una solución óptima. En pocas palabras, si muchas soluciones a un problema, una debe ser en un vértice
- Entonces, si un problema tiene exactamente una solución óptima, ésta debe ser una solución FEV.
- Si el problema tiene múltiples soluciones óptimas, al menos dos deben ser soluciones FEV.

## Problema tipo prueba

![[IMG_0071.jpeg]]

![[IMG_0072.jpeg]]

faltó una foto