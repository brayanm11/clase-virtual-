# Modelamiento mediante Diagramas de Bloques
Los diagramas de bloques constituyen una herramienta fundamental en el modelamiento y análisis de sistemas dinámicos. Su utilidad radica en representar visualmente la relación funcional entre los distintos componentes de un sistema, facilitando el diseño, la comprensión y la implementación de sistemas de control. Este tipo de modelamiento se basa en el uso de funciones de transferencia para representar los elementos del sistema y su interacción a través de señales de entrada y salida. Se aplica comúnmente en ingeniería eléctrica, mecánica, térmica, hidráulica, y procesos químicos, permitiendo una transición eficiente entre el modelo físico y su análisis computacional.
## 1. Subtítulos
1.1 Introducción al modelamiento de sistemas dinámicos

1.2 ¿Qué es un diagrama de bloques?

1.3 Elementos fundamentales de los diagramas de bloques

1.4 Diagramas de bloques aplicados a diferentes dominios físicos

1.5 Transformación de ecuaciones diferenciales a diagramas de bloques

1.6 Ventajas y limitaciones del modelamiento por bloques

## 2. Definiciones
🔑 Sistema físico: conjunto de elementos interconectados que interactúan mediante el intercambio de energía y/o materia.

🔑 Modelamiento: proceso de construcción de una representación matemática o gráfica de un sistema real.

🔑 Diagrama de bloques: representación gráfica de un sistema donde cada bloque representa una operación matemática o función de transferencia.

🔑 Función de transferencia: cociente de la transformada de Laplace de la salida sobre la transformada de Laplace de la entrada, bajo condiciones iniciales nulas.

🔑 Nodo de suma: elemento que realiza la suma algebraica de señales que entran al sistema.

🔑 Punto de ramificación: punto desde el cual una señal se dirige a varios bloques simultáneamente.


## 3. Subsecciones
###3.1. Modelado de sistemas de mezcla

En los sistemas de mezcla, se considera un tanque donde entran dos flujos con distintas concentraciones. Se busca obtener una expresión que modele la concentración de la mezcla dentro del tanque a lo largo del tiempo, considerando el balance de masa.

###3.2. Modelado de sistemas térmicos

El modelado térmico considera la transferencia de calor entre un cuerpo y su entorno. A través de la ley de conservación de energía y elementos como resistencia térmica y capacidad térmica, se forma una ecuación diferencial que se transforma en una función de transferencia.

###3.3. Modelado de sistemas eléctricos equivalentes

El modelamiento eléctrico se utiliza como analogía para representar sistemas de otros dominios (ej: masa-resorte-amortiguador en forma de circuitos RLC) facilitando su análisis mediante componentes conocidos como resistencias, inductancias y capacitancias.

###3.4. Diagramas de bloques con retroalimentación

Los diagramas de bloques permiten representar la realimentación (feedback) mediante la conexión de una parte de la salida nuevamente a la entrada. Esta configuración es esencial en sistemas de control y regulación.
## 4. Ejemplos
Si en algún caso pretende dar un ejemplo explicativo ya sea a través de texto o através de ecuaciones matemáticos, utilizar la palabra 'Ejemplo' seguido de una numeración consecutiva dentro de la clase. Utilice el emoji 💡 antecediendo la palabra.

## 5. Ecuaciones
Para la edición de ecuaciones debe utilizar la etiqueta '$$' al comienzo y final de la ecuación para que la ecuación quede centrada ocupando una línea. Si se quiere que la ecuación quede integrada en el texto debe utilizar la etiqueta '$' al comienzo y final de la ecuación. Las ecuaciones pueden ser editadas utilizando el código LATEX, en el siguiente enlace encuentran un editor de ecuaciones que les genera el código. http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp . Sin embargo hay muchas otras herramientas que pueden utilizar para esto.

💡**Ejemplo 1:** si se va a representar la ecuación de la ley de Ohm se puede mostrar así $R=\frac{V}{I}$ o también,

$$R=\frac{V}{I}$$

$${
\begin{pmatrix*}[r]
63 & 71 & 2\\
6 & 829 & 12\\
599 & 9 & 361
\end{pmatrix*}
}={\begin{pmatrix*}[r]
63 & 71 & 2\\
6 & 829 & 12\\
599 & 9 & 361
\end{pmatrix*}}$$


## 6. Figuras
Todas las figuras que incluya deben ser generadas por ustedes, **no utilizar las figuras de las presentaciones**. Para incluir figuras puede seguir los siguientes pasos:
* Primero escribimos ![]().
* Después escribimos, dentro de los corchetes, el texto alternativo. Este es opcional y solo entra en acción cuando no se puede cargar la imagen correctamente.
* Después escribimos, dentro de los paréntesis, la ubicación del archivo (ya sea una url o una ubicación dentro de algun folder local). Se recomienda poner las imágenes en una carpeta que se llame imágenes dentro del repositorio github para que no tengan problemas al cargar las imágenes.

💡**Ejemplo 2:**

![Figura de prueba](images/plantilla/Captura2.PNG)

Figura 1. Figura de prueba

Incluya la respectiva etiqueta a modo de descripción de la figura y mantenga numeración consecutiva para todas las figuras de la clase.

## 7. Tablas
En caso de necesitar la inclusión de tablas para organizar información se recomienda el uso de la herramienta del siguiente enlace https://www.tablesgenerator.com/markdown_tables , la cual permite organizar la información dentro de la tabla y genera el código markdown automáticamente:

💡**Ejemplo 3:** 

| **Resultado** | **x = número de intentos hasta primer éxito** |
|---------------|-----------------------------------------------|
|       S       |                       1                       |
|       FS      |                       2                       |
|      FFS      |                       3                       |
|      ...      |                      ...                      |
|    FFFFFFS    |                       7                       |
|      ...      |                      ...                      |

Tabla 1. Tabla de ejemplo

Cada tabla debe llevar la etiqueta que describa su contenido y numeración consecutiva para todas las tablas

## 8. Código
Teniendo en cuenta que el curso requiere del desarrollo de código matlab, c, c++ u otro. Si requiere incluir pequeños segmentos de código en los apuntes hágalos de la siguiente manera:

💡**Ejemplo 4:**
```
var sumar2 = function(numero) {
  return numero + 2;
}
```

## 9. Ejercicios
Deben agregar 2 ejercicios con su respectiva solución, referentes a los temas tratados en cada una de las clases. Para agregar estos, utilice la etiqueta #, es decir como un nuevo título dentro de la clase con la palabra 'Ejercicios'. Cada uno de los ejercicios debe estar numerado y con su respectiva solución inmediatamente despues del enunciado. Antes del subtitulo de cada ejercicio incluya el emoji 📚

## Rúbrica
| 0-1                                                                                   | 1-2                                                                                  | 2-3                                                                                                                                                                               | 3-4                                                                                                                                                                       | 4-5                                                                                                                                                                               |
|---------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Presenta menos del 10% de los temas o no presenta por  el medio y formato  solicitado | Presenta menos del 40% de los temas solicitados, y  cumple parcialmente la plantilla | Presenta menos del 60% de los temas solicitados (con descripciones, gráficos tablas, etc), y cumple  parcialmente la plantilla. No presenta la totalidad  de ejercicios resueltos | Presenta menos del 80% de los temas solicitados (con descripciones, gráficos, tablas, etc) y cumple con  la plantilla. No presenta  la totalidad de ejercicios  resueltos | Presenta el 100% de los temas vistos en clase (con descripciones, gráficos, tablas, etc), siguiendo totalmente la plantilla. presenta la  totalidad de los ejercicios solicitados |

## 10. Conclusiones
Agregue unas breves conclusiones sobre los temas trabajados en cada clase, puede ser a modo de resumen de lo trabajado o a indicando lo aprendido en cada clase

## 11. Referencias
Agregue un subtítulo al final donde pueda poner todas las referencias consultadas incluyendo el origen o fuente de los ejercicios planteados. Tambien dentro del texto referencie los textos o artículos consultados y las figuras y tablas dentro de la explicación de las mismas.
