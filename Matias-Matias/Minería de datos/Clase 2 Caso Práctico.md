### Ejemplo
Supongamos que quieres descargar datos del canal **HLZ** de la estación **ANTU**, red **C**, para el **1 de marzo de 2023** entre las **00:00 y 01:00 UTC**, usando el servidor IRIS:

[Link]([service.iris.edu/fdsnws/dataselect/1/query?net=C&sta=ANTU&cha=HLZ&start=2023-03-01T00:00:00.000Z&end=2023-03-01T01:00:00.000Z”](https://service.iris.edu/fdsnws/dataselect/1/query?net=C&sta=ANTU&cha=HLZ&start=2023-03-01T00:00:00.000Z&end=2023-03-01T01:00:00.000Z%E2%80%9D))

![[Pasted image 20250329101954.png]]
#### Tomamos los 3 sensores que mas se parecen
![[Pasted image 20250329102011.png]] 

----------
## Preparación de los Datos (Data Preparation)
¿Entonces con esos datos calcular donde ocurrió un terremoto debe ser sencillo no?
Porque el terremoto tiene un punto donde pasa y la energía que libera es lineal, obvio.
![[Pasted image 20250329102213.png]]

### ¿Cómo que el terremoto tiene 2 ondas y se mueven a una velocidad distinta?
![[Pasted image 20250329102311.png]]
Fuente: [Link](https://ecampusontario.pressbooks.pub/geology/chapter/9-1-understanding-earth-through-seismology/)
### ¿Cómo que las ondas rebotan como la luz en distintos puntos debido a cambios en el manto terrestre y generan interferencia?
![[Pasted image 20250329102601.png]]

## Modelado (Modeling)
**Objetivo**: Aplicar técnicas de minería de datos para generar conocimiento a partir de los datos.
- Se eligen los algortimos adecuados
	- Clasificación
	- Clustering
	- Regresión
	- Etc
- Se entrenan modelos y se ajustan parámetros.
- Se prueban distintos enfoques para ver cuál tiene mejor desempeño.
Aquí se utilizan herramientas como **Scikit-learn, XGBoost, etc.** Aunque en contextos simples también se pueden usar herramientas no programáticas.

[¿Quieren ver cientos de líneas de código y de frustación? ](https://colab.research.google.com/drive/1-4AnwKhWUfgEvFP9G6XHZl7PnRM4CsEz?usp=sharing)


## Evaluación (Evaluation)

**Objetivo**: Determinar si el modelo cumple con los objetivos del negocio.
- Se revisa el desempeño del modelo con métricas (precisión, recall, AUC, etc.).
- Se valida si responde bien al problema definido.
- Se toman decisiones: 
	- ¿Es útil?
	- ¿Es comprensible?
	- ¿Es ético?
Es una etapa crítica: Un modelo puede tener buena precisión pero no ser útil o ético.

![[Pasted image 20250329110703.png]]
A partir de los datos de “movimiento angular” la idea era obtener una especie de regresión lineal que me permitiera para una distancia al terremoto, profundidad, cual fue la magnitud del terremoto como tal, con lo cual obtuve este grafico, pero emmmm no esta bien.

## Conclusión  
![[Cross-industry-standard-img.png]]

- Dado que no se ha encontrado información real o relevante que aporte valor al análisis, es necesario regresar a la etapa de Comprensión para entender mejor el contexto y así desarrollar un producto verdaderamente útil.
