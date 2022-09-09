# Proyecto 02

## Desafio

El segundo proyecto tendrá más libertad que el primero. Esto es porque queremos que tengan un proyecto en sus portafolios que les interese o se relacione con la industria en la que quieren trabajar.

La tarea para esta semana es proponer dos posibles conjuntos de datos que les gustaría trabajar para el proyecto 2.  

Escogerán el conjunto de datos de primera opción, y un conjunto de datos de reserva en caso de que el primero propuesto no se apruebe.  

Estos datos pueden proceder de cualquier fuente y ser sobre cualquier tema con estas limitaciones:

* los datos deben estar disponibles para su uso (es su responsabilidad garantizar que la licencia indique que pueden utilizarlos)
* los datos deben ser adecuados para un ambiente profesional
* los datos NO deben contener información personal
* los datos NO deben ser de un conjunto de datos usados en alguna tarea o clase del curso

Asegúrense de seleccionar un conjunto de datos con el que sea razonable trabajar en el tiempo que nos queda. Piensen qué preguntas podrían responder con el conjunto de datos que seleccionen. 

Deben proponer dos conjuntos de datos que tengan cada uno un componente de aprendizaje supervisado. Pueden elegir un problema de regresión o clasificación para cada conjunto de datos propuesto.  



## DataScience Framework

A continuación se presenta un esquema de cómo será presentado el trabajo:


1. **Definir el problema:** Si la solución es ciencia de datos, aprendizaje automático, análisis predictivo, inteligencia comercial o cualquier otra palabra de moda, ¿cuál es el problema? Como dice el refrán, _no pongas el carro delante del caballo_. Problemas antes de los requisitos, requisitos antes de las soluciones, soluciones antes del diseño y diseño antes que la tecnología. Con demasiada frecuencia, saltamos rápidamente a la nueva tecnología, herramienta o algoritmo brillante antes de determinar el problema real que estamos tratando de resolver.


2. **Reúna los datos:** John Naisbitt escribió en su libro Megatrends de 1984 (sí, 1984), "nos ahogamos en datos, pero ansiamos conocimiento". Entonces, lo más probable es que los conjuntos de datos ya existan en alguna parte. , en algún formato. Puede ser externo o interno, estructurado o no estructurado, estático o transmitido, objetivo o subjetivo, etc. Como dice el refrán, no hay que reinventar la rueda, solo hay que saber dónde encontrarla. En el siguiente paso, nos preocuparemos por transformar los "datos sucios" en "datos limpios".


3. **Preparar datos para el consumo:** Este paso a menudo se conoce como disputa de datos, un proceso necesario para convertir datos "salvajes" en datos "manejables". La disputa de datos incluye la implementación de arquitecturas de datos para el almacenamiento y el procesamiento, el desarrollo de estándares de gobernanza de datos para la calidad y el control, la extracción de datos (es decir, ETL y web scraping) y la limpieza de datos para identificar puntos de datos aberrantes, faltantes o atípicos.


4. **Realizar análisis exploratorio:** Cualquiera que haya trabajado alguna vez con datos sabe, basura dentro, basura fuera (GIGO). Por lo tanto, es importante implementar estadísticas descriptivas y gráficas para buscar posibles problemas, patrones, clasificaciones, correlaciones y comparaciones en el conjunto de datos. Además, la categorización de datos (es decir, cualitativa frente a cuantitativa) también es importante para comprender y seleccionar la prueba de hipótesis o el modelo de datos correctos.


5. **Modelar datos:** Al igual que las estadísticas descriptivas e inferenciales, el modelado de datos puede resumir los datos o predecir resultados futuros. Su conjunto de datos y los resultados esperados determinarán los algoritmos disponibles para su uso. Es importante recordar que los algoritmos son herramientas y no varitas mágicas ni balas de plata. Aún debe ser el maestro artesano (wo)man que sabe cómo seleccionar la herramienta adecuada para el trabajo. Una analogía sería pedirle a alguien que le entregue un destornillador Philip, y le entregan un destornillador de cabeza plana o, peor aún, un martillo. En el mejor de los casos, muestra una completa falta de comprensión. En el peor de los casos, hace imposible completar el proyecto. Lo mismo es cierto en el modelado de datos. El modelo incorrecto puede conducir a un rendimiento deficiente en el mejor de los casos y a una conclusión incorrecta (que se utiliza como inteligencia procesable) en el peor de los casos.


6. **Valide e implemente el modelo de datos:** Después de haber entrenado su modelo en función de un subconjunto de sus datos, es hora de probar su modelo. Esto ayuda a garantizar que no haya sobreajustado su modelo ni lo haya hecho tan específico para el subconjunto seleccionado, que no se ajuste con precisión a otro subconjunto del mismo conjunto de datos. En este paso, determinamos si nuestro [modelo se sobreajusta, generaliza o no se ajusta a nuestro conjunto de datos](http://docs.aws.amazon.com/machine-learning/latest/dg/model-fit-underfitting-vs-overfitting.html ).


7. **Optimizar y crear estrategias:** Este es el paso del "hombre biónico", en el que repites el proceso para hacerlo mejor... más fuerte... más rápido de lo que era antes. Como científico de datos, su estrategia debe ser externalizar las operaciones de desarrollo y la plomería de aplicaciones, de modo que tenga más tiempo para concentrarse en las recomendaciones y el diseño. Una vez que pueda empaquetar sus ideas, esta se convierte en su tasa de "cambio de moneda".