# IIO422: Hidrología - Ayudantía 05

JMV

## Preámbulo

Esta ayudantía tiene como objetivo reforzar el trabajo autonomo entorno a la plataforma Git, donde cada estudiante pueda clonar este repositorio en sus dipositivos local para luego subir la resolución de las preguntas presentadas a continuación en un pequeño informe.

------------------------------------------------------------------------

## Parte 1: Manejo de datos espaciales y temporales

En la carpeta `01_data` se encuentran datos de precipitación espacial para Chile continental, cada estudiante deberá recortar el producto para la cuenca asiganada en la `Tabla 1`, para ello descargar la delimitación disponible en CamelsCL, opcionalmente se puede utilizar la libreria RcamelsCL (ver documentación).

Posteriormente, deberán obtener una serie temporal de la precipitación de la cuenca a traves de su recorte espacial y realizar un analisis exploratorio de datos que pueda responder las preguntas solicitadas en el apartado de `Informe`.

| Estudiante    | Código BNA/Camels-Cl |
|---------------|----------------------|
| D. Garrido    | 9402001              |
| A. LLanquinao | 9123001              |
| S. Lobos      | 7350001              |
| J. Millan     | 7104002              |
| V. Rapiman    | 6028001              |
| F. Ravanal    | 5406001              |
| A. Vásquez    | 5702001              |

: Tabla 1: Asignación de cuenca

El script deberá ser guardado en la carpeta `Rscripts` bajo el nombre tipo `APELLIDO.R`

## Parte 2: Informe

1.  Describa qué es CR2MET, su resolución espacial y temporal, y qué variable de precipitación está utilizando exactamente.

2.  ¿Qué formato tienen los archivos de CR2MET y qué paquete de R utilizó para importarlos?

3.  ¿Cómo delimitó su zona de estudio o cuenca, y qué función utilizó para realizar el recorte espacial?

4.  ¿Cómo extrajo la serie de tiempo para el promedio de la cuenca, y qué rango de fechas cubre su análisis?

5.  ¿Cuál es la precipitación media anual y mensual de su zona de estudio? Realice una descripción estadistica de la serie anual y mensual

6.  ¿Qué tipo de gráfico utilizó para mostrar la variabilidad espacial y cuál para la variabilidad temporal?

7.  ¿Detectó valores faltantes en sus datos? ¿Cómo los trató?

8.  Grafique un boxplot de la precipitación mensual o anual. Describa qué observa respecto a la dispersión de los datos y la presencia de posibles valores atípicos.

9.  ¿Qué criterio utilizó para considerar un valor como atípico? Discuta la implementación considerando que la precipitación no es una variable simétrica.

10. Aplique al menos dos tests de homogeneidad a la serie de precipitación media anual para detectar posibles quiebres o cambios de media en el tiempo.

11. Aplique un test de estacionariedad e indique qué paquete de R utilizó.

12. Interprete los resultados en conjunto: ¿la serie es homogénea y estacionaria, o se detecta un quiebre o tendencia?

------------------------------------------------------------------------

## Resultados

### Elaboración de Informe

Cada estudiente deberá redactar un informe simple en formato `Markdown` respondiendo las preguntas antes solicitados en la carpeta `05_docs` donde deberá guardarlo de la manera `APELLIDO.md`. Todas las figuras y tablas necesarias para la elaboración del informe deberán estar presentes en una subcarpeta dentro de `03_outputs`, de la forma `03_outputs/APELLIDO/`

#### Anexos: Declaración de uso de Inteligencia Artificial

El uso de inteligencia artificial (IA) está permitido siempre y cuando se realice de la forma estipulada en el programa de asignatura, a modo de transparentar el uso de IA los estudiantes deberán declarar en esta sección:

- Qué herramientas de inteligencia artificial utilizaron (nombre y versión, si corresponde).
- Para qué etapas del trabajo las utilizaron (por ejemplo: redacción de código en R, depuración de errores, interpretación de resultados, redacción de texto, búsqueda de información, generación de gráficos, etc.).
- Cómo las utilizaron, especificando el grado de intervención humana posterior (por ejemplo: revisión y corrección manual del código generado, verificación de resultados, edición del texto propuesto).
- Qué partes del informe fueron elaboradas completamente sin apoyo de IA.

Esta declaración no afecta negativamente la evaluación por el uso de estas herramientas, pero su omisión o falta de transparencia sí será considerada una falta de honestidad académica.

------------------------------------------------------------------------

## Bonificación

Para los informes subidos antes de las 15:00 hrs del día viernes 02 de Octubre de 2026, se converserá con el profesor de la asigntaura la opción de entregar bonificación de decimas para la parte práctica del curso dependiendo de la calidad del producto entregado.

------------------------------------------------------------------------

Cualquier consulta o problemas contactarme al correo j.moran02\@ufromail.cl