Fecha: 28-03-2025
Asignatura: Minería de datos  #MineriaDeDatos
Docente: Eliecer Peña Ancavil
Correo:  [peliecer@docente.ubo.cl](mailto:%70el%69%65%63%65%72@%64oc%65%6e%74%65%2e%75%62o%2e%63%6c)

---------
## Nuestra agenda de hoy
1.  Revisión de clases anteriores 
2.  Qué es minería de datos
3. CRISP-DM
4. Paso a paso 
5. Evaluación
------
## Material de Clases 

#Link-google-colab  [Link](https://colab.research.google.com/drive/1ukzX2q23wZn09Sfn9qeMEtwFgCBzZIYm?usp=sharing)

----------

## ¿Qué es la minería de Datos?

La minería de datos es el proceso de descubrir patrones útiles en grandes volúmenes de información. Es como buscar pepitas de oro en una montaña de datos. No sabemos exactamente qué encontraremos, pero sabemos que hay valor oculto si sabemos dónde mirar.

Lo que hace la minería de datos no es simplemente mostrar gráficos o sacar promedios: es identificar relaciones, comportamientos y tendencias que muchas veces no son evidentes a simple vista.

--------
Breve Historia de la Minería de Datos 
- Años 60-80: Uso de estadística tradicional para analizar muestras pequeñas de datos.
- Años 80-90: Aparece el Buisness Intelligence. Se crean reporte y dashboards para apoyar decisiones de negocio.
- Años 90: Surgen técnicas de minería de datos para analizar grandes volúmenes de datos con algoritmos automáticos.
- 2000 en adelante: Evolución hacia el machine learning y la inteligencia artificial.
- Hoy: La minería de datos forma parte fundamental de la ciencia de datos. Se integra con programación, visualización, ética y negocio.

Antes analizábamos planillas de Excel, hoy los algoritmos analizan millones de datos en segundos. Pero lo importante sigue siendo el mismo: entender el comportamiento oculto que está en los datos.

--------

## Cross-Industry Standard Proccess for Data Mining

CRISP-DM es una metodología ampliamente utilizada en la ciencia de datos para guiar el proceso de análisis y minería de datos. Esta metodología es reconocida por su flexibilidad y enfoque estructurado, lo que la hace aplicable a una variedad de industrias y tipos de proyectos de datos.
![[Cross-industry-standard-img.png]]

------
##  Comprensión del negocio (Buisness Understanding)

Objetivo: Comprender claramente cuál es el problema que se necesita resolver. 
- Se identifican los objetivos desde el punto de vista de la organización, cliente o contexto. 
- Se traduce ese objetivo en una pregunta de datos.
- Se establece qué métricas van a definir el éxito del proyecto.

***Tenemos sensores de terremoto por todo Chile, queremos tener un sistema que sea capaz de detectar la posición y origen de un terremoto en base a la información requerida***

----------------------
## Comprensión de los Datos (Data Undestanding)
**Objetivo**: Conocer a fondo los datos disponibles.
- Se recolectan los datos disponibles. 
- Se analiza la calidad, el formato, la distribución, los valores faltantes, y se detectan errores.
- Se hacen las primeras visualizaciones y análisis exploratorios. 
Este paso ayuda a saber si los datos que tenemos realmente sirven para resolver el problema definido.

#Link-google-colab  [Link](https://colab.research.google.com/drive/1ukzX2q23wZn09Sfn9qeMEtwFgCBzZIYm?usp=sharing)

- **Hay 3 redes.** 
- **Cada una tiene una cantidad independiente de estaciones que puede variar.**
- **Cada estación tiene una cantidad independiente de sensores que miden cualquier cosa, temperatura, presión, cantidad de payasos azules, y terremotos.**
- **Una estación tiene al menos un conjunto de sensores que miden el desplazamiento en Norte, Este y Altura, Todos trabajando a una frecuencia especifica (20Hz a 200Hz)**

1 RED -> N cantidad de estaciones.
1 Estación -> N sensores. => Donde los sensores pueden medir => Temperatura, Presión, Terremotos.
1 Estación -> Posee  =< 1 conjunto de sensores que miden Norte, Este y Altura.

