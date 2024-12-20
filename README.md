# PyMath-Lab

A través de los gráficos generados, hemos podido observar cómo diversas características del estudiante, como el género, la raza/etnia, la educación de los padres, el tipo de almuerzo y la preparación para el examen, influyen en las puntuaciones de matemáticas. En general, los resultados sugieren que:

- El género y la preparación para el examen tienen un impacto considerable en las puntuaciones de matemáticas.
- Existen variaciones en el rendimiento académico entre los grupos raciales/étnicos, posiblemente relacionadas con desigualdades en recursos.
- Los estudiantes con almuerzo estándar tienden a obtener mejores resultados, lo que podría estar vinculado a factores socioeconómicos.

Estos hallazgos resaltan la importancia de implementar estrategias para abordar desigualdades y mejorar el éxito académico.

## Tabla de contenidos

1. [Nombre](#PyMath-Lab)
2. [Descripción](#Breve-descripción-del-proyecto)
3. [Arquitectura](#Arquitectura-del-proyecto)
4. [Limpieza de datos](#Limpieza-de-datos)
6. [Proceso de desarrollo](#Proceso-de-desarrollo)
7. [Estadísticos](#Estadísticos)
8. [Tecnologías usadas](#Tecnologías-usadas)
9. [Funcionalidad](#Funcionalidad)

---

# PyMath-Lab

## Breve descripción del proyecto

Este análisis se basa en un conjunto de datos que estudia el impacto de factores personales, sociales y educativos en las puntuaciones de exámenes de matemáticas. Se analizaron variables como género, raza/etnia, nivel educativo de los padres, tipo de almuerzo y participación en cursos de preparación.

![image](https://github.com/user-attachments/assets/ceebd7fc-33a9-43c5-8a33-36af4f5f3458)

![image](https://github.com/user-attachments/assets/936db9d4-54af-4720-8be3-3f32110c8ab7)

---

## Arquitectura del proyecto

Nuestro proyecto se organiza a grandes rasgos de la siguiente forma:

![image](https://github.com/Guill2/PyMath-Lab/blob/main/IMGs/Arquitectura_PyCode.png)

---

## Limpieza de datos

![image](https://github.com/user-attachments/assets/5ed8450a-cd8a-4fac-a08e-a91fd0904d9c)

---

## Proceso de desarrollo

1. **Búsqueda del dataset**: Selección de un conjunto de datos relevante en Kaggle.  
   [Fuente del dataset](https://www.kaggle.com/datasets/sudhanshu2198/analyzing-exam-scores)

2. **Limpieza de datos**: Eliminación de valores nulos, duplicados y corrección de errores.

3. **Preprocesamiento**: Estandarización de datos categóricos y análisis preliminar.

4. **Análisis exploratorio**: Identificación de patrones y relaciones mediante gráficos y estadísticas.

5. **Visualización**: Creación de gráficos para comunicar hallazgos clave.

6. **Documentación**: Elaboración de conclusiones basadas en los resultados obtenidos.

---

## Estadísticos

A continuación, se describe cada una de las columnas presentes en el dataset:

- **gender**: Género del estudiante (masculino/femenino).
- **race/ethnicity**: Grupo racial o étnico del estudiante.
- **parent_education_level**: Nivel educativo de los padres.
- **lunch**: Tipo de almuerzo proporcionado (estándar o gratis/reducido).
- **test_prep_course**: Participación en un curso de preparación para el examen.
- **math**: Puntuación obtenida en matemáticas (0 a 100).

---

## Tecnologías usadas

- **Lenguaje**: Python.
- **Bibliotecas**: Pandas, NumPy, Matplotlib, Seaborn, Sklearn, Warnings.

---

## Funcionalidad

Una vez terminado nuestro análisis de datos hemos implementado una página web en donde se muestran de una forma más ordenada nuestros gráficos finales.

![image](https://github.com/Guill2/PyMath-Lab/blob/main/IMGs/Pag1.png)
![image](https://github.com/Guill2/PyMath-Lab/blob/main/IMGs/pag2.png)

[Enlace de nuestra página web](https://guill2.github.io/PyMath-Lab/)

